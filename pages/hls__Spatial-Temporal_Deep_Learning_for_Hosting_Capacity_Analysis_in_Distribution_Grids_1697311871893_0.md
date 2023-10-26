file:: [Spatial-Temporal_Deep_Learning_for_Hosting_Capacity_Analysis_in_Distribution_Grids_1697311871893_0.pdf](../assets/Spatial-Temporal_Deep_Learning_for_Hosting_Capacity_Analysis_in_Distribution_Grids_1697311871893_0.pdf)
file-path:: ../assets/Spatial-Temporal_Deep_Learning_for_Hosting_Capacity_Analysis_in_Distribution_Grids_1697311871893_0.pdf

- long short-term memory (LSTM)
  ls-type:: annotation
  hl-page:: 1
  hl-color:: green
  id:: 652aecbf-6ede-4658-af6d-0ff2a7ad49de
- HC is denoted as the maximum active power that can be injected by DERs at a bus in an existing distribution grid without causing technical problems or requiring changes to power system facilities.
  ls-type:: annotation
  hl-page:: 1
  hl-color:: red
  id:: 652aed3d-d633-43d4-aefa-9a75f7927c9d
- the deterministic (worst-case), stochastic, streamlined, and iterative Integration Capacity Analysis (ICA) methods
  ls-type:: annotation
  hl-page:: 1
  hl-color:: green
  id:: 652aed92-4f05-4784-9497-442c8199d9d1
  hl-stamp:: 1697312152723
- Differently, using historical time-series data, the streamlined method [22] and the iterative ICA [23], [24] method provide insight into how hosting capacity changes over time and the ability to derive a corresponding hosting capacity pattern subjected to time
  ls-type:: annotation
  hl-page:: 1
  hl-color:: green
  id:: 652aedef-c0bd-4977-80ec-08e476f7bf29
- calculation burden is still the limit of traditional HCA for real-time tasks
  ls-type:: annotation
  hl-page:: 2
  hl-color:: green
  id:: 652aee7e-79a8-4337-91ef-f36b53a0d7ce
- machine learning-based problem formulation
  ls-type:: annotation
  hl-page:: 2
  hl-color:: green
  id:: 652aeed4-0059-4f59-bba9-dea3423bed82
- Though the basic LSTM framework can capture the timevarying impacts in HCA, the impact of spatial information cannot be embedded directly
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 652aef42-8f5a-4b04-b51a-e790cb1fe2df
  hl-stamp:: 1697312580062
- Therefore, we modiﬁed the forget gate to dual forget gates, which allows the model to transfer temporal and spatial memory in parallel
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 652aefa7-fc38-4d80-914c-07d326209ddb
- This can be achieved by a cloud-based platform called end-to-end solar energy optimization platform (e-SEOP
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 652af0d8-81c8-4551-ba6c-918874fe4b02
- (p1, p2) = (0, 2)
  ls-type:: annotation
  hl-page:: 2
  hl-color:: purple
  id:: 652af155-5521-405f-858f-187625787b79
  hl-stamp:: 1697313112273
- our learning-based HCA is to ﬁnd a mapping rule between the power ﬂow data and the hosting capacity data.
  ls-type:: annotation
  hl-page:: 2
  hl-color:: yellow
  id:: 652af1d0-f03e-41d9-9d51-6149734905ac
  hl-stamp:: 1697313234043
- Speciﬁcally, the power ﬂow data from power ﬂow analysis is the training input, including the voltage magnitude, voltage angle, load proﬁles, and PV proﬁles, etc. Moreover, the per-bus HC data is the desired output, which is also generated from simulation.
  ls-type:: annotation
  hl-page:: 3
  hl-color:: yellow
  id:: 652af233-0d4e-4914-a99d-57723b90f93f
- temporal sequenc
  ls-type:: annotation
  hl-page:: 3
  hl-color:: yellow
  id:: 652af2be-e66e-45ec-9cea-e4626f308103
- The spatial sequences
  ls-type:: annotation
  hl-page:: 3
  hl-color:: yellow
  id:: 652af2c4-7251-4309-b9f2-6e3f3cfc84ec
- A random traversal in the network will result in wrong spatial correlation. Thus, to convert the network into a spatial sequence, we propose traversing the network with paths. This method divides the distribution grid into different paths, from the slack bus or three-phase main trunk to each lateral end.
  ls-type:: annotation
  hl-page:: 3
  hl-color:: yellow
  id:: 652af359-b7a0-4e6a-abc0-9d8269576072
- longest paths method
  ls-type:: annotation
  hl-page:: 3
  hl-color:: red
  id:: 652af369-9b4d-4816-9bdb-17551c159ec8
  hl-stamp:: 1697313643068
- An RNN is a series of identical feedforward neural networks, one unit for each time or step, which are known as ‘RNN cells’ [43], [44]
  ls-type:: annotation
  hl-page:: 3
  hl-color:: red
  id:: 652c3e7d-5187-4a56-9bb1-b1d668145f42
- RNNs cannot transfer information correctly between two cells with relatively long distances
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c3f9e-7710-4fd3-a141-40cb3a85899e
  hl-stamp:: 1697398688543
- To solve this problem, LSTMs improve basic RNNs via gate functions, which are capable of learning short-term and long-term dependencies [45]
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c3fec-bc41-4cbd-a4e5-47f083027b88
- sigmoid function
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c40a8-d1e2-4067-82b4-9805e1deae7b
- weight matrices
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c40ba-b818-4b7c-8022-c73023afd261
- biases
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c40d1-a825-466f-911f-f613166e196e
- element-wise (Hadamard) product
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c4139-7295-4b04-a0bc-de58aedff387
- Therefore, the connectivity relationship is crucial in HCA, and ignoring the spatial correlation will cause low accuracy.
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c419b-892e-4069-9a70-b56862519e41
- In order to consider both temporal and spatial
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 652c41e1-df06-428a-a1be-89af2ae2b5c2
- correlation for HC, we embed the topology information of the power system by modifying the LSTM to the Spatial-Temporal LSTM. The spatial sequences we used are the paths in the network, and each of the paths is from the feeder head to the lateral end
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 652c41f7-a0f5-46ca-b02f-146c1f00cc0d
- Therefore, we modiﬁed this gate to dual forget gates. The dual forget gates are designed to decide what information the cell should memorize from these two dimensions. Consequently, one new cell can receive the cell states and hidden states from the last temporal cell and the last spatial cell separately.
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 652c4250-d111-4026-8bff-8890ae2a6cdc
- sensitivity gate
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 652c42fb-b3c0-4edc-b440-6c3a8a7d6c3d
- vector of voltage sensitivity data
  ls-type:: annotation
  hl-page:: 6
  hl-color:: yellow
  id:: 652c43e3-4f5e-4341-8337-5511393e7445
- We will validate the performance of the designed dual forget gates and the sensitivity gates via the comparison with baseline models, which are the temporal sequence LSTM and the spatial sequence LSTM. These comparison results will support our design
  ls-type:: annotation
  hl-page:: 7
  hl-color:: yellow
  id:: 652c446c-a47e-4cda-8855-a44e6f0d7eb0
- which also reinforces the superiority of our new designs
  ls-type:: annotation
  hl-page:: 10
  hl-color:: yellow
  id:: 652c46be-274e-44e6-bb89-125e71a5f31e
- for example, a treestructured LSTM network or a combination of the GNN and LSTM network may be feasible research directions to extend the ST-LSTM design.
  ls-type:: annotation
  hl-page:: 10
  hl-color:: yellow
  id:: 652c46db-3a66-4981-95c2-e583f05c9871
- CYME 
  ls-type:: annotation
  hl-page:: 7
  hl-color:: yellow
  id:: 653a5ea6-a19d-4c9a-83eb-b707d4637488