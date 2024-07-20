# numero-secreto

[Programação > Lógica de Programação > Git e GitHub: compartilhando e colaborando em projetos](https://cursos.alura.com.br/course/git-github-compartilhando-colaborando-projetos)

```bash
echo "# numero-secreto" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main
git remote add origin https://github.com/juliomendes160/alura.git
git push -u origin main

ssh-keygen -t ed25519 -C "juliomendes160@hotmail.com"

git clone https://github.com/juliomendes160/alura.git

git status
git add .
git log

git remote
git push origin main

git pull origin main

git revert 903a35a045bde41a4581166e39de02643d5989aa

git commit --amend -m "last commit"
```