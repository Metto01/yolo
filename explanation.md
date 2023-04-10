* I chosee the image node:14.16.0-alpine3.13 because it is among the best images to use for java based apps.
* I used the FROM,WORKDIR,COPY,RUN,EXPOSE AND CMD Directives to run both containers.
* I was able to build two images as well one for the backend and another for the client folder.
* the ID for te two images are as follows: '3d6527f6cd9b' and '3229426b6ea6 '
* I have created a network under the name yolo 
* Inside th yolo network I managed to connect two containers 'a5fbb5667359' and '124ec99a92cd'.respectively.
* I was able to run both containers but the communication between the two containers didn't workout as expected.
* I added to the root file an ansible folder with the yml playbook file in it.
* I created a vagrant folder.
* I created a vagrantfile.
* I created a folder under the name manifest 
* In the manifest folder I created two files under the name:yolo-deployment.yaml and yolo-services.yaml



