```bash
┌──(george㉿mastro)-[~/Projects/personal_info] (main ✔)
└─$ git checkout -b feat/add-readme
Switched to a new branch 'feat/add-readme'

┌──(george㉿mastro)-[~/Projects/personal_info] (feat/add-readme ✔)
└─$ cat about_me.json | tail -n 9
  "name": "George",
  "species": "Human",
  "interests": [
    "Learning",
    "Creating",
    "Tinkering"
  ],
  "status": "doing something",
  "license": "MIT",
  "copyright": "© 2026 contributor. All rights reserved."
}

┌──(george㉿mastro)-[~/Projects/personal_info] (feat/add-readme ✔)
└─$ git commit -am "feat(readme): add initial profile config"
[feat/add-readme e4f5a6b] feat(readme): add initial profile config
 1 file changed, 10 insertions(+)

┌──(george㉿mastro)-[~/Projects/personal_info] (feat/add-readme ✔)
└─$ git checkout -b feat/skillset
Switched to a new branch 'feat/skillset'

┌──(george㉿mastro)-[~/Projects/personal_info] (feat/skillset ✔)
└─$ echo "Fetching developer tech stack..."
Fetching developer tech stack...

┌──(george㉿mastro)-[~/Projects/personal_info] (feat/skillset ✔)
└─$ grep -iE "stack|languages|tools" about_me.json || find . -name "*.svg" && echo "SUCCESS"
./assets/badges/tech_stack.svg
SUCCESS

┌──(george㉿mastro)-[~/Projects/personal_info] (feat/skillset ✔)
└─$ git commit -am "feat(skills): configure language & toolset badges"
[feat/skillset c8d9e0f] feat(skills): configure language & toolset badges
 1 file changed, 15 insertions(+)

┌──(george㉿mastro)-[~/Projects/personal_info] (feat/skillset ✔)
└─$ git log -2 --oneline
c8d9e0f (HEAD -> feat/skillset, origin/feat/skillset) feat(skills): configure language & toolset badges
e4f5a6b (feat/add-readme) feat(readme): add initial profile config about myself
```
### 🛠️ Languages & Technologies


<p align="left">
  <img src="https://img.shields.io/badge/C-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /
  <img src="https://img.shields.io/badge/Html-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/Css-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
   <img src="https://img.shields.io/badge/Javascript-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</p>



<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-languages/?username=george-mastro&layout=compact&theme=dracula&hide_border=true" alt="Top Languages" />
</div>
