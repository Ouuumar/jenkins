node {
    checkout scm

    docker.withRegistry('https://registry.example.com', 'credentials-id') {

        def customImage = docker.build("bigwwale/jenkinsed-node-pipeline")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}