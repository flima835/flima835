## Oiii eu sou a Felipe Lima, criador de conteúdo para cultura SRE/DevOps!

import requests

def get_repository_stats(owner, repo):
    url = f"https://api.github.com/repos/{owner}/{repo}/stats/contributors"
    response = requests.get(url)
    
    if response.status_code == 200:
        stats = response.json()
        return stats
    else:
        print("Error:", response.status_code)
        return None

owner = "username"
repo = "repository_name"
stats = get_repository_stats(owner, repo)

if stats:
    print("Contributors statistics:")
    for contributor in stats:
        print(f"Contributor: {contributor['author']['login']}")
        print(f"Total commits: {contributor['total']}")
else:
    print("Failed to fetch repository statistics.")


<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="Rafa-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="Rafa-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
</div>
  
  ##
 
<div> 
  
   
  <a href = "mailto:flima835@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/ink-felipe-lima/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  
</div>
