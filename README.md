
# **Manual de Utilização do Git pelo Prompt de Comando**

## **1. Enviar Código para o GitHub**
 ##Se o código é novo:

# Se o código é antigo e foi atualizado:
 # Siga essa ordem de comando: 
''' git status (confirmar o que já foi alterado) git add . | git commit -m "atualizacao" | git push origin main | git tag -a 1.0.x -m "v1.0.x" | git push --tag'''

### **Passo a Passo geral:**
1. Abra o Prompt de Comando.
2. Navegue até o diretório onde deseja trabalhar:
   ```cmd
   cd \
   cd "caminho_da_pasta"
   ```
3. Clone o repositório do GitHub:
   ```cmd
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   ```
4. Verifique os arquivos no diretório:
   ```cmd
   dir
   ```
5. Entre na pasta do repositório clonado:
   ```cmd
   cd SEU_REPOSITORIO
   ```
6. Adicione os arquivos ao controle de versão:
   ```cmd
   git add .
   ```
7. Verifique o status dos arquivos:
   ```cmd
   git status
   ```
8. Faça o commit com uma mensagem descritiva:
   ```cmd
   git commit -m "Descrição do commit"
   ```
9. Envie os arquivos para o repositório remoto:
   ```cmd
   git push origin main
   ```

---

## **2. Criar, Verificar e Fazer Push de uma Tag**

### **Passo a Passo:**

#### **Criar uma Tag**
1. Certifique-se de estar na pasta do repositório:
   ```cmd
   cd "caminho_da_pasta"
   ```
2. Crie uma tag com uma mensagem descritiva:
   ```cmd
   git tag -a 1.0.0 -m "v1.0.0"
   ```

#### **Verificar as Tags Existentes**
1. Liste todas as tags do repositório:
   ```cmd
   git tag
   ```

#### **Fazer Push de uma Tag**
1. Envie uma tag específica para o repositório remoto:
   ```cmd
   git push origin 1.0.0
   ```
2. Para enviar todas as tags de uma vez:
   ```cmd
   git push origin --tags
   ```

---

## **3. Atualizar o Código e a Tag**

### **Passo a Passo:**
1. Baixe as atualizações do repositório remoto:
   ```cmd
   git pull origin main
   ```
2. Verifique o status dos arquivos:
   ```cmd
   git status
   ```
3. Adicione os novos arquivos ou alterações:
   ```cmd
   git add .
   ```
4. Faça o commit com uma mensagem descritiva:
   ```cmd
   git commit -m "Atualização do código"
   ```
5. Envie as alterações para o repositório remoto:
   ```cmd
   git push origin main
   ```
6. Atualize a tag (se necessário):
   ```cmd
   git tag -a 1.0.1 -m "v1.0.1"
   git push --tag
   ```

---

## **4. Excluir ou Adicionar Arquivos no Repositório**

### **Passo a Passo:**
1. Navegue até a pasta do repositório:
   ```cmd
   cd "caminho_da_pasta"
   ```
2. Verifique o status dos arquivos:
   ```cmd
   git status
   ```
3. Adicione ou remova arquivos:
   - Para adicionar:
     ```cmd
     git add nome_do_arquivo
     ```
   - Para remover:
     ```cmd
     git rm nome_do_arquivo
     ```
4. Verifique novamente o status:
   ```cmd
   git status
   ```
5. Faça o commit com uma mensagem descritiva:
   ```cmd
   git commit -m "Descrição da alteração"
   ```
6. Envie as alterações para o repositório remoto:
   ```cmd
   git push origin main
   ```

---

## **5. Renomear Arquivos no Prompt**

### **Passo a Passo:**
1. Liste os arquivos no diretório:
   ```cmd
   dir
   ```
2. Renomeie o arquivo:
   ```cmd
   ren nome_atual.extensao novo_nome.extensao
   ```
3. Verifique se o arquivo foi renomeado:
   ```cmd
   dir
   ```
4. Atualize o repositório:
   ```cmd
   git add .
   git commit -m "Renomeação de arquivo"
   git push origin main
   ```

---

## **6. Baixar Arquivos Atualizados do GitHub**

### **Passo a Passo:**
1. Navegue até o diretório onde deseja baixar o repositório:
   ```cmd
   cd "caminho_da_pasta"
   ```
2. Clone o repositório:
   ```cmd
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   ```
3. Verifique os arquivos baixados:
   ```cmd
   dir
   ```

---

## **7. Apagar Arquivos no Repositório**

### **Passo a Passo:**
1. Navegue até a pasta do repositório:
   ```cmd
   cd "caminho_da_pasta"
   ```
2. Liste os arquivos no diretório:
   ```cmd
   dir
   ```
3. Apague o arquivo desejado:
   ```cmd
   del nome_do_arquivo
   ```
4. Verifique se o arquivo foi apagado:
   ```cmd
   dir
   ```
5. Atualize o repositório:
   ```cmd
   git add .
   git commit -m "Remoção de arquivo"
   git push origin main
   ```

---

## **Dicas Gerais:**
- Sempre use mensagens de commit claras e descritivas.
- Utilize `git status` frequentemente para verificar o estado do repositório.
- Para evitar sobrescrever alterações, use `git pull` antes de fazer `git push`.

---

Com essas instruções, você pode criar, verificar e enviar tags, além de realizar outras operações no Git de forma detalhada e organizada!
