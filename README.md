# ImmoScout24.ch Real Estate Scraper

## Project Overview

Welcome to the ImmoScout24.ch Real Estate Scraper! This project is based on the original scraper developed by [balzer82](https://github.com/balzer82/immoscraper). The scraper has been updated to handle the latest JSON/HTML structures and includes enhancements for easier debugging and additional scraping features to cover practically all available information on ImmoScout24.ch.

## Description

This project is designed to scrape detailed real estate listings from ImmoScout24.ch. By leveraging this scraper, users can gather extensive information about properties, including pricing, descriptions, locations, and other relevant details. The scraper has been enhanced to include more features and improved code structure, making it a robust tool for collecting real estate data.

## Installation

Before you start, ensure you have the following Python libraries installed. These packages are essential for running the scraper:

- `requests`: For making HTTP requests to ImmoScout24.ch.
- `beautifulsoup4`: For parsing HTML and XML documents.
- `pandas`: For data manipulation and storage.
- `json`: For handling JSON data.

Install the required packages using pip:

```bash
pip install requests beautifulsoup4 pandas
```

### Clone the repository:
```
git clone https://github.com/Fredeys/immoscout24-scraper.git
```
### Navigate to the project directory:
```
cd immoscout24-scraper
```
### Start Jupyter Notebook:
```
jupyter notebook
```
### Open the notebook:
- In the Jupyter interface that opens in your web browser, navigate to and open the immoscout24_scraper.ipynb notebook.

### Run the notebook:
- Execute the cells in the notebook sequentially to run the scraper and collect data.

## Customizing scraping parameters
You can adjust the scraping parameters specific types or regions. Modify the the parameters in the `immoscout24_scraper.ipynb` script to suit your needs.

## Debugging
Enhanced debugging features have been integrated to help you indentify and resolve issues quickly.

## Saving the data
After scraping, the data is saved into a CSV file. The filename is dynamically generated based on the type of property, transaction type, and the current date. The save_to_csv function handles the process.
```
save_to_csv(df, s, k, w)
```

## Contributing
We welcome contributions from the community! If you have ideas for improvements or new features, feel free to fork the repository and submit a pull request. Here's how you can contribute:

1. Fork the repository.
Create a new branch for your feature or bug fix:
```
git checkout -b feature-name
```
2. Make your changes and commit them:
```
git commit -m "Add some feature"
```
3. Push to the branch:
```
git push origin feature-name
```
4. Open a pull request to the main repository.

## Credits
Special thanks to balzer82 for the original scraper code. This project builds upon his work and adapts it to the current website structures.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.

