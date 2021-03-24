# GUIDE FOR HOW DEPLOY PROJECT TO SERVER USING SSH ACCESS

## Creating test environment
 - Creating docker container with ssh.[docker image](https://github.com/s1ntaxe770r/SSH-dockerfile)
   
    docker pull ghcr.io/s1ntaxe770r/image:latest

## Github actions to deploy usig ssh
  [Run SSH command action](https://github.com/marketplace/actions/run-ssh-command)
    - [workflow example](https://github.com/garygrossgarten/github-action-ssh/blob/master/.github/workflows/ssh-example-workflow.yml)
  [SSH for GitHub Actions](https://github.com/appleboy/ssh-action#-ssh-for-github-actions)
    - [workflow example](https://github.com/appleboy/ssh-action#usage)
    - [all properties](https://github.com/appleboy/ssh-action/blob/master/action.yml)
  


## Login to server using ssh:
    (http://www.linuxproblem.org/art_9.html)