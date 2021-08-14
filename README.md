
# ola este projeto da dica  sobre o git
git --version 
# inicializar um repositoria vazio
git init 
# "nome do arquivo"  para um aquivo especifico  ou ."ponto" para enviar todos os arquivos : este comado  mando o arquivo para  area de start "é famozo comit"
git add 

# este comado exibe as aquivo comitado
git status 

# esta comado faz o envio do arquivo  
git commit -m "primeiro comit" 

# este comado é para remonear o a branch que eu estou utilizando 
git branch -m" main" 

 # este comado faz  a conecção do meu repasitorio git local  com o do githib cujo nome é origin  e so utilizamos este comado uma unica fez por projeto criado

 git remote add origin https://github.com/RRobDaltro/Projeto1.git

# esta comado  faz o empurrao do meu commit ja realizado com o meu repositorio github 
 git branch -M main
git push -u origin main

# para criar uma nova branch: branch é uma nova ramificação no projeto normalmento uma fitnion tais como um botao para o projeto com o comado 
git checkout -b "nome do arquivo"
# para verificar ou voltar para branch o comado é
git checkout "nome da branch" main

