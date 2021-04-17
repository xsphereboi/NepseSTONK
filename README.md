# NepseSTONK

NepseSTONK is a Python Code for easy scraping of share prices and cache them.

## Installation

Use the git to install NepseSTONK.

```bash
git clone https://github.com/xsphereboi/NepseSTONK.git
```

## Usage For Scraping Data

```python
import nepse

Fetcher = nepse.Fetch() # Initialize
data= Fetcher.getInfo(SYMBOL) # Gets All the required information about certain company off sharesansar.com
```
## Usage For Chart

```python
import nepse

Fetcher = nepse.Graph() # Initialize
chart= Fetcher.basicGraph(SYMBOL) # Scrapes History From NepseAlpha and Plots them and save them to "{symbol}.png"
```
## TO-DO
This is just a raw code/POC , i have not got time to make it production ready . The first step i will be doing is to polish this POC for production ready. 

Will work hard on Chart.
