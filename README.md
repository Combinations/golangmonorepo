# golangmonorepo
When first working with Golang one of the difficulties I ran into was not knowing how to structure my project...
The purpose of this repo is to provide an example monolithic folder structure.

## Makefile

Customize your build, test, deploy, clean, ect.. 

## cmd folder

Meant to hold application entry points (main functions). The entry points are used to set up and configure each application. 

## pkg folder

Internal packages not significant enough to be standalone. 

## bin folder

Meant to hold binaries. Complied application binaries would be generated from the makefile and moved here.

## scripts folder

Deploy scripts.

## documents folder

For all documentation. Remember to use GoDoc's!

## final thoughts

Remember this is just a suggestion. Golang does not force a folder convention. 



