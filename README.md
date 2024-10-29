# Udemy Course Price Tracker with Automated Sale Alerts

## Project Background
Udemy offers a wide range of courses for learning new skills, with standard prices typically between $100-$250. However, Udemy frequently runs flash sales, offering discounts from 50% to 80%, which can significantly reduce course costs. The challenge is that Udemy does not notify users about these sales through promotional emails, making it easy to miss these savings opportunities. 

This project addresses the gap by creating a price tracker that monitors the price of specified Udemy courses and sends email notifications when a course is on sale, ensuring users can purchase courses at the best price.

The Python Jupyter notebook for this project can be found [HERE](https://github.com/Lekan-E/Udemy-Course-Price-Tracker/blob/2c9bf5adef376cbbba7ac0164805b1beea7ac86e/Udemy%20Price%20Tracker.ipynb)


![ALT TEXT](https://github.com/Lekan-E/Udemy-Course-Price-Tracker/blob/2c9bf5adef376cbbba7ac0164805b1beea7ac86e/Misc/udemy-sale.png)
Here is an example of a flash sale, which usually runs from 1-3 days.

## Methodology
### Key Libraries
The project uses several Python libraries for data collection, processing, and automation:
- Pandas: For data manipulation and storage.
- Matplotlib: For visualizing price trends over time.
- OS: To interact with the operating system and access environment variables.
- BeautifulSoup: For parsing HTML and extracting web data.
- Selenium: To automate browser actions for scraping dynamic content.
- Http.Client: For handling HTTP requests and responses.
- Requests: To make HTTP requests for web data.
- Email: To generate and send email alerts.
- SSL: To enable secure connections for email transmission.connections.

### Project Flowcart
Here are the main steps for this projects, which are summarized in the flow chart below:
1. Data Collection: Scrape daily course prices and store them in a CSV file.
2. Data Visualization: Create initial visualizations (line charts) to explore price trends.
3. Email Notification: Send alerts when the course price meets the target discount threshold.
4. Automation: Use Windows Task Scheduler to automate daily script execution for consistent price tracking.

![ALT TEXT](https://github.com/Lekan-E/Udemy-Course-Price-Tracker/blob/2c9bf5adef376cbbba7ac0164805b1beea7ac86e/Misc/Project%20Flowchart.jpg)

## Final Results
A sample email notification includes the current sale price, a link to the course, and a historical price chart to help users make informed purchase decisions.

![alt text](https://github.com/Lekan-E/Udemy-Course-Price-Tracker/blob/2c9bf5adef376cbbba7ac0164805b1beea7ac86e/Misc/sample-email.png)
(ignore the price for now, this is just for illustration purposes)

## Future Improvements
Over time, we will collect price data for multiple courses, enabling us to build a regression model to predict future sale dates and further enhance the tool's value.