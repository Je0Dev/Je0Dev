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
c8d9e0f (HEAD -> feat/skillset, origin/feat/skillset) feat(skills): configure personal badges
e4f5a6b (feat/add-readme) feat(readme): add initial profile config about myself
```
<p align="left">
  <!-- TypeScript -->
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-90%25-brightgreen?style=for-the-badge" />
  <br />
  <!-- Rust -->
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-80%25-green?style=for-the-badge" />
  <br />
  <!-- Python -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-80%25-green?style=for-the-badge" />
  <br />
  <!-- JavaScript -->
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Confidence-75%25-green?style=for-the-badge" />
  <br />
  <!-- C -->
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-70%25-yellowgreen?style=for-the-badge" />
  <br />
  <!-- LaTeX -->
  <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-65%25-yellowgreen?style=for-the-badge" />
  <br />
  <!-- Java -->
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-60%25-yellow?style=for-the-badge" />
  <br />
  <!-- HTML5 -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-60%25-yellow?style=for-the-badge" />
  <br />
  <!-- CSS3 -->
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-50%25-orange?style=for-the-badge" />
  <br />
  <!-- MySQL -->
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Confidence-50%25-orange?style=for-the-badge" />
</p>
