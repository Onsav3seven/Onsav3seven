- 👋 Hi, I’m @Onsav3seven
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
<!---
Onsav3seven/Onsav3seven is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!-- A pergunta do questionário -->

<p>Aceita namorar comigo?</p>

<!-- Botões para responder sim ou não -->

<button onclick="showMessage('Sim')">Sim</button>

<button onclick="showMessage('Não')">Não</button>

<!-- Um elemento para exibir a mensagem de resposta -->

<p id="response"></p>

<!-- Uma função JavaScript para exibir a mensagem de resposta -->

<script>

  function showMessage(response) {

    // Obtém o elemento para exibir a mensagem

    var messageElement = document.getElementById("response");

    

    // Verifica se a resposta foi "Sim" ou "Não"

    if (response === "Sim") {

      // Exibe uma mensagem diferente dependendo da resposta

      messageElement.innerHTML = "Eu estava certo o tempo todo e sempre quis ter você na minha vida!";

    } else {

      messageElement.innerHTML = "Lamento que você tenha escolhido não. Talvez no futuro as coisas mudem.";

    }

  }

</script>

