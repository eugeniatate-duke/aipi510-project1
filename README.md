## Project 1: The Youth Red Wave

## Overview  
I analyzed American National Election Studies (ANES) data to explore whether young voters (18–29) are leaning more conservative, contributing to a broader “red wave.” I compared partisan identification across age groups and created new features to highlight generational trends.  

## Blog Post 
https://bylinedocs.com/published/9727ae27-7350-4888-b077-358bfd11e642 

---

## Dataset  
- **Source:** ANES Guide to Public Opinion and Electoral Behavior  
- **Citation:** American National Election Studies. [https://electionstudies.org](https://electionstudies.org) https://electionstudies.org/data-tools/anes-guide/anes-guide.html?chart=party_identification_7_pt 
- **Description:** The ANES dataset provides survey responses from U.S. citizens across election years (1952–present). Respondents report their partisan identification (Strong Democrat → Strong Republican) along with demographic subgroups.  
- **Subset used in this project:** Age demographics (`18–29`, `30–44`, `45–59`, `60+`).  
- **Variables included:**  
  - `Year` – survey year  
  - `Subgroup` – age group  
  - `Total Cases` – number of respondents in the subgroup  
  - Partisan ID counts (Strong Democrat, Weak Democrat, Independent Democrat, Independent, Independent Republican, Weak Republican, Strong Republican)  
  - Derived percentages (`D %`, `R %`, `I %`)  
---

## How to Reproduce  
1. Clone the repo and enter the folder:  
   ```bash
   git clone https://github.com/eugeniatate-duke/aipi510-project1.git
   cd aipi510-project1

2. Create a virtual environment and install requirements: 
    python -m venv venv
    source venv/bin/activate      # Mac/Linux  
    venv\Scripts\activate         # Windows  
    pip install -r requirements.txt

3. Run notebook: 
    jupyter notebook project1.ipynb


