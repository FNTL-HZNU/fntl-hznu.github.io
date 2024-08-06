# RSLB: Robust and Scalable Load Balancing in Software-Defined Data Center Networks


{{< figure src="/images/RSLB.png"  height="auto" width="450px">}}



###  摘要

<p>Data center networks demand high-performance, robust, and scalable load balancing protocols. Despite progress, existing work still cannot meet these requirements well. Software defined networking (SDN) can bring considerable flexibility to the management of data center networks. In the software-defined data center network, we design, analyze, and evaluate RSLB, a robust and scalable load balancing protocol that overcomes these challenges. RSLB uses fine-grained flowcell as the transmission unit, and uses link delay as the congestion metric. It uses a threestep routing strategy to route flowcells to the path with the least congestion. Through global congestion awareness, RSLB reduces flow completion time (FCT), and is more robust to topological asymmetries compared to existing congestion-agnostic schemes. To collect and store congestion information, RSLB adopts a distributed control structure that monitors the congestion of the entire network through multiple controllers, which makes it much more scalable for implementation in large-scale networks compare to existing congestion-aware schemes. The simulation results show that RSLB can achieve lower FCT for mice flows and higher throughput for elephant flows than existing schemes, no matter in failure-free topology or asymmetric topology.</p>

​      



</p>

</p>



<span style="font-size:22px;">**链 接**</span> <span style="margin-left:20px; font-size:14px;">https://ieeexplore.ieee.org/abstract/document/9832649</span>

<span style="font-size:20px;">**出版物**</span> <span style="font-size:14px;">     *IEEE Transactions on Network and Service Management*, _**TNSM**_ 2021</span>




