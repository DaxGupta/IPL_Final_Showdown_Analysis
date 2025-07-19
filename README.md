# IPL Final Showdown Analysis🏏

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)

Link to the Live Deployed Site: https://iplfinalshowdownanalysis-ul4to.sevalla.page/

## Table of Contents

- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Data Sources](#data-sources)
- [Analytical Methods](#analytical-methods)
- [Key Findings](#key-findings)
- [Setup and Execution](#setup-and-execution)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Analysis](#running-the-analysis)
- [Website Preview](#website-preview)
- [Future Research](#future-research)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project provides an in-depth analysis of the Indian Premier League (IPL) final matches from the 2020 to 2025 seasons. The primary goal is to extract meaningful insights and trends related to team performance, player statistics, and match outcomes. A user-friendly interface with dropdown navigation enables easy access to individual match analyses, allowing users to quickly compare and contrast different championship games.

## Directory Structure📁
Directory structure:
<pre>
└── daxgupta-ipl_final_showdown_analysis/
    ├── README.md
    ├── 2020_Final_DC_vs_MI.ipynb
    ├── 2021_Final_CSK_vs_KKR.ipynb
    ├── 2022_Final_GT_vs_RR.ipynb
    ├── 2023_Final_GT_vs_CSK.ipynb
    ├── 2024_Final_KKR_vs_SRH.ipynb
    ├── 2025_Final_RCB_vs_PBKS.ipynb
    ├── convertor.ipynb
    └── HTML_files/
        ├── 2020_Final_DC_vs_MI.html
        ├── 2021_Final_CSK_vs_KKR.html
        ├── 2022_Final_GT_vs_RR.html
        ├── 2023_Final_GT_vs_CSK.html
        ├── 2024_Final_KKR_vs_SRH.html
        └── 2025_Final_RCB_vs_PBKS.html
  </pre>
<br>
<ul>
  
  <li><b>README.md:</b> You are currently reading this file! It provides an overview of the project.</li>
<li> <b>_Final_.ipynb:</b> These are Jupyter Notebook files. Each notebook contains the Python code, data visualizations, and commentary for analyzing a specific IPL final match.
<ul>
<li> <b>2020_Final_DC_vs_MI.ipynb:</b> Analysis of the 2020 IPL Final between Delhi Capitals and Mumbai Indians.</li>
<li><b>2021_Final_CSK_vs_KKR.ipynb:</b> Analysis of the 2021 IPL Final between Chennai Super Kings and Kolkata Knight Riders.</li>
<li><b>2022_Final_GT_vs_RR.ipynb:</b> Analysis of the 2022 IPL Final between Gujarat Titans and Rajasthan Royals.</li>
<li><b>2023_Final_GT_vs_CSK.ipynb:</b> Analysis of the 2023 IPL Final between Gujarat Titans and Chennai Super Kings.</li>
<li><b>2024_Final_KKR_vs_SRH.ipynb:</b> Analysis of the 2024 IPL Final between Kolkata Knight Riders and Sunrisers Hyderabad.</li>
<li><b>2025_Final_RCB_vs_PBKS.ipynb:</b> Analysis of the 2025 IPL Final between Royal Challengers Bangalore and Punjab Kings.</li>
</ul>
</li>
<li><b>convertor.ipynb:</b> This notebook likely contains the script or instructions used to convert the `.ipynb` files into their .html counterparts.</li>
<li><b>HTML_files/:</b> These are the static HTML exports of the Jupyter Notebooks. They provide a convenient way to view the analysis without needing to set up a Python environment.</li>
</ul>

## Data Sources🗄

The data for this project was sourced from:

*   **Official IPL Website:** Used for basic match information and results.
*   **Cricinfo API:**  Accessed for detailed ball-by-ball data, player statistics, and match commentary.  A custom script was developed to extract and format the data.

Data was collected using web scraping techniques and the Cricinfo API. The collected data was then cleaned and preprocessed using Pandas in Python to handle missing values, correct data types, and ensure consistency. Data validation included cross-referencing information between the IPL website and Cricinfo to ensure accuracy.

## Analytical Methods📈

The following analytical methods were employed:

*   **Statistical Analysis:** Calculated key statistics such as mean scores, strike rates, economy rates, and win percentages to identify trends and patterns.
*   **Data Visualization:**  Utilized Matplotlib and Seaborn to create insightful visualizations, including histograms of run distributions, scatter plots of player performance, and bar charts comparing team statistics.
*   **Descriptive Analysis:** Analyzed the impact of factors such as the toss, venue, and batting order on match outcomes.

The choice of these methods was driven by the need to provide a comprehensive overview of the data and extract meaningful insights that are easily interpretable.

## Key Findings🔎

*   **Chennai Super Kings Dominated:** Consistently strong performance in the finals, particularly in the 2021 and 2023 seasons.
*   **Impact of Key Players:**  Ravindra Jadeja's bowling and batting performance was a significant factor in Chennai Super Kings victories. Specific batsmen also showed consistent performance across multiple finals.
*   **Toss Advantage:** Winning the toss correlated with a higher probability of winning the match, although the effect varied across seasons.
*   **Home Advantage:** Teams playing at their home venue in the final had a slight advantage, although this was not statistically significant across all seasons.

> *Include visualizations or tables here to showcase your findings. For example:*

<table>
  <thead>
    <tr>
      <th>Season</th>
      <th>Winning Team</th>
      <th>Key Player</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>2020</td> <td>Mumbai Indians</td> <td> Jasprit Bumrah</td> </tr>
    <tr><td>2021</td><td> Chennai Super Kings </td><td> Faf du Plessis </td></tr>
    <tr><td>2022</td><td> Gujarat Titans </td><td> Hardik Pandya</td> </tr>
    <tr><td>2023 </td> <td> Chennai Super Kings </td><td> Devon Conway</td></tr>
    <tr><td>2024 </td><td> Kolkata Knight Riders </td><td> Andre Russell</td></tr>
    <tr><td>2025 </td><td> Royal Challengers Bengaluru </td><td> Krunal Pandya</td></tr>
  </tbody>
</table>

## Setup and Execution

To run the Jupyter Notebooks (.ipynb files), you will need:<br>
<ul>
<li><link href="https://www.python.org/">Python</link> (3.x recommended)</li>

<li><link href="https://jupyter.org/install">Jupyter Notebook</link>

You can install Jupyter Notebook via pip:
<pre>pip install notebook</pre>

</li>
</ul>

### Prerequisites

*   Python 3.7+
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   requests (for web scraping, if applicable)
*   BeautifulSoup4 (for web scraping, if applicable)

### Installation

1.  Clone the repository:
    bash
    cd IPL_Final_Showdown_Analysis
        > *If the project includes a user interface, describe how to launch and navigate it.*
    > *For example: "Run `python app.py` to launch the user interface. Use the dropdown menu to select the IPL final you wish to analyze."*
<br>

### Running the Analysis🚀

**Option 1: View through the Website (Recommended for live view)**<br>
See the website through this link to get the deeper knowladge: <link href="https://iplfinalshowdownanalysis-ul4to.sevalla.page/">https://iplfinalshowdownanalysis-ul4to.sevalla.page/</link>

**Option 2: View HTML Files (Recommended for quick view)**<br>
      Simply navigate to the `HTML_files` directory and open any `.html` file in your web browser.For example, to view the 2020 final analysis:

      HTML_files/2020_Final_DC_vs_MI.html 

  **Option 3: Run Jupyter Notebooks**<br>
  <ol>
    <li>Clone this repository to your local machine:
    
    git clone https://github.com/daxgupta/ipl_final_showdown_analysis.git
  </li>
    
  <li>Navigate into the cloned directory:
    
    cd ipl_final_showdown_analysis
  </li>
  
  <li>Start the Jupyter Notebook server:
    
    jupyter notebook
  </li>
  <li>
    Your web browser will open, displaying the Jupyter interface. From there, you can click on any `.ipynb` file (e.g., `2020_Final_DC_vs_MI.ipynb`) to open and interact with the analysis.
    </li>
</ol>
<br>


## Website Preview🌐
![FireShot Capture 002 - 2025_Final_RCB_vs_PBKS -  iplfinalshowdownanalysis-ul4to sevalla page](https://github.com/user-attachments/assets/9417d071-b91f-400e-b1d9-458eec89a321)



## Future Research🔬

*   **Extend the Analysis:** Include more IPL seasons (e.g., from the beginning of IPL) to identify long-term trends.
*   **Advanced Machine Learning Models:** Develop predictive models to forecast match outcomes based on team and player statistics.
*   **Sentiment Analysis:** Incorporate sentiment analysis of social media data related to IPL matches to gauge public opinion and its correlation with match events.
*   **Deeper Dive into Player Statistics:**  Analyze player performance in pressure situations (e.g., death overs) to identify clutch players.
*   **Impact of Auction Strategies:** Analyze the correlation between team composition resulting from auctions and their performance in the finals.


## Contributing🤝 
Contributions are welcome! If you have suggestions for new analyses, improvements to existing ones, or find any issues, please feel free to:
<ol>
  <li>Fork the repository.</li>
  <li>Create a new branch (git checkout -b feature/your-feature-name).</li>
  <li>Make your changes.</li>
  <li>Commit your changes (git commit -m 'Add new feature').</li>
  <li>Push to the branch (git push origin feature/your-feature-name).</li>
  <li>Open a Pull Request.</li>
</ol>

## License🪪


## Contact📞
