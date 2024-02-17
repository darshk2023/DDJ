Basketball Analysis Toolkit
This toolkit is designed to provide comprehensive analysis for basketball players and teams through interactive spider plots. It leverages data to compare performance across various metrics and generates advice for improvement or strategy adjustment.

Features
Player Analysis: Compare two players based on performance metrics such as usage percentage, win shares, and more.
Team Analysis: Compare two teams based on game performance metrics like points per game, turnovers per game, etc.
Advice Generation: Offers strategic advice based on the analysis to improve performance or exploit opponents' weaknesses.
Setup
To run this notebook, you will need Python installed on your system along with the following libraries:

customtkinter: For the GUI components.
tkinter: Standard Python GUI library used alongside customtkinter for additional features.
pandas: For data manipulation and analysis.
plotly: For creating interactive plots.
webbrowser: For displaying plots in a web browser.
tempfile & os: For temporary file management and OS-related operations.
Installation
Ensure you have Python installed, then install the required libraries using pip:

sh
Copy code
pip install customtkinter pandas plotly
Note: tkinter is typically included with Python, and webbrowser, tempfile, and os are part of the Python Standard Library.

Usage
Start the Application: Run the notebook to launch the GUI.
Choose Analysis Type: Select either 'Player Analysis' or 'Team Analysis'.
Input Names and Years: Enter the names of the players or teams you wish to compare, along with the year(s) for analysis.
Submit for Analysis: Click the 'Submit' button to generate the spider plot and view the comparison.
View Advice: After the analysis, a window will pop up with customized advice based on the comparison.
Data
The application requires two CSV files for its data source:

NBA_Players.csv: Contains player performance metrics.
TeamPerGame.csv: Contains team performance metrics.
Ensure these files are correctly formatted and located in the same directory as the notebook for the application to function properly.

Contributing
Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

License
This project is open-source and available under the MIT License.

This README provides a general overview and instructions for using the notebook. You may need to adjust paths, filenames, or installation commands based on your specific environment or if you make modifications to the notebook.





