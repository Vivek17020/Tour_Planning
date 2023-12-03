
<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [License](#license)



<!-- ABOUT THE PROJECT -->
## About The Project
This is a simple streamlit app to demonstrate HERE Tour Planning. With the Tour Planning, you can dynamically optimize routes for multiple vehicles of Tourists visiting a set of locations given real-life constraints such as limited capacity in a vehicle or delivery time windows.

![Product Name Screen Shot](here_tpa_demo.gif)

Upload a pre-formatted tpa_request excel file with the details of transport orders and fleet of vehicles. Configure costs to optimize the tour plans for, and send it over to HERE Tour Planning. The API will solve the multi-vehicle routing problem and provide the optimal sequence of locations according to the costs.


### Built With
[Streamlit](https://streamlit.io/)

<!-- GETTING STARTED -->

### Prerequisites
Python3

### Installation
1. Get a API Key at [HERE Developer Portal](https://developer.here.com) and send us a request for evaluation access with short description of your company and use-case

2. Install dependencies
```sh
pip install -r requirements.txt
```
3. Run
```sh
streamlit run tpa_demo.py
```

<!-- USAGE EXAMPLES -->
## Usage
Demonstrate HERE Tour Planning with simple multi-vehcile routing problems

<!-- ROADMAP -->
## Roadmap
- Routing with HERE Routing v8
- Support for Bus profile




<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE` for more information.




<!-- MARKDOWN LINKS & IMAGES -->
[product-screenshot]: streamlit-fundamentals_app-2021-05-11-10-05-53.gif
