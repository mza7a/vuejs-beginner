pipeline {
	agent any

	stages {

		stage("build") {
			when {
				expression {
					BRANCH_NAME == 'develop'
				}
			}
			steps {
				echo "This is the part where we build the application"
			}
		}

		stage("test") {
			steps {
				echo "This is the part where we test the application"
			}
		}

		stage("deploy") {
			steps {
				echo "This is the part where we deploy the application"
			}
		}
	}
}
