# BSM-LP: Bidirectional Switch Migration with Controller Load Prediction for Software-Defined Internet of Things.


{{< figure src="/images/bsm-lp.webp"  height="auto" width="500px">}}

### 摘要

<p>The Software-Defined Internet of Things (SD-IoT) utilizes the centralized control and programmability of SoftwareDefined Networking (SDN) to enhance network performance optimization and efficient resource utilization in IoT. As the network scale expands, the multiple-controller architecture becomes crucial for ensuring reliability and scalability in SD-IoT. However, the dynamic changes in traffic patterns often lead to imbalanced loads among controllers. Existing solutions primarily focus on switch migration schemes, but traditional schemes primarily rely on real-time data to assess controller loads, which fails to predict future controller loads and leads to unnecessary switch migrations. Meanwhile, existing schemes frequently encounter the challenge of overloading the target controller, leading to reduced migration efficiency. Furthermore, conventional schemes tend to overlook the issue of isolated nodes that arise from switch migrations, thereby compromising network reliability and security. To address these challenges, we propose bidirectional switch migration based on load prediction (BSM-LP), which utilizes an ATT-GRU model to accurately predict controller loads based on historical load data, thereby preventing unnecessary switch migrations. Moreover, we introduce a bidirectional switch migration algorithm that enhances migration efficiency while avoiding overloading the target controller. Additionally, we present an algorithm for identifying and integrating isolated nodes to reduce their occurrence. Finally, we validate the effectiveness of BSMLP, and the experimental results demonstrate that it reduces the load imbalance rate by an average of 22.3% and the response time by 30.5% compared to existing schemes.</p>

<p> 


​    

</p>

</p>



<span style="font-size:22px;">**链 接**</span> <span style="margin-left:20px; font-size:14px;">     https://dl.acm.org/doi/10.1145/3600061.3603124</span>

<span style="font-size:20px;">**出版物**</span> <span style="font-size:14px;">     *IEEE Internet of Things Journal*, _**IoTJ**_ 2024</span>






