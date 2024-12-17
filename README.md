# Computer Infrastructure Assessments
This repository contains my work for the Computer Infrastructure module at ATU during the 2024-2025 academic year.<br>
## About this project
This project demonstrates how various Linux commands and Python tools are used to process data. It was completed as part of an educational exercise to develop skills in automation, data handling, and analysis. The tasks involve creating directories, fetching data from open sources, and summarizing it using Python libraries.
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
Install them using
``` bash
pip install pandas matplotlib`
```
### Data source:
[Athenry weather data](https://prodapi.metweb.ie/observations/athenry/today)
## Tasks overview
### Task 1: Directory structure
Created the directory `data` with subdirectories `timestamps` and `weather` using Linux commands `mkdir`, `cd`.

### Task 2: Timestamps
Generated a file `now.txt` with timestamps using the `date` command and verified its content with `more`.

### Task 3: Formatted Timestamps
Created a file `formatted.txt` with timestamps in the format YYYYmmdd_HHMMSS using `date +%Y%m%d_%H%M%S`.

### Task 4: Timestamped Files
Automated the creation of empty files named with timestamps using `touch` and embedded `date` commands.

### Task 5: Download Data
Downloaded data from the Athenry weather station using the `wget` command.

### Task 6: Timestamp the Data
Enhanced the `wget` command to save files with timestamped names, making each file uniquely identifiable.

### Task 7: Automating the Process
Created a shell script **weather.sh** to automate the data download process.

## Automated Weather Data Collection Project
The project automates the process of collecting and storing daily weather data using a script and GitHub Actions. The automation runs the script every day at 9 AM, retrieves the data, and updates the repository with the new information.

### Purpose and Use:
The project ensures that weather data is consistently collected, saved, and version-controlled without manual intervention. 
This is particularly useful for:
* Data Tracking: Building a historical record of weather data for analysis or reference.
* Automation Practice: Demonstrating the use of GitHub Actions for scheduling, automating scripts, and managing repositories.
* Reliability: Eliminating the need for manual updates while ensuring data is collected daily.
## Getting help
If you encounter any issues or have questions, feel free to contact me.
## Contribute
Contributions are welcome! Clone the repository, make your improvements or suggestions, and submit a pull request.
## References
[Data sourse](https://data.gov.ie/)<br>
[60 essential Linux commands](https://www.hostinger.com/tutorials/linux-commands)<br>
[The quick and simple editor for cron schedule expressions ](https://crontab.guru/)<br>
[Workflow syntax for GitHub Actions](https://docs.github.com/en/actions/writing-workflows/workflow-syntax-for-github-actions)<br>
## Author
Katerina Lisovenko
Atlantic Technological University Student (2024-2025)
### Disclaimer
AI tools, including GPT-3 (ChatGPT), were used to assist with style and grammar checks, as well as to research additional solutions, while ensuring the accuracy and quality of the work.