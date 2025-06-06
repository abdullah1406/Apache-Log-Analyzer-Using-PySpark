# Apache-Log-Analyzer-Using-PySpark
## Project Description
This project offers an efficient and scalable approach for analyzing Apache HTTP access logs using Apache Spark’s Python interface — PySpark. Built with a focus on Big Data Security, it processes large volumes of unstructured log data to extract valuable insights related to system activity and potential security threats.

The application utilizes regular expressions to parse key fields from the logs, such as IP addresses, timestamps, request methods, URLs, status codes, and response sizes. By leveraging PySpark’s parallel processing capabilities, the system handles large-scale data analysis with speed and reliability.
 
Post data extraction, various analytical operations are performed, including detecting the most frequent IPs, identifying popular endpoints, and categorizing HTTP response codes. For better understanding and reporting, the outcomes are visualized using Matplotlib. Additionally, the system highlights anomalies by filtering out suspicious 4xx and 5xx status codes, which often signal potential attacks or server misconfigurations.
 
This solution is developed on Google Colab, making it easily accessible without needing a local Spark setup. Overall, the project showcases how big data tools can be effectively used to transform raw server logs into meaningful cybersecurity insights.
## Technologies Used
* Apache Spark

* PySpark

* Google Colab

* Regular Expressions (Regex)

* Matplotlib

* Pandas

* Apache HTTP Access Logs

## Author
Muhammad Abdullah Bajwa  
BS Cyber Security and Digital Forensics  
Big Data Security - Log Analyzer using Apache Spark
