# GPUs-Price-Tracking-using-BS4

**Project Overview: Web Scraping E-Commerce Data**

1. **Objective**: The project aims to extract product information from an e-commerce website, specifically focusing on graphics cards.

2. **Technologies Used**: Python is the primary programming language used for web scraping and data manipulation. The Beautiful Soup library is used for parsing HTML content, and the requests library is used to make HTTP requests to the website.

3. **Process**:
   - The project starts by sending an HTTP request to the target e-commerce website and obtaining the HTML content of the product category page for graphics cards.
   - Beautiful Soup is employed to parse the HTML content and extract relevant data such as product names, prices, and links.
   - Iterating through the extracted data, the program creates a dictionary that stores the product names, formatted prices, and corresponding links.
   - The extracted data is then sorted based on the formatted prices, using the `sorted()` function with a custom sorting key.
   - Finally, the program displays the sorted product names along with their formatted prices in a visually appealing format, using ANSI escape codes for text formatting.

4. **Output**: The output of the project is a list of sorted graphics card products, each displayed with its name and formatted prices, providing users with an organized overview of the available products.

5. **Challenges**: Challenges may include handling dynamic web pages, dealing with inconsistent HTML structure, and adhering to website terms of use while scraping data.

6. **Future Enhancements**: To extend the project, I could implement more advanced features, such as collecting additional product details, integrating with a database to store the extracted data, or even building a user interface for better interaction.

