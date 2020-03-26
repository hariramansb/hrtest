node {
checkout scm
docker.withRegistry('https://registry.hub.docker.com', 'docker') {
def customImage = docker.build("hariramans/testapp")
/* Push the container to the custom Registry */
customImage.push()
}
}
