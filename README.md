# GIT FLOW

## Iniciar um projeto
git flow init

***

## Para criar uma nova feature
git flow **feature** start nome-da-feature

## Quando terminar a feature
git flow **feature** finish nome-da-feature

***

## Para criar um hotfix
git flow **hotfix** start nome-da-fix
> cria um branch de hotfix apartir do **master**

## Quando terminar o hotfix
git flow **hotfix** finish nome-da-fix
>automaticamente faz o merge com o master e develop

***

## Para iniciar a Release
git flow **release** start 1.0.0

## Quando terminar a Release
git flow **release** finish '1.0.0'

### fim
 


