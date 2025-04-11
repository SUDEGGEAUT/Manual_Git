# manual_github

# ENVIAR CÓDIGO PARA O GITHUB

cd/

C:\>cd python 2

C:\python 2>git clone https://github.com/SUDEGGEAUT/fala_br.git

C:\python 2>dir


C:\python 2>cd fala_br

C:\python 2\fala_br>dir
 

C:\python 2\fala_br>git add .


C:\python 2\fala_br>git status


C:\python 2\fala_br>git commit -m "Primeiro Upload"


C:\python 2\fala_br>git push --force origin main

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# PARA CRIAR TAG

caso não esteja na pasta: cd (caminho da nova pasta)

git tag – a 1.0.0 -m “v1.0.0” 

git push --tag

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# ATUALIZAR A TAG COM O NOVO CÓDIGO

git pull origin main

git status

git add .

git status

git commit -m "Atualizacao do codigo"

git push --force origin main



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# EXCLUI OU ADD O ARQUIVO QUE ESTA NA PASTA ONDE ESTÁ O PROGRAMA DO GIT

cd/
cd (caminho da pasta)

git status
 ** Verificar se a pasta está no caminho**

git add.

git status

git commit -m "atualizacao"

git push --force origin main

adicionar a tag



----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# PARA APAGAR OS ARQUVIOS E RENOMEAR A PASTA - PROMPT

git clone https://github.com/SUDEGGEAUT/download_protocolo_pdf2page.git

dir

cd **copia o caminho da pasta onde foi baixada**

del (nome do arquivo que eu quero apagar)

dir (conferir se o arquivo foi apaagdo)

git status (verificar se o arquivo foi excluido comparando com o commit anterior)

git commit -m ("atualizacao")

git push --force origin main (pode ser origin main ou origin master)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# RENOMEAR UM ARUIVO NO PROMPT

DIR

**Selecionar o nome do arquivo**

ren (nome atual(espaço)nome atualizado)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# BAIXAR ALGUM ARQUIVO ATUALIZADO DO GITHUB

cd/

cd (caminho do arquivo onde será baixado a atualização)

git clone (LINK DO CODIGO DO GIT)







































