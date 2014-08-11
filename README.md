open-vmf
========

Open Virtual Machine Formart by B8G Datentechnik &amp; Direkt SPEED VAGRANT, DOCKER, BAREMETAL, EC2


Spezification:
Takes any Source: Vagrant, docker, shell script ..

Makes out of it

name.ovmf

FROM type SOURCE
MODIFY type TARGET 
DO type cmd
DO type cmd
SAVE ovmf



ovmf contains all instructions needed and all data

example convert of a Docker-Container github repo
-> Take Repo
-> Write all files into a array
-> Transform ADD Statments in dockerfile with the array data as cat here document
->
