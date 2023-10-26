file:: [Electrical_Model-Free_Voltage_Calculations_Using_Neural_Networks_and_Smart_Meter_Data_1697314312902_0.pdf](../assets/Electrical_Model-Free_Voltage_Calculations_Using_Neural_Networks_and_Smart_Meter_Data_1697314312902_0.pdf)
file-path:: ../assets/Electrical_Model-Free_Voltage_Calculations_Using_Neural_Networks_and_Smart_Meter_Data_1697314312902_0.pdf

- Results considering different weeks with the same and higher PV penetrations demonstrate an average error of less than 2 Volts; showing that, in the absence of LV electrical models, the methodology could be used by distribution companies for different applications
  ls-type:: annotation
  hl-page:: 1
  hl-color:: green
  id:: 653a6c6b-f406-4d21-a5fb-f506c4e177e6
  hl-stamp:: 1698327676408
- his paper proposes a scalable electrical model-free voltage calculation methodology that uses Neural Networks to capture the underlying relationships among historical smart meter data (P, Q, and V) and the corresponding LV network.
  ls-type:: annotation
  hl-page:: 1
  hl-color:: green
  id:: 653a6c83-5a32-41e7-8ea6-6e90002cf79b
- However, the main challenge for distribution companies is that accurate voltage calculations require power ﬂow analyses that need detailed electrical models which, in the context of LV networks, are not readily available in most parts of the world. The associated data (e.g., topology, connectivity, phase grouping, impedances, etc.) is often erroneous or incomplete [5], [6] which makes the production of electrical models a very time-consuming and costly task
  ls-type:: annotation
  hl-page:: 1
  hl-color:: yellow
  id:: 653a6e37-3572-41c8-a007-b85b5b25a52f
  hl-stamp:: 1698328122210
- An alternative
  ls-type:: annotation
  hl-page:: 1
  hl-color:: yellow
  id:: 653a6f00-9e2f-473b-bb8c-6e6f3d86d89f
- The electrical model-free calculation of voltages is a topic that has only started to be explored in the last few years
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 653a6f6f-d37f-4e04-ba8b-ce9e7c17dfde
- Nonetheless, the interactions with the upstream MV network were not considered
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 653a7094-f1e3-4292-90c4-7ddf3efddb3a
- It concluded that linear regressions and neural networks achieved the most accurate voltage calculations
  ls-type:: annotation
  hl-page:: 2
  hl-color:: red
  id:: 653a70f8-af11-4b92-862d-4b86cf92d9ae
  hl-stamp:: 1698328826380
- This paper proposes a scalable methodology based on nonlinear regressions, speciﬁcally using Neural Networks (NNs), to calculate voltages without electrical models
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 653a7232-7fa7-4c86-b643-33f13a3fa5f6
  hl-stamp:: 1698329141251
- The output of a single neuron corresponds to an activation function applied over the weighted sum of its inputs shifted by a bias, as shown in 
  ls-type:: annotation
  hl-page:: 3
  hl-color:: yellow
  id:: 653a7571-101c-4748-a73e-52baefe8cf7a
- For the proposed model-free voltage calculations, the inputs for NNi are both the active and reactive power of all the customers, thus, the input layer dimension of NNi is twice the number of customers, i.e., 2|C|
  ls-type:: annotation
  hl-page:: 3
  hl-color:: yellow
  id:: 653a763d-4f94-4978-9d36-50da61a76234
- For the present study, mini batch gradient descent is considered
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 653a7aa9-3d48-468f-9bc3-01fa7c8f5261
- To handle the use of additional information, a multi-input multi-output NN, hereafter referred to as MNN
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 653a7b65-839d-4766-9b48-fbcdc4c2e099
- s its calculation is based on aggregated active and reactive power only and are used to include additional information into the formulation, i.e., relationships among P|Q∑ and V.
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 653a7da9-b110-48db-a61b-d437280184e3
- Therefore, the hyperparameters that are found to be the most suitable for a particular LV network will not work when using another LV network with different characteristics. Consequently, a scalable methodology to ﬁnd the most suitable NNs (i.e., NN∗ and MNN∗) is crucial so the same recipe can be applied by distribution companies on any type or size of LV network.
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a7e5d-4ca5-40ef-8785-63230845e21c
- inputs and outputs
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a802b-ab5d-4d4a-bf4e-836fabc32e5e
- a linear activation function
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a8055-59ad-4961-a22d-065c70b81b68
- inputs and outputs are scaled to values within the range [0, 1]
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a805e-662d-49aa-be3f-9750636baf4b
- ADAM optimize
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a8061-7f61-4c65-8f18-2ed94a229f47
- L2 regularization to prevent overﬁtting
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a806a-7f5c-4135-aefe-fb922d991cbf
- regularization factor
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a8088-719c-4953-ad2a-105108180927
- hyperparameters (i.e., number of hidden layers, number of neurons and activation function in each hidden layer, learning rate, batch size, regularization factor, and epochs)
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 653a809a-fd96-4301-b818-4a7839ad95a5