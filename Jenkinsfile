node {
	stage 'Checkout'
		checkout scm
        stage 'Build'
                sh 'mkdir build >/dev/null 2>&1'
                sh 'cd build'
                sh 'cmake .. && make'
}
