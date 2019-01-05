node('master') {
    // some block
	stage('Preparation') {
		// some block
		git credentialsId: 'af5e0618-1d18-489f-9d64-97e776dafd1a', url: 'http://172.28.64.1:9001/kbfg-test/springmvctest.git'
	}
	
	stage('Build') {
		// some block
		withMaven(maven: 'M3', tempBinDir: '') {
			// some block
			sh 'mvn -Dmaven.test.failure.ignore clean package'
		}
	}
}
