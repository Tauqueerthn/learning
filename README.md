pipeline {
   agent any

   stages {
      stage('compile') {
         steps {
            echo 'Hello Tauqueer hussain1'
         }
      }
      stage('build') {
         steps {
            echo 'Hello Tauqueer hussain2'
         }
      }
      stage('deploy') {
         steps {
            echo '<html>

<body>

  <h1>Simple SVG example</h1>

  <svg width="1000" height="1000">

  <circle cx="100" cy="100" r="90" stroke="blue" stroke-width="5" fill="yellow" />

  </svg>

</body>

</html>'
         }
      }
   }
}
