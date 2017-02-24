# Wot Linker

A tool that import Duniter's data in Neo4j Database.
This tool is built as a Duniter specialized node.
It can be used to perform analysis on the current and past wot.


# Neo4j Data Model

![Data Model Diagramm](https://raw.githubusercontent.com/greyzlii/wotlinker/master/docs/datamodel.jpg)


# Installation notes 

## Java 8

If using Debian, please follow instructions here :
http://tecadmin.net/install-java-8-on-debian/

## Neo4j 

Instructions here : http://debian.neo4j.org/

## Yarn 

Follow instructions here :
https://yarnpkg.com/lang/en/docs/install/#linux-tab

## Nvm

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash 
source ~/.bashrc 
nvm install 6

## WotLinker

apt-get install build-essential

git clone https://github.com/greyzlii/wotlinker.git 
cd wotlinker/
yarn
