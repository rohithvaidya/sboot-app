# Overview

![Build/Test](https://github.com/DevopediaOrg/sboot-app/actions/workflows/build-and-test.yml/badge.svg)

Setting Up Github Action here
1) In the workflow file, there are two jobs which run in parallel after the commit
2) There is a local env var and a global env var
3) Two different OS is used
<br></br>
4) If Sequential job execution is required, add needs: <job_name>
   <br></br>
5) Spawning 4 separate jobs given as a matrix
 <br> </br>
6) Can also add dynamic strategy where test job depends on the matrices produced by previous jobs



