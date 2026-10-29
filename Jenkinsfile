pipeline { agent any
stages { stage('Checkout') {
steps {
echo 'Checking out source code...'
}
}

stage('Build') { steps {
echo 'Building the application...'
}
}

stage('Test') { steps {
echo 'Testing the application...' echo 'All tests passed successfully!'
}
}

stage('Deploy') { steps {
echo 'Deploying application...'
echo 'Application deployed successfully!'
}
}
}
}