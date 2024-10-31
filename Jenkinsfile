node {
  stage 'Checkout'
  checkoutscm

  stage 'Build'
  sh 'javac HellowWorld.java'

  stage 'Test'
  sh 'java HellowWorld | grep Hello'
}
