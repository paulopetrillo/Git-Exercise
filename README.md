<h1>Praticando Comandos Git</h1>
<h2><b>Preparatório</b></h2>
<p>Antes de tudo é necessario realizar a instalação do Git: <a href="https://git-scm.com/downloads">https://git-scm.com/downloads</a></p>
<p>Após feita a instalação abra o terminal e utilize o comando Git, caso apareça informações sobre comandos relativos ao Git a instalação foi feita com sucesso, caso contrário há de verificar, pois a instalação não foi feita corretamente.(Até onde eu sei, kkkk...)</p>
Obs. Não abordaremos fork nessa pŕatica.

<p>A primeira parte é realizar um clone deste projeto em seu computador, antes de tudo vá a uma pasta em que queira que o projeto seja clonado. (Dica: Comando `cd` lhe permite navegar entre diretorios.)</p>

<b>Comando: <pre>git clone https://github.com/Didimoykds/Git-Exercise.git</pre></b>

<p>Após o fim da transferência do projeto, ` escreva git branch ` para que você consiga ver as branchs existentes em seu projeto. Provavelmente em seu terminal mostrará somente a branch <b>Master</b>, pois é a única branch existente em seu projeto.</p>

<p>Para que você consiga clonar todas as branchs de um repositorio, você precisa executar o comando <pre> git fetch "repositorio"</pre>, como já possuimos um repositorio remoto setado na origin, que é o https://github.com/Didimoykds/Git-Exercise.git, só precisamos dar um <pre>git fetch origin</pre>. ( origin = https://github.com/Didimoykds/Git-Exercise.git )
agora escreva novamente o comando <pre>git branch</pre> e verá que seu projeto agora possui novas branchs.</p>
