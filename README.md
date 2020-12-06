# Stock-Market-Analysis

### Web scrape yahoo finance to obtain stock data and calculate returns over the last 5 years

Using several python packages like selenium and bs4, we will scrape the yahoo finnace website and obtain the historical stock prices of a particular company

## Tech Stack:
```
python: 3.6.8
jupyter notebook: 6.0.3
```
### Note (For chrome users): For selenium to access the browser, it would require the chrome webdriver installed- 
_Download and install Chrome Browser from_ https://www.google.com/chrome/.

_ChromeDriver executable file is available at_ https://sites.google.com/a/chromium.org/chromedriver/downloads.


## Dependancies:
```
selenium: 3.141.0
beautifulsoup4: 4.7.1
seaborn: 0.9.0
plotly: 4.13.0
matplotlib: 3.1.0
mplfinance: 1.14.0
lxml: 4.3.4
```

## Install Dependancies

if using the anaconda prompt
```
conda install --upgrade <pakage_name>
```

if using command line
```
pip instal <package_name>
```

## Running the code:

Once the dependencies are installed, we will start he webdriver and execute javascript.
We then print page source to confirm whether the webdriver has returned an appropriate result. It should look something like this:


