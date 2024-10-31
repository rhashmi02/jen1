node {
 stage 'Checkout'
 checkout scm

 stage 'Build'
 sh 'javac HellowWorld.java'

 stage 'Test'
 sh 'java HellowWorld | grep Hello'
}
