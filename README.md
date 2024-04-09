docker container vs github runner machine

using containers can create a predefined environment
you could reuse the container in different workflows whenever you need that environment

run docker containers on top of runner machines provided by github

steps of the job are executed inside the container

TODO:
service containers?
extra services run which can run side by side along with your jobs or steps
