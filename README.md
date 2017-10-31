# JenkinsScripts
My jenkins script for TRACIM

Plugin i use : https://github.com/codeclou/jenkins-github-webhook-build-trigger-plugin


Pipeline number : 3

__________________________________________________________________________
Pipeline name : Scenario1

__________________________________________________________________________
Pipeline name : Scenario2

"Le scénario n°2 se déclenche suite au scénario n°1, si celui-ci se termine correctement.
Il a pour but de publier l'image Docker algoo/tracim:unstable"
__________________________________________________________________________
Pipeline name : Scenario3

"Le scénario n°3 se déclenche lorsqu'un tag est crée sur la branche master du projet github tracim.
Il a pour but de publier l'image Docker algoo/tracim:<"$tag">"
__________________________________________________________________________
