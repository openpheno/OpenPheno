# OpenPheno: Open-Access, User-Friendly, Smartphone-Based Plant Phenotyping Platform

[![GitHub License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/OpenPheno/OpenPheno/blob/main/LICENSE)  
[![Open Source](https://img.shields.io/badge/Open_Source-Friendly-brightgreen.svg)](https://opensource.org/licenses/MIT)

## About OpenPheno

OpenPheno is an open-access, user-friendly, and smartphone-based software platform designed for instant plant phenotyping. It is encapsulated within a WeChat Mini-Program, leveraging cloud computing to provide a portable, intuitive, and cost-free solution for plant scientists, breeders, and enthusiasts. OpenPheno aims to democratize plant phenotyping by making advanced tools accessible to a broader audience, including those without specialized hardware or coding skills.

## Key Features

- **Zero-Cost and Portable**: No specialized hardware required. Accessible via smartphone through the WeChat Mini-Program.
- **Diverse and Open**: Supports phenotyping of various plant species. Developers can contribute new algorithms to expand the platform's capabilities.
- **Real-Time Analysis**: Capture plant images with your smartphone and get phenotyping results instantly.
- **User-Friendly Interface**: Designed for users with different backgrounds, from researchers to field technicians.

## Applications

OpenPheno currently supports the following phenotyping tools:

1. **SeedPheno**: Automated seed size and count analysis.
2. **WheatHeadPheno**: Wheat head detection and morphological analysis.
3. **LeafAnglePheno**: Measurement of flag leaf angle in wheat.
4. **SpikeletPheno**: Spikelet counting and morphological analysis in wheat.
5. **CanopyPheno**: Analysis of plant canopy structure.
6. **TomatoPheno**: Measurement of tomato fruit size and count.
7. **CornPheno**: Corn kernel counting and row feature extraction.

## Getting Started

### Prerequisites

- **Smartphone**: iOS or Android device with WeChat installed.
- **Python 3.6 or higher**: Required for backend and algorithm development.
- **Internet Connection**: Required for data transmission and cloud processing.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/OpenPheno/OpenPheno.git
   cd OpenPheno
   
2. 

### Usage
1. Open the OpenPheno WeChat Mini-Program on your smartphone.
2. Select a phenotyping tool (e.g., SeedPheno, WheatHeadPheno).
3. Capture an image of the plant specimen.
4. Tap "Analyze" to process the image and view the results.

## Contributing
We welcome contributions from the community to enhance OpenPheno's capabilities. To contribute a new algorithm or tool:
- **Fork the Repository**:
Fork this repository to your GitHub account.
- **Develop Your Tool**:
Implement your algorithm in Python.
Ensure it follows the OpenPheno API format.
- **Submit Your Contribution**:
Create a pull request with your executable files, model weights, and documentation.
Our team will review and integrate your contribution.


## Contact
For any questions or support, please contact the OpenPheno team at openpheno@phenotrait.com.
