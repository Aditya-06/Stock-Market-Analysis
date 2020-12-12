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


## Dependencies:
```
selenium: 3.141.0
beautifulsoup4: 4.7.1
seaborn: 0.9.0
plotly: 4.13.0
matplotlib: 3.1.0
mplfinance: 1.14.0
lxml: 4.3.4
```

## Install Dependencies

if using the anaconda prompt
```
conda install --upgrade <pakage_name>
```

if using command line
```
pip instal <package_name>
```

## Let's take a look at the website:

![image](https://user-images.githubusercontent.com/56297484/101980674-111b7700-3c8d-11eb-9b99-484fe33feb90.png)

The highlighted table contains the data we require to conduct our analysis

## Running the code:

Once the dependencies are installed, we will start the webdriver and execute javascript.
We then print page source to confirm whether the webdriver has returned an appropriate result. It should look something like this:

![image](https://user-images.githubusercontent.com/56297484/101277796-e472e580-37dc-11eb-9791-81bcde138437.png)

We then parse the html table on the website and store the values in a pandas dataframe

![image](https://user-images.githubusercontent.com/56297484/101277831-2a2fae00-37dd-11eb-99e5-8cab54ca2a51.png)

Now that we have the required data, we can begin plotting

### Table | Open | Close

![image](https://user-images.githubusercontent.com/56297484/101277818-14ba8400-37dd-11eb-8212-0df4d4b39bfc.png)

### Candlestick plots

Using plotly
![image](https://user-images.githubusercontent.com/56297484/101277838-40d60500-37dd-11eb-9edb-e0ca7b5dcb2d.png)

Using matplotlib and mpf
![image](https://user-images.githubusercontent.com/56297484/101277862-6531e180-37dd-11eb-96e6-755507890f3a.png)

### Returns:

Plotting yearly retunrs on the stock
![image](https://user-images.githubusercontent.com/56297484/101277880-8561a080-37dd-11eb-9bec-b10faa8bfc53.png)

Plotting cumulative returns over 5 years
![image](https://user-images.githubusercontent.com/56297484/101277919-c954a580-37dd-11eb-8a69-436ffffb69e2.png)

Plotting a shared axis plot using seaborn
![image](https://user-images.githubusercontent.com/56297484/101277940-df626600-37dd-11eb-9435-601ada5bfa7d.png)

