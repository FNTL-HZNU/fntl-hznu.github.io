# Attention-based LSTM for Controller Load Prediction in Software-Defined Networks


{{< figure src="/images/att-lstm.png"  height="auto" width="500px">}}

### 引言

<p>Implementing load balancing for the control plane of SoftwareDefined Networking (SDN) can improve network reliability, scalability, and overall performance. However, existing load balancing strategies struggle to address potential future load imbalances,which can adversely affect network quality.</p>



<p>Current load balancing solutions rely on real-time data collection to determine the status of a controller. However, during the time between identifying a load imbalance and completing migration, the overloaded state of the controller can negatively impact the network. Accurate prediction of controller load and proactive switch migration can effectively reduce the duration of the controller’s load imbalance state, thereby improving load balancing efficiency. Controller load mainly comes from processing Packet_in messages, making it essential to accurately predict the transmission rate of these messages for each switch managed by the controller.</p>

  <p>Traditional time-series prediction models, such as Recurrent Neural Networks (RNN), can effectively process time-series data and exhibit memory and temporal dependency processing capabilities, achieving good prediction results. The Long Short-Term Memory (LSTM) model was used to predict controller load, demonstrating the feasibility of load prediction. However, the traditional LSTM model typically uses the final hidden state to predict, which can lead to the loss of valuable information contained in intermediate hidden states, especially when processing long sequences.  As the performance of controller load balancing is directly impacted by the accuracy of the model’s prediction, it is crucial to improve the prediction accuracy.
To improve the accuracy of the prediction model, we propose a new controller load prediction model based on the traditional LSTM model, called Attention-LSTM. We integrate attention mechanisms into LSTM, taking into account the hidden state of each LSTM time step, effectively improving the accuracy of the final prediction results. Our experiments demonstrate that our proposed model achieves higher prediction accuracy than existing models on the same dataset.</p>



​    

</p>

</p>



<span style="font-size:22px;">**链 接**</span> <span style="margin-left:20px; font-size:14px;">     https://dl.acm.org/doi/10.1145/3600061.3603124</span>

<span style="font-size:20px;">**出版物**</span> <span style="font-size:14px;">     *2023: 7th Asia-Pacific Workshop on Networking*, _**APNET**_ 2023</span>










