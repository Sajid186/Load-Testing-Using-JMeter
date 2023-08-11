# Load-Testing-Using-JMeter
This repository contains the results of load testing conducted on Dhaka Snob.com (https://www.dhakasnob.com/) using Apache JMeter, a powerful open-source tool for performance and load testing. The primary objective was to assess the website's performance under different load conditions. The test plan, summary report, and supporting files are provided to facilitate analysis and insights.

# Load Testing Summary
Test Setup-
->Test Plan: DhakaSnob.jmx
->Output Log: report.csv
->Results Dashboard: index.html

# How to View the Results
1.Download the report.csv file.
2. Open the summary report in a spreadsheet software for detailed analysis.
To view the graphical results, follow these steps:
Download the full results folder: results
Open a web browser.
Navigate to the index.html file

# Commands Used for Generating Report
>jmeter -n -t "E:\JMeter\DhakaSnob.jmx" -l "E:\JMeter\report.csv" -e -o "E:JMeter\results"

# Some Snippets from Generated Report Interface
![Jm1](https://github.com/Sajid186/Load-Testing-Using-JMeter/assets/69852376/5cc9383e-1f31-458b-b487-b0a3afde2853)
![JM2](https://github.com/Sajid186/Load-Testing-Using-JMeter/assets/69852376/75298d8a-3d82-434c-bd14-a97e581d716a)
![Jm3](https://github.com/Sajid186/Load-Testing-Using-JMeter/assets/69852376/63454998-1a62-4891-82af-1c50b581e797)
![Jm4](https://github.com/Sajid186/Load-Testing-Using-JMeter/assets/69852376/3224af5f-b086-4b80-abe3-7bc40da08491)
![Jm5](https://github.com/Sajid186/Load-Testing-Using-JMeter/assets/69852376/ea0731e6-9af4-4f47-9be6-a0d2dec437e6)
![Jm6](https://github.com/Sajid186/Load-Testing-Using-JMeter/assets/69852376/ac6c7ac8-b657-47f4-b9ca-1d28725c6b69)
![Jm7](https://github.com/Sajid186/Load-Testing-Using-JMeter/assets/69852376/89375347-19c1-4044-85e4-d7a806865ed9)

# Notes
This repository aims to provide transparency and insights into the load testing process for Dhaka Snob.com. The summary report, along with the JMeter test plan and results, can be used for performance analysis and optimization. It is a valuable resource for those interested in load testing methodologies, JMeter usage, and understanding the performance characteristics of web applications.

We encourage collaboration, feedback, and further exploration of the results to enhance the website's performance and user experience.

For any questions or suggestions, please feel free to reach out.

(Note: The provided .jmx files, report.csv, and results folder will be available in this repository for further examination.)

