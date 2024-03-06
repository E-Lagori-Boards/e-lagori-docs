Do you have new amazing product in mind that could solve a problem that you and the world has been facing but dont have suffecient knowledge of electronics to make it happen?
Do you have project that is so large that you are stuck up with a bundle of criscrossing wires which may fall apart any time?
or Do you want save time and money spent making custom boards which is long lead time process and involves multiple iterations?

Typically these are the questions faced by every developer and project mangement team irrespective of whether it is a small hobby project  or large team accomplisihing complex design. Typical process of developing product follows below cycle and time line

Concept Block diagram development - 1 week
Circuit development - 8.6 weeks
Schematic development - 1 weeks
Layout development - 4.3 weeks
Procurement and Fabrication - 13 weeks
Board bring up - 4.3 weeks
Software  interface and testing - 21 weeks
Total - 53 weeks

We may bo back to previous steps at any point and repeat the process. 

Typical way yo reduce the risk of failure is to use the Evaluation boards and DIY boards which at present are not compatiable with each other and hence leads to large volume of wires for interconnectivity. 

Following problems are typically faced when designing a new prototype

1. Systems cannot be built with Eval boards, which forces Custom design too early in the design cycle even before Proof of concept is demonstrated.
2. Co-design from multiple streams like mechanical eng etc required too early in the design leading to multiple iterations.
3. High prototype production cost.
4. Modifications due to change in specifications results in redesign.
5. Time taken for small batch production is significantly high and most EMS manufacturers are not interested.
6. Significant wastage of components and resources when iterations are required.
7. Errors require remaking the complete PCB and Long time lost in iterations.

The primary Question which triggered development of E-LAGORi is "Can we develop an ecosystem where all the above issues are solved and Evaluation boards of multiple companies can be made intecompatible?"

Lets take a step back

At present all systems are composed of Analog section, Digital section and power section.
Analog section typically has cascade structure. 
Digital and power sections has bus structure. 

E-Lagori incorporates these basic structures to create a comprahensive stackable architecture where you can select the route of signal path across the modules using a conductive ink. This architecture allows you to decide which signals can enter and exit the module and continue propagation along the system. More about the architecture in the "Architecture of E-LAGORi module" section
