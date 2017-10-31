# JenkinsScripts
My jenkins script for TRACIM

Plugin i use : https://github.com/codeclou/jenkins-github-webhook-build-trigger-plugin


Pipeline number : 3

__________________________________________________________________________
Pipeline name : Scenario1

"Le scénario n°1 se déclenche à chaque "push" sur la branche github "develop" du projet tracim.
Il a pour but de publier ll'image Docker algoo/tracim_testing : latest."
__________________________________________________________________________
Pipeline name : Scenario2

"Le scénario n°2 se déclenche suite au scénario n°1, si celui-ci se termine correctement.
Il a pour but de publier l'image Docker algoo/tracim:unstable"
__________________________________________________________________________
Pipeline name : Scenario3

"Le scénario n°3 se déclenche lorsqu'un tag est crée sur la branche master du projet github tracim.
Il a pour but de publier l'image Docker algoo/tracim:<"$tag">"
__________________________________________________________________________
