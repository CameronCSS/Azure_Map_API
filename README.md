<a name="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="https://github.com/user-attachments/assets/40d681d5-5b1f-4c93-bddc-83bc07cd5a5e" alt="AzureMapApiLogo" height="150">
  </a>

  <h3 align="center">Data Extraction using Azure Map API</h3>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

A client needed School information in a particular area. 
<br>
Using the Azure Map API we can quickly gather all that information and give them a clean file with the data they need.

What you need:
* Azure API key
* Python coding knowledge
* Know how to use jupyter notebooks 
<sup>(Its much easier to test and decipher JSON in a notebook than a straight .py file)</sup>



<p align="right">(<a href="#readme-top">back to top</a>)</p>



### *Final Output Data*
 <img src="https://github.com/user-attachments/assets/da17c99d-ea7d-45ac-9d04-1b378df240d4" alt="AzureMapApiLogo" height="500">



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

If you want to try this project yourself you first need to get an Azure API key [HERE](https://azure.microsoft.com/en-us/products/azure-maps)

### Installation

1. You will need these packages
* pandas
  ```sh
  pip install pandas
  ```
* numpy
  ```sh
  pip install numpy
  ```
* matplotlib (Optional)
  ```sh
  pip install matplotlib
  ```


2. Clone the repo
   ```sh
   git clone https://github.com/CameronCSS/Azure_Map_API.git
   ```
3. Enter your API in `secret.py`
   ```py
   AZURE_MAP_KEY = 'your_api_key'
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

We will be using a GET HTTP method to get our data. We can use python to easily manipulate the URL and get the desired data
```python
# Sample GET HTTP request
https://atlas.microsoft.com/search/address/json?&subscription-key={YOUR-AZURE_MAP_KEY}&api-version=1.0&language=en-US&query=400 Broad St, Seattle, WA 98109

"This will return results for the exact address '400 Broad St, Seattle, WA 98109'"
```

You can learn more about the Azure API usage [HERE](https://learn.microsoft.com/en-us/azure/azure-maps/how-to-search-for-address)



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.



----

<a name="Contact"></a> 
## <a href="https://camdoesdata.com/#contact">Contact Me</a>

  </table>
  <p style="margin-left: auto;">
    <a href="https://drive.google.com/file/d/1YaM4hDtt2-79ShBVTN06Y3BU79LvFw6J/view?usp=sharing" target="_blank" rel="noopener noreferrer">
      <img src="https://user-images.githubusercontent.com/121735588/215364205-abdfc0ac-53db-4733-8d43-b57c1bafb802.png" alt="Resume button">
    </a>
  </p>
</div>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

