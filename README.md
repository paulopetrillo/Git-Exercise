<h1>Praticando Comandos Git</h1>
<h2><b>Preparatório</b></h2>
<p>Antes de tudo é necessario realizar a instalação do Git: <a href="https://git-scm.com/downloads">https://git-scm.com/downloads</a></p>
<p>Após feita a instalação abra o terminal e utilize o comando Git, caso apareça informações sobre comandos relativos ao Git a instalação foi feita com sucesso, caso contrário há de verificar, pois a instalação não foi feita corretamente.(Até onde eu sei, kkkk...)</p>

<p>O exercicio será composto de alguns comandos padrões com o objetivo de colocar seu nome dentro do arquivo participantes</p>

<h2><b>Prática</b></h2>
<p>Faça um clone do projeto em seu computador</p>
<b>Comando: <pre>git clone https://github.com/Didimoykds/Git-Exercise.git</pre></b>
<p>Abra o projeto com alguma IDE ou Editor de Texto e então crie uma nova branch</p>
<b>Comando: <pre>git checkout -b seu-nome</pre></b>
<p>Coloque seu nome no arquivos participantes, porém siga o padrão do arquivo, salve sua modificações.</p>
<p>Adicione sua modificações ao stash e logo após efetive sua modificação</p>
<b>Comando para adicionar a stash: <pre>git add .</pre></b>
<b>Comando para efetivar a modificação: <pre>git commit -m "Eu adicionei meu nome ao arquivo participantes.md"</pre></b>
<p>Logo após envie para o repositorio remoto origin(https://github.com/Didimoykds/Git-Exercise.git)</p>
<b>Comando para ver em qual branch você está: <pre>git status</pre></b>
<b>Comando para enviar as modificações para o repositorio: <pre>git push origin nome-branch</pre></b>
<p>Agora atualize a página e provavelmente o github irá lhe mostrar que é possivel realizar uma pull request para a branch master, faça a PR e então vou avaliar e mergear.</p>

<b>A pratica não teve como intenção, explicar como o git funciona ou até mesmo todos os comandos, o exericicio só teve como objetivo, dar um 'primeiro contato' com a ferramenta.</b>





