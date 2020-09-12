## Comandos para criar um repositório GIT a partir de um diretório existente

```
cd existing_folder
git init
git remote add origin https://<endereco do repositório>.git
git add .
git commit -m "Initial commit"
git push -u origin master
git config --global user.name "Your Name"
git config --global user.email you@example.com
git commit --amend --author='Your Name <you@example.com>'
```

## Criar um branch cópia do branch master

```
git checkout master
git checkout -b <novo branch>
```

## Veja mais

https://education.github.com/git-cheat-sheet-education.pdf
