<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>

<body>

  <h1 align="center">Reconhecimento de Voz com Nalu</h1>

  <p align="center">
  </p>

  <p align="center">
    <em>Este é um projeto simples em Python que utiliza reconhecimento de fala para executar comandos específicos.</em>
  </p>

  <h2>Descrição</h2>

  <p>
    A aplicação é capaz de realizar tarefas como informar as horas, buscar informações na Wikipedia e reproduzir músicas no YouTube com base nos comandos do usuário.
  </p>

  <h2>Pré-requisitos</h2>

  <p>
    Antes de executar o programa, certifique-se de ter as seguintes dependências instaladas:
  </p>

  <ul>
    <li>SpeechRecognition</li>
    <li>pyttsx3</li>
    <li>wikipedia-api</li>
    <li>pywhatkit</li>
  </ul>

  <p>
    Você pode instalar as dependências executando o seguinte comando:
  </p>

  <pre>
    <code>
      pip install -r requirements.txt
    </code>
  </pre>

  <p>
    Além disso, verifique se o seu sistema possui o Pyaudio instalado para lidar com a entrada de áudio do microfone.
  </p>

  <h2>Como Executar o Programa</h2>

  <ol>
    <li>
      <strong>Clone o Repositório:</strong>
      <pre><code>git clone https://github.com/seu-usuario/voice-recognition-nalu.git</code></pre>
    </li>
    <li>
      <strong>Navegue até o Diretório do Projeto:</strong>
      <pre><code>cd voice-recognition-nalu</code></pre>
    </li>
    <li>
      <strong>Execute o Programa:</strong>
      <pre><code>python nome_do_arquivo.py</code></pre>
      Substitua <code>nome_do_arquivo.py</code> pelo nome do arquivo que contém o código fornecido.
    </li>
  </ol>

  <h2>Comandos Suportados</h2>

  <ol>
    <li>
      <strong>Horas:</strong>
      <p>O comando "horas" informará as horas atuais.</p>
    </li>
    <li>
      <strong>Pesquisa na Wikipedia:</strong>
      <p>Utilize o comando "procure por" seguido do termo desejado para buscar informações na Wikipedia.</p>
    </li>
    <li>
      <strong>Reprodução de Música no YouTube:</strong>
      <p>O comando "toque" seguido do nome da música iniciará a reprodução da música correspondente no YouTube.</p>
    </li>
  </ol>

  <h2>Notas Adicionais</h2>

  <ul>
    <li>
      <p>Se o programa detectar a palavra-chave "nalu", ela será removida do comando para evitar repetições.</p>
    </li>
    <li>
      <p>Certifique-se de que o microfone está funcionando corretamente antes de executar o programa, pois problemas de áudio podem afetar o reconhecimento de fala.</p>
    </li>
  </ul>

  <h2>Contribuições</h2>

  <p>
    Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.
  </p>

  <h2>Licença</h2>

  <p>
    Este projeto está licenciado sob a MIT License.
  </p>

</body>

</html>
