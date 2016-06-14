# Cálculo do Índice de Qualidade da Água

A aplicação para o cálculo do IQA foi desenvolvida utilizando o sistema operacional Ubuntu, para instalar o GTK no Ubuntu basta executar o comando <pre>sudo apt-get install libgtk-3-dev</pre></br>
A pasta raiz do projeto contém 4 arquivos, sendo o iqa.c o fonte</br>
Para compilar o programa o usuário deve executar o seguinte comando no terminal </br> <pre>gcc iqa.c \`pkg-config --libs gtk+-3.0\` \`pkg-config --cflags gtk+-3.0\` -o iqa  -lm</pre></br>
Também é possível compilar o programa utilizando o comando <pre>make</pre></br>
É possível executar o programa executando o comando: </br>
<pre>./iqa</pre>
