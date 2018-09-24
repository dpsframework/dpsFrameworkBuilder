# _dpsFramework_ installer utility 


**_Abstract:_**  _dpsFramework_ is a very low weight _integrated development environment_ (IDE) that is executed on JADE[1] multi-agent platform _agents_. This framework is oriented to allow _Java_ Language programming in _agents_ at runtime. With _dpsFramework_ it is possible to build complex behaviors and eliminate or incorporate these behaviors from agent task scheduler, without the need to close, re-compile and re-enter the agent on JADE  platform. _dpsFramework_ improves source-code debugging capacity because, it offers the main functionalities of an _integrated development environment_ and it includes functionalities to facilitate agent-oriented programming (AOP)[2].

_dpsFramework_ also allows to run analysis processes; write _scripts_ to automate the repetition of tests; _dpsFramework_  facilitates the observation in real time of asynchronous phenomena generated by isolated behavior or, when this phenomena is generated by grouped behaviors in FIPA[3] protocols on a delayed and heterogeneous communication network. Beyond these capabilities, _dpsFramework_ is an excellent tool to teach and to study in depth the agent-oriented programming and, it has demonstrated how to distribute _rule-based expert systems_  using multi-agent technology.

## How to use the installer utility

- Download .JAR binary file from: https://github.com/dpsframework/dpsFrameworkBuilder/releases
- Open a terminal:





         $ >  export CLASSPATH=./*:lib/*:
         $ >  java -jar dspFrameworkBuilder-1.7.jar   new  apollo56
         $ >  cd apollo56
     
         ~/apollo56/ $ >  java launcher
         ~/apollo56/ $ >  java generate
         ~/apollo56/ $ >  java shell
      
         ~/apollo56/ $ >  java launcher monitor      localhost   Mont712 
         ~/apollo56/ $ >  java launcher stage-node   localhost   Jarvis CLIPS  
  
          etc.

**Fig. 1:** _Monitor-Agent GUI with selected Tab JADE-JAVA Shell console at runtime._
![](/assets/images/psMonitorAgent00.png)



# 2. References 

[1]: **JADE Platform**. <http://jade.tilab.com/>. CSELT, S. & TILab, S. (2017). Jade - java agent development framework. is a framework to develop multi-agent systems in compliance with the fipa specifications. jade 4.5.0 - revision 6825 of 23-05-2017 10:06:04. Open Source, under LGPL restrictions.

[2]: **Agent Oriented Programming**. Shoham, Y. (2005). Agent oriented programming: An overview of the framework and summary of recent research. <https://link.springer.com/chapter/10.1007/3-540-58095-6_9>

[3]:  **FIPA**. [FIPA00001] FIPA Abstract Architecture Specification. Foundation for Intelligent Physical Agents, 2002. <http://www.fipa.org/specs/fipa00001>. 

