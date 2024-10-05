# FedFT - Pre-Print

Communication efficiency is a widely recognised research problem in Federated Learning (FL), with recent work focused on developing techniques for efficient compression, distribution and aggregation of model parameters between clients and the server. Particularly within distributed systems, it is important to balance the need for computational cost and communication efficiency. However, existing methods are often constrained to specific applications and are less generalisable. In this paper, we introduce FedFT (federated frequency-space transformation), a simple yet effective methodology for communicating model parameters in a FL setting. FedFT uses Discrete Cosine Transform (DCT) to represent model parameters in frequency space, enabling efficient compression and reducing communication overhead. FedFT is compatible with various existing FL methodologies and neural architectures, and its linear property eliminates the need for multiple transformations during federated aggregation. This methodology is vital for distributed solutions, tackling essential challenges like data privacy, interoperability, and energy efficiency inherent to these environments. We demonstrate the generalisability of the FedFT methodology on four datasets using comparative studies with three state-of-the-art FL baselines (FedAvg, FedProx, FedSim). 

Our results demonstrate that using FedFT to represent the differences in model parameters between communication rounds in frequency space results in a more compact representation compared to representing the entire model in frequency space. This leads to a reduction in communication overhead, while keeping accuracy levels comparable and in some cases even improving it. Our results suggest that this reduction can range from 5% to 30% per client, depending on dataset.

Pre-print available at: [https://arxiv.org/abs/2409.05242](https://arxiv.org/abs/2409.05242)
Bibtext
```bib
@article{palihawadana2024fedft,
  title={FedFT: Improving Communication Performance for Federated Learning with Frequency Space Transformation},
  author={Palihawadana, Chamath and Wiratunga, Nirmalie and Wijekoon, Anjana and Kalutarage, Harsha},
  journal={arXiv preprint arXiv:2409.05242},
  year={2024}
}
```

### Complete code will be added after first review
