
# Mekong Salinity Research (MKS Research)

MKS Research was developed during my time as an undergraduate student at Ho Chi Minh City University of Technology (HCMUT), under the close supervision of [`Dr. Nguyen An Khuong`](https://orcid.org/0000-0002-9910-6387) and  [`PhD Candidate Ngo Luong Thanh Tra`](https://greenwich.edu.vn/personnel/ths-ngo-luong-thanh-tra/). It has been a great honor to have them as my co-advisors throughout this project.

This project marks the beginning of my research journey in **time-series data analysis**, **long- and short-term forecasting** and **related problems**. The datasets used in this project were generously provided by the Technical Department of [`Tien Giang Irrigation Works Operating Company`](http://thuyloitiengiang.vn/) and the [`Southern Institute of Water Resources Research (SIWRR)`](https://www.siwrr.org.vn/). Many thanks to both organizations for providing these valuable datasets that made this research possible.


## State-of-the-art (SOTA) in this area
If you are interested in salinity forecasting, as I am, here are some papers on the topic that have been published up to October 2026:
| Published | Paper | Paper Type | SCImago Ranking |
|---|---|---|---|
| May 2026 | *Deep Learning-Based Salinity Forecasting in the Vietnamese Mekong Delta: A Cung Hau Estuary Case Study* [`[Water]`](https://doi.org/10.3390/w18101240) |  | 🥇 Q1 |
| Dec 2025 | *Salinity forecasting in the Vietnamese Mekong Delta: Evaluating the predictive power of machine learning approaches  using multitemporal lag features* [`[Hue University Journal of Science: Natural Science]`](https://jos.hueuni.edu.vn/index.php/hujos-ns/article/view/7876) |  | ⚠️ None |
| Sep 2025 | *Salinity Intrusion Prediction in the Estuary Using Machine Learning: Vietnam’s Mekong Delta Tested for Global Study* [`[Iranian Journal of Science and Technology, Transactions of Civil Engineering]`](https://doi.org/10.1007/s40996-025-02034-7) |  | 🥈 Q2 |
| May 2025 | *Predicting salinity levels in the Mekong delta (Viet Nam): analysis of machine learning and deep learning models* [`[Discover Artificial Intelligence]`](https://doi.org/10.1007/s44163-025-00336-3) |  | 🥇 Q1 |
| Mar 2025 | *Short‐term salinity prediction for coastal areas of the Vietnamese Mekong Delta using various machine learning algorithms: a case study in Soc Trang Province* [`[Applied Water Science]`](https://doi.org/10.1007/s13201-025-02419-z) |  | 🥇 Q1 |
| Feb 2025 | *Estuary salinity prediction using machine learning: case study in the Hau estuary in Mekong River, Vietnam* [`[Water Supply]`](https://doi.org/10.2166/ws.2025.007)|  | 🥈 Q2 |
| Sep 2022 | *Apply Machine Learning to Predict Saltwater Intrusion  in the Ham Luong River, Ben Tre Province* [`[VNU Journal of Science: Earth and Environmental Sciences]`](https://doi.org/10.25073/2588-1094/vnuees.4852)|  | ⚠️ None |
| May 2022 | *Performances of Different Machine Learning Algorithms for Predicting Saltwater Intrusion in the Vietnamese Mekong Delta  Using Limited Input Data: A Study from Ham Luong River* [`[Water Resources]`](https://doi.org/10.1134/S0097807822030198)|  | 🥉 Q3 |
| Aug 2021 | *Performance evaluation of Auto-Regressive Integrated Moving Average models for forecasting saltwater intrusion into Mekong river estuaries of Vietnam* [`[Vietnam Journal of Earth Sciences]`](https://doi.org/10.15625/2615-9783/16440)|  | 🥈 Q2 |

**Note: I will keep updating this list.** If you have published any related papers in this field, please let me know, and I will add them as soon as possible.

### Inspect the project structure:

```
Mekong-Salinity-Research/
├── README.md                     # Overview of the research repository
├── requirements.txt              # pip dependency list for quick environment setup
├── LICENSE / CONTRIBUTING.md     # Upstream license and contribution guide
├── data/                         # Centralized research datasets
│   ├── salinity-and-water-level/ # Downstream salinity and water-level observations
│   ├── river-discharge/          # Upstream river discharge datasets
│   └── metadata/                 # Metadata describing datasets and their sources
├── papers/                       # Research projects and associated papers
└── run.py                        
```

## Contact
If you have any questions or suggestions, feel free to contact me:
```
Nguyen Duy Khang
Bachelor Student - School of Industrial Management
Ho Chi Minh City University of Technology (HCMUT) - VNU-HCM
Mobile: (+84) 393 421 279
Email: khang.nguyen4growth@hcmut.edu.vn
```
Or describe it in Issues.

## Acknowledgments

This research is constructed based on the following repos and data sources:

- **Benchmarking methodology:** [Time Series Library (TSLib)](https://github.com/thuml/Time-Series-Library)
- **Salinity and water-level datasets:** [Tien Giang Irrigation Works](http://thuyloitiengiang.vn/)
- **River discharge datasets:** [Southern Institute of Water Resources Research (SIWRR)](https://www.siwrr.org.vn/)

