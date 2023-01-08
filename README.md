# Docker
<h3> Concept:</h3>
<ul>
<li>Docker is an open-source application container engine. 
<li>It came in 2013 and was realized based on go. 
<li>Docker can help developers package applications and dependencies to a light weight and portable container and publish on any Linux environment. 
<li>Docker used sandbox mechanism and each container is isolated with others;
</ul>
<h3> Structure </h3>
<img src="https://docs.docker.com/engine/images/architecture.svg" width="600px" height="400px"></img>
The relationship between image and container is similar to the relation between instaintiable class and object.
<h3> Commands:</h3>
<table>
  <tr>
    <th></th>
    <th>command</th>
    <th>explanation</th>
  </tr>
  <tr>
    <td>service related command</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>image related command</td>
    <td>docker images;<br>
      docker search redis;<br>
      docker pull redis;(download redis)<br>
      docker rmi ...
    </td>
    <td>the second one is to download redis;<br>
      the third one is to remove redis;
    </td>
  </tr>
  <tr>
    <td>container related command</td>
    <td>docker run -it --name=c1 centos:latest /bin/bash<br>
    docker ps -a<br>
    docker run -id --name=c2 centos:7<br>
    </td>
    <td>1.create and run the container directly<br>
      2.show all container<br>
      3.create and use the command to run the container
    </td>
  </tr>
