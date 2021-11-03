# github-org-box
Code for generate a github organization overview including security insights

Requirements:  Git + Python3 + Python3-pip
>
> sudo apt install -y git python3 python3-pip
> 
#### Script Steps:

What the output show us?

- Date of execution;
- Organization name;
- Total repository count;
- Public repositories;
- All used languages;
- 5 most common used languages;
- Total members count;
- Team names;
- Name of Administrators;
- Archived repositories count;
- Forked repositories names;
- Repositories with vulnerable libs.

About each repository:

- Name;
- If is private;
- If readme file exist;
- All topics;
- Endpoint link;
- Last Update in days;
- If the repository has protection rule (>1 reviewers) for Master Branch;
- Teams with access;
- If security alerts is active;
- Number of vulnerable libs. 

Todo:
- [ ] If dependabot alerts is active by default
- [ ] Containerization
- [ ] Create a dashboard

#### How-to:
> git clone https://github.com/lucas-apd/github-org-box.git
> 
> cd github-org-box
> 
> pip3 install -r requirements.txt
> 
> export GITHUB_TOKEN=< YOUR-TOKEN-HERE >
>  
> export GITHUB_ORG=< YOUR-ORG-NAME-HERE >
>  
> python3 main.py
  

  
  
**The result is a file like [github_full_report_orgname.json](https://github.com/lucas-apd/github-org-box/blob/main/example.report.json)**

Help me!
