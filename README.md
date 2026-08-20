# Inicializa o repositório Git
git init
# Adiciona todos os arquivos
git add .
# Cria o primeiro commit
git commit -m "Adiciona index.html e index2.html"
# Define a branch principal como main
git branch -M main
# Conecta ao seu repositório do GitHub (substitua pelo seu link)
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
# Envia os arquivos
git push -u origin main