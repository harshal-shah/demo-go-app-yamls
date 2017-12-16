node 
{


    checkout scm 

stage 'Deploy'
  sh("kubectl apply -f ./manifests/ -n ${env.BRANCH_NAME}")

}
