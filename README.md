
# hackGPT v23 ![hackGPT badge](https://img.shields.io/badge/hackGPT-v23-purple)

Test the app live here: [https://hackgpt.com](https://hackgpt.com)

![Screenshot 2023-04-30 at 6 59 28 PM](https://user-images.githubusercontent.com/3261849/235382192-714758c2-5117-4c95-851d-eeeb9301221f.png)
![Screenshot 2023-05-11 at 12 09 48 PM](https://github.com/NoDataFound/hackGPT/assets/3261849/f8f85831-706f-4398-9da1-365323f656bd)
![WhiskersGPT](https://github.com/NoDataFound/hackGPT/assets/3261849/2157a52a-5f77-4d23-a6ca-c80d917b2bf8)
![Screenshot 2023-04-29 at 2 42 41 PM](https://user-images.githubusercontent.com/3261849/235321459-35eb1ecb-58b6-4439-9fee-dbc63e13f3e1.png)
![Screenshot 2023-04-24 at 8 41 52 PM](https://user-images.githubusercontent.com/3261849/234341399-f79b9ca3-e829-4831-8e67-e75e8840adfd.png)

## Features

### 1. Hunt for JIRA issues
Automate the process of finding and fixing JIRA issues labeled as `type=bug`. Commit the fixes back to the ticket as a comment.

![JIRA Bug Fixing](https://user-images.githubusercontent.com/3261849/228703126-adf614ba-d931-4ec0-8d1a-99654063058b.mp4)

### 2. Launch hackGPT with Python
Load the chatbot in a new tab of your active browser with PrettyTable for logging.

![PrettyTable Logging](https://user-images.githubusercontent.com/3261849/222942128-3f75b9b7-5763-4a0c-a4df-aadbb24dcf5d.mp4)

### 3. hackGPT enabled Siri
Integrate with Siri for voice command functionality.

![Siri Integration](https://user-images.githubusercontent.com/3261849/222963874-096f2add-ffa9-40be-a7f2-8c604cf5e3b2.png)

### 4. Automate CVE exploit creation and CyberDefense protections
Generate exploits and defenses automatically.

![Automate CVE Exploit](https://user-images.githubusercontent.com/3261849/207626394-cb272c96-c370-4870-9a13-6d43397fb830.png)

### 5. Mobile compatibility
Use hackGPT on mobile devices.

![hackGPT on Mobile](https://user-images.githubusercontent.com/3261849/218890190-e4edceff-ca65-4db0-93ee-82aa055eb576.png)

### 6. Parsing and analysis of JSON threat data
Automate the parsing and analysis of JSON threat data from CyberDefense tools.

![JSON Parsing](https://user-images.githubusercontent.com/3261849/217700643-ab202279-9558-41da-83db-ce64f7e796a1.png)

## Installation

### Clone the repository
\`\`\`bash
git clone https://github.com/NoDataFound/PwnAI.git
\`\`\`

#### Alternatively, clone via SSH
\`\`\`bash
git clone git@github.com:NoDataFound/hackGPT.git
\`\`\`

### Setup virtual environment (optional)
\`\`\`bash
python3 -m venv env
source env/bin/activate
\`\`\`

### Install dependencies
\`\`\`bash
python3 -m pip install -r requirements.txt
\`\`\`

### Review Input and Bulk Input samples
\`\`\`bash
head -n 10 input/malware/malware_sample && head -n 10 input/sample_sources
\`\`\`

### Open Jupyter Notebook
Install Jupyter Notebook if needed:
\`\`\`bash
pip3 install jupyter notebook
\`\`\`

### Launch Notebook with VSCode
Install the Jupyter extension from the marketplace: [Jupyter Renderers](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers)

### Configure .env with your OpenAI API key
The notebook will assist you in setting the API key.

### Use Python
#### Set API key on launch
![Set API Key](https://user-images.githubusercontent.com/3261849/205458244-ed556dd8-c8d8-498d-9a1d-727d139e46d7.png)

#### Single searches
\`\`\`bash
python3 PwnAI.py
\`\`\`

![Single Search](https://user-images.githubusercontent.com/3261849/205525796-d8d009b5-9d76-4b04-ae24-319e5f1ea924.png)

#### Bulk searches
\`\`\`bash
python3 PwnAI_bulk.py
\`\`\`

![Bulk Search](https://user-images.githubusercontent.com/3261849/205525811-8c5eb58b-257e-4412-a462-89f0c3ccb5be.png)
