

# Computer Infrastructure Assessments
This repository contains my work for the Computer Infrastructure module at ATU during the 2024-2025 academic year.<br>
## About this project
This project demonstrates the use of various Linux commands and Python tools to process data. It was completed as part of an educational exercise to develop skills in automation, data handling, and analysis. The tasks involve creating directories, fetching data from open sources, and summarizing it using Python libraries.
## Use of this project
The project is a practical guide for beginners in Linux and Python, showcasing how to:
* Use shell commands to create and manage files and directories.
* Automate the download of data.
* Utilize Python tools such as pandas for data exploration and analysis.
## Getting started
To work with this project, ensure the following setup:
### Environment:
Install Python (version 3.7 or higher).
Install Jupyter Notebook for running and editing the `.ipynb` file.
### Modules Required:
* pandas: For data analysis.
* matplotlib: For visualizations (optional for future analysis).
Install them using `pip install pandas matplotlib`.
### Data Sourse:
[Athenry weather data](https://prodapi.metweb.ie/observations/athenry/today)
## Tasks Overview
Task 1: Directory Structure
Created a directory data with subdirectories timestamps and weather using Linux commands `mkdir`, `cd`.

Task 2: Timestamps
Generated a file now.txt with timestamps using the `date` command and verified its content with `more`.

Task 3: Formatted Timestamps
Created a file formatted.txt with timestamps in the format YYYYmmdd_HHMMSS using `date +%Y%m%d_%H%M%S`.

Task 4: Timestamped Files
Automated the creation of empty files named with timestamps using `touch` and embedded `date` commands.

Task 5: Download Data
Downloaded data from the Athenry weather station using the `wget` command.

Task 6: Timestamp the Data
Enhanced the `wget` command to save files with timestamped names, making each file uniquely identifiable.

Task 7: Automating the Process
Created a shell script **weather.sh** to automate the data download process. Made the script executable using `chmod u+x` and executed it with `./weather.sh`.

## Getting help
If you encounter any issues or have questions, feel free to contact me.
## Contribute
Contributions are welcome! Clone the repository, make your improvements or suggestions, and submit a pull request.
## References
https://data.gov.ie/<br>
https://www.hostinger.com/tutorials/linux-commands
## Author
Katerina Lisovenko
Atlantic Technological University Student (2024-2025)
### Disclaimer
AI tools, including GPT-3 (ChatGPT), were used to assist with style and grammar checks, as well as to research additional solutions, while ensuring the accuracy and quality of the work.