node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/repositories', 'mohan0607') {

        def customImage = docker.build("mohan0607/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
