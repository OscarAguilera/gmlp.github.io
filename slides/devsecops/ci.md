<p class="fragment highlight-current-blue">CONTINUOUS INTEGRATION</p>

<p class="fragment fade-in-then-semi-out">![contuousi](./img/CiC.png?raw=true)<!-- .element height="55%" width="55%" --></p>


# CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Continuous integration (CI) is the practice of merging all developer working copies to a shared mainline several times a day.</p>


<p class="fragment highlight-current-blue">CONTINUOUS INTEGRATION</p>

<p class="fragment fade-in-then-semi-out">Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.</p>
 <p class="fragment fade-in-then-semi-out">![git](https://blog.cpanel.com/wp-content/uploads/2018/05/image2018-2-8_17-46-1.png?raw=true)</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Then... we have code and branches, now what?</p>
<p class="fragment fade-in-then-semi-out">![jackie](./img/Jackie-chan-confused.png?raw=true)</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Let's build, but... what it's a build?</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">In the field of software development, the term build is similar to that of any other field.That is, the construction of something that has an observable and tangible result.</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Build automation is the process of automating the creation of a software build and the associated processes including: compiling computer source code into binary code, packaging binary code, and running automated tests.</p>


##  CONTINUOUS INTEGRATION

 <p class="fragment fade-in-then-semi-out">![maven](./img/maven-logo.png?raw=true) <!-- .element height="40%" width="40%" --></p>
 <p class="fragment fade-in-then-semi-out">![gradle](./img/gradle.png?raw=true) <!-- .element height="20%" width="20%" --></p>
 <p class="fragment fade-in-then-semi-out">![ant](./img/ant.png?raw=true)</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Ok, we did a Build and now what????</p>
<p class="fragment fade-in-then-semi-out">![what](./img/NowWhat.gif?raw=true)</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Now we have an Artifact!!!... But WTH!? is an artifact?</p>
<p class="fragment fade-in-then-semi-out">An artifact is one of many kinds of tangible by-products produced during the development of software. Some artifacts (e.g., use cases, class diagrams, and other Unified Modeling Language (UML) models, requirements and design documents) help describe the function, architecture, and design of software. Other artifacts are concerned with the process of development itself such as project plans, business cases, and risk assessments.</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Artifacts can be used to represent data created as a side-effect of running a build. Artifacts are files which are associated with a single build.A build can have any number of artifacts associated with it.</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">![nexus](./img/nexus.png?raw=true)</p>
<p class="fragment fade-in-then-semi-out">![nexus](./img/artifactory.png?raw=true)</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">But who controls and manage all of this stuff? it's magic? DevOps people are wizards?</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Here is were we use a continuous integration software that supports our continuous integration process, in which developer's changes are immediately tested and reported when they are added to the mainline code base.</p>


<p class="fragment fade-in-then-semi-out">![ci](./img/cicd.png?raw=true) <!-- .element height="50%" width="50%" --></p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Our orchestrator did the build and deploy the artifact, now what?</p>
<p class="fragment fade-in-then-semi-out">![next](https://media.giphy.com/media/4bWWKmUnn5E4/giphy.gif)</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">We can't have CI without automated testing.</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">But where is all this automated testing executed?</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">![junit](./img/JUnit_logo.png?raw=true)<!-- .element height="10%" width="10%" --></p>
<p class="fragment fade-in-then-semi-out">![selenium](./img/selenium.png?raw=true)<!-- .element height="10%" width="10%" --></p>
<p class="fragment fade-in-then-semi-out">![Robot](./img/robot.png?raw=true)<!-- .element height="10%" width="10%" --></p>
<p class="fragment fade-in-then-semi-out">![bash](./img/bash.png?raw=true)<!-- .element height="10%" width="10%" --></p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">Another part of CI/CD and DevOps is "Infrastructure as code", the capability of create and destroy servers under demand for specific needs or testing, with the fiability everytime will we have the same config.</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">For local environments:</p>

<p class="fragment fade-in-then-semi-out">![vagrant](./img/vagrant.png?raw=true)</p>

<p class="fragment fade-in-then-semi-out">![compose](./img/compose.png?raw=true)</p>


#  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">For Public/private/Hybrid clouds:</p>

<p class="fragment fade-in-then-semi-out">![terraform](./img/terraform.png?raw=true)</p>
<p class="fragment fade-in-then-semi-out">![cloudformation](./img/cloudformation-logo.png?raw=true)</p>


#  CONTINUOUS INTEGRATION

 <p class="fragment fade-in-then-semi-out">How can I manage the configuration to be the same always and across all my environments?</p>
 <p class="fragment fade-in-then-semi-out">Source Control Tools</p>  
  
<p class="fragment fade-in-then-semi-out">![gitmerge](./img/gitmerge.gif)</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">![cm-tools](./img/cm-tools.png?raw=true)</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">How can we know the health of my environments and get alerts in time?</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">![zabbix](./img/zabbix.png?raw=true) <!-- .element height="30%" width="30%" --></p>
<p class="fragment fade-in-then-semi-out">![graphite](./img/graphite.png?raw=true) <!-- .element height="30%" width="30%" --></p>
<p class="fragment fade-in-then-semi-out">![prometheus_logo](./img/prometheus_logo.png?raw=true)<!-- .element height="20%" width="20%" --></p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">And log management?</p>


##  CONTINUOUS INTEGRATION

<p class="fragment fade-in-then-semi-out">![splunk](./img/splunk.png?raw=true) <!-- .element height="70%" width="70%" --></p>
<p class="fragment fade-in-then-semi-out">![elastic](./img/elastic.png?raw=true) <!-- .element height="50%" width="50%" --></p>
<p class="fragment fade-in-then-semi-out">![stackdriver](./img/stackdriver.png?raw=true)<!-- .element height="50%" width="50%" --></p>


# CONTINUOUS INTEGRATION BEST PRACTICES

<p class="fragment fade-in-then-semi-out">Maintain a Single Source Repository</p>
<p class="fragment fade-in-then-semi-out">Automate the build</p>
<p class="fragment fade-in-then-semi-out">Make your build Self-Testing</p>
<p class="fragment fade-in-then-semi-out">Everyone Commits to The Mainline Every Day</p>
<p class="fragment fade-in-then-semi-out">Every Commit should build the mainline on an Integration machine</p>
<p class="fragment fade-in-then-semi-out">Fix Broken Build Immediately</p>
<p class="fragment fade-in-then-semi-out">Keep the Build fast</p>
<p class="fragment fade-in-then-semi-out">Test in a clone of production Environment</p>
<p class="fragment fade-in-then-semi-out">Make it easy to get the latest executable</p>
<p class="fragment fade-in-then-semi-out">Everyone can see what’s happening</p>
<p class="fragment fade-in-then-semi-out">Automate Deployment</p>


