# Web Crawler

This web crawler searches a designated website for intended results and pulls them into the program.

## Features

- **Website Crawling**: Fetch content from designated URLs.
- **Custom Search**: Extract specific results based on the user-defined criteria.
- **Scalable**: Designed to handle small to medium-scale web crawling tasks.

## Technologies Used

- **Java**: Core programming language used for building the application.
- **Libraries**:
  - **JSoup**: For parsing and extracting data from HTML documents.
  - **Apache HttpClient**: For making HTTP requests to fetch web content.

## Installation

To use the Web Crawler, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/GauthamSathishD/Web-Crawler.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Web-Crawler
   ```
3. Compile the program:
   ```bash
   javac -cp jsoup.jar:apache-httpclient.jar:. Crawler.java
   ```
4. Run the program:
   ```bash
   java -cp jsoup.jar:apache-httpclient.jar:. Crawler
   ```

## Usage

1. Specify the target URL(s) within the program.
2. Define the search criteria for the content you want to extract.
3. Run the program to crawl the specified websites and view the results.
