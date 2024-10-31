# <p>DevDocsHub: Your One-Stop Shop for Programming Documentation
<img  src="https://readme-typing-svg.herokuapp.com?color=45ffaa&size=40&width=900&height=80&lines=Welcome-to-DevDocsHub"/>
</p>

DevDocsHub is a powerful Django-based web application designed to empower developers and learners. It aims to be the ultimate resource for programming knowledge and open-source exploration, offering a user-friendly interface and a wealth of essential materials.
<br/>
<table align="center">
    <thead align="center">
        <tr border: 2px;>
            <td><b>🌟 Stars</b></td>
            <td><b>🍴 Forks</b></td>
            <td><b>🐛 Issues</b></td>
            <td><b>🔔 Open PRs</b></td>
            <td><b>🔕 Close PRs</b></td>
        </tr>
     </thead>
    <tbody>
      <tr>
          <td><img alt="Stars" src="https://img.shields.io/github/stars/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
          <td><img alt="Forks" src="https://img.shields.io/github/forks/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
          <td><img alt="Issues" src="https://img.shields.io/github/issues/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
          <td><img alt="Open Pull Requests" src="https://img.shields.io/github/issues-pr/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
          <td><img alt="Closed Pull Requests" src="https://img.shields.io/github/issues-pr-closed/andoriyaprashant/DevDocsHub?style=flat&color=critical&logo=github"/></td>
      </tr>
    </tbody>
</table>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

**Why Use DevDocsHub?**

* **Consolidated Knowledge:** DevDocsHub brings together comprehensive documentation for various programming languages, information on popular open-source projects, and step-by-step tutorials in a single, centralized platform.
* **Enhanced Learning:** By streamlining access to valuable resources, DevDocsHub simplifies the process of acquiring and strengthening technical skills.
* **Improved Efficiency:**  No more hunting for information scattered across the web. DevDocsHub provides an efficient way to find what you need, enabling developers of all levels to work more productively.
<div align="center">
    <br>
    <!-- Table for GitHub Repo Stats -->
    <table align="center" border="1" cellpadding="10" cellspacing="0">
        <thead align="center">
            <tr>
                <td><b>🌟 Stars</b></td>
                <td><b>🍴 Forks</b></td>
                <td><b>🐛 Issues</b></td>
                <td><b>🔔 Open PRs</b></td>
                <td><b>🔕 Closed PRs</b></td>
                <td><b>🛠️ Languages</b></td>
                <td><b>🌐 Contributors</b></td>
            </tr>
        </thead>
        <tbody align="center">
            <tr>
                <td><img alt="Stars" src="https://img.shields.io/github/stars/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
                <td><img alt="Forks" src="https://img.shields.io/github/forks/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
                <td><img alt="Issues" src="https://img.shields.io/github/issues/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
                <td><img alt="Open Pull Requests" src="https://img.shields.io/github/issues-pr/andoriyaprashant/DevDocsHub?style=flat&logo=github"/></td>
                <td><img alt="Closed Pull Requests" src="https://img.shields.io/github/issues-pr-closed/andoriyaprashant/DevDocsHub?style=flat&color=critical&logo=github"/></td>
                <td><img alt="GitHub language count" src="https://img.shields.io/github/languages/count/andoriyaprashant/DevDocsHub?style=flat&color=critical&logo=github"/></td>
                <td><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/andoriyaprashant/DevDocsHub?color=2b9348"/></td>
            </tr>
        </tbody>
    </table>
    
   <br>
    <!-- Repository link -->
    <a href="https://github.com/andoriyaprashant/DevDocsHub" target="_blank">
        <strong>Check out the DevDocsHub repository on GitHub</strong>
    </a>
</div>

* **Table of Contents**
   - [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Data Insertion Guide](#data-insertion-guide)
   - [Contributing to DevDocsHub](#contributing-to-devdocshub)
   - [License](#license)
   - [Contact](#contact)


**Getting Started**

DevDocsHub is easy to set up and use. Here's a quick guide:

**Prerequisites:**

* Python 3.x installed on your system
* Basic knowledge of Git version control (recommended)

**Installation:**

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/andoriyaprashant/DevDocsHub.git
   cd DevDocsHub
   ```

2. **Create and Activate a Virtual Environment:**

   This step isolates project dependencies and avoids conflicts with your system-wide Python installation. 

   **Windows:**

   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

   **macOS/Linux:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies:**

   ```bash
   pip install <package_name>
   ```

4. **Apply Database Migrations:**

   This step prepares the database schema for the application:

   ```bash
   python manage.py migrate
   ```

5. **Start the Development Server:**

   This command launches DevDocsHub locally for testing and development:

   ```bash
   python manage.py runserver
   ```

   By default, the server will be running at `http://127.0.0.1:8000/`. You can access DevDocsHub in your web browser at this address.

6. **Data Insertion Guide for ProgrammingLanguage and Documentation Models**

This guide explains how to add data to the `ProgrammingLanguage` and `Documentation` models from JSON files using Django's `loaddata` command.

   #python manage.py loaddata <json_file_name.json>
   
   ```bash
   python manage.py loaddata programminglanguage.json
   python manage.py loaddata docomentation.json
   ```
![download](https://github.com/user-attachments/assets/f9dd9390-b451-4937-9986-8eab1a48fdd2)

**Contributing to DevDocsHub**

We welcome contributions from the community! Here's how to get involved:

1. **Fork the Repository:**

   Head over to the DevDocsHub project on GitHub and click the "Fork" button to create your own copy. 

2. **Clone Your Fork:**

   Use Git to clone your forked version of the repository locally:

   ```bash
   git clone https://github.com/your-username/DevDocsHub.git
   ```
   Replace `your-username` with your actual GitHub username.

3. **Create a Branch:**

   Before making changes, create a new branch to isolate your work:

   ```bash
   git checkout -b your-feature-name
   ```
   Replace `your-feature-name` with a descriptive name for your changes.

4. **Make Your Changes:**

   Edit the relevant files and make your contributions to the project.

5. **Commit Your Changes:**

   Once you're happy with your work, stage the changes and commit them to your local branch:

   ```bash
   git add .
   git commit -m "Your informative commit message"
   ```

6. **Push Your Changes:**

   Push your changes to your forked repository on GitHub:

   ```bash
   git push origin your-feature-name
   ```

7. **Create a Pull Request:**

Head back to your forked repository on GitHub and navigate to the "Pull requests" tab. Click on "New pull request" to submit your changes for review and potential merging into the main DevDocsHub repository.

**License:**
Licensed

**Contact Information:**
For any issue in contribution, contact @andoriyaprashant .


**We appreciate your contributions!**


  




