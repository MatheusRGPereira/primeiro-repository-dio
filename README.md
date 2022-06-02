# Introdução ao Git e Github 📖🟢
Introdução as formatos de segurança e comando para versionamento de codigo git

 #### 🚀 Utilização das chaves de acesso SSH Keys
 
1. Agora va até no seu desktop e de um git bash
2. Escreva o seguinte codigo **ssh-keygen -t ed25519 -C seuemail@gmail.com**
3. Coloque sua senha
4. va até a pasta onde a chave foi criada utilizando o comando cd geralmente é **/c/user/Nome/.ssh**
5. Use o comando **cat id_ed25519.pub** e copie a chave (guarde essa chave)
6. Abra as configurações (settings) no canto superior direito
7. Clique em SSH and GPG
8. Clique em new key
9. De um titulo para essa chave e cole a chave criada la no git bash na aba KEY.
10. E agora para utilizar essa chave nos seus codigo utilize o comando **eval $(ssh-agent -s)** vai ser passado o agent pid que é o seu codigo de iniciação
11. Utilize o comando **ssh-add id_ed25519** coloque a senha que voçe passou lá no passo 3 E está pronto a sua chave de acesso!!

#### 🚀 Utilização Do token de autenticação
1. Va até o canto superior direito em settings clique em Developer setting
2. Clique em Personal access token
3. Generate new token
4. Coloque sua senha do github
5. De um nome para esse token
6. Acione o botão repo para que possa fazer suas movimentações dentro do github
7. Copie esse token em algum lugar seguro e utilize sempre quando for solicitado uma autenticação quando estiver utilizando o git
#### 🚀 Iiciando um novo repositorio no gitHub
1. Crie um novo repositorio no github, de um nome para esse repositorio adicione um readme
2. Copie o link https no seu repositorio
3. va até a sua pasta de trabalho e de o comando  **git init** para inicializar o repositorio local
4. Utilize o seguinte comando para inicar o repositorio remoto a essa local de trabalho **git remote add origin (o link https que foi copiado do repositorio)**
5. Utilize o comando para puxar os arquivos do repositorio remoto **git pull origin (nome da branch)**
6. Pronto ja pode começar a codar!!!!

#### 🚀 Fazendo alterações no seu codigo
1. Utilize o comando **git add .** para adicionar as modificações que estão prontas para commits
2. Utilize o comando **git commit -m "Comentario sobre a modificação"** para que crie uma um ponto de marcação naquela parte especifica do codigo
3. E por ultimo utilize o comando **git push origin (nome da branch)** para que essas modificações subam para o repositorio remoto!!!



🎁 Obrigada @DIO pelos aprendizados nessa trilha 

