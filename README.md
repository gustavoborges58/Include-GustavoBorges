# Include-GustavoBorges

**Sobre o código DHT**

* O código, submetido pela primeira vez na atividade recolhida e corrigida no dia 07/05, utiliza da biblioteca DHT.h - comum aos sensores da família DHT - para realizar a obtenção da informação de temperatura ambiente;
* Como mencionado na atividade citada acima, as informações de temperatura e umidade são enviadas em um único barramento para a porta escolhida do Arduino. Logo, ao definir o pino utilizado através do parâmetro DHTPIN, é possível utilizar os comandos inerentes à biblioteca para a extração de informações;
* No caso do código em questão, utilizamos a função dht.readTemperatura() para armazenar a informação de temperatura já convertida em °C em uma variável real (aqui sendo utilizada como um real de 64 bits) chamada temp;
* A depender dos valores de temp, dentro do range de funcionamento do DHT11, é possível estabelecer uma rotina de acionamento de componentes que sejam interessantes para a manutenção da temperatura do sistema;

**Comandos utilizados em terminal**

* Para realizar as etapas seguintes, correspondentes ao envio do arquivo para o repositório utilizando o terminal, antes de mais nada, fez-se necessária a clonagem do repositório na máquina em questão. Para tal, fora utilizado o comando *$ git clone* e a especificação do caminho do repositório a ser clonado, utilizando a seguinte sintaxe:

> $ git clone https://github.com/gustavoborges58/Include-GustavoBorges.git

* Feito isso, foi possível clonar o repositório na forma de uma pasta dentro do PC;
* Para adicionar arquivos e alterações ao repositório no GitHub, antes de mais nada, fez-se necessário salvar o arquivo dentro do diretório clonado. No caso, criou-se o arquivo *DHT.txt*, contendo o código a ser upado para o Arduino;
* Em seguida, fora utilizado o comando *$ git add .* para iniciar o envio;
* Após enviar o comando, fora utilizado o *$ git commit -m* para adicionar uma descrição ao mesmo, em que *-m* teria como valor uma mensagem correspondente à descrição citada. A sintaxe deste comando seria a seguinte, na execução prática:

> $ git commit -m "Programacao base do sensor de temperatura e umidade*

* Após realizar as devidas alterações, fez-se necessário utilizar o *$ git push* para enviar o arquivo com todas as suas especificações e descrição para o repositório no GitHub. Para tal, tornou-se necessário especificar o destino do arquivo em questão, utilizando, afinal, a seguinte linha de comando:

> $ git push --set-upstream origin master

* Após a realização destas etapas, foi possível enviar todas as alterações no diretório para o repositório online.
