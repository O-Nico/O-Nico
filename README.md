<!-- Insira este código dentro do seu README.md -->

<h1 align="center">Olá, sou o Nicolas!</h1>
<h2 align="center">Estudante de Engenharia da Computação</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=O-Nico&show_icons=true&theme=highcontrast" alt="Estatísticas do GitHub de Nicolas">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=O-Nico&layout=compact&theme=highcontrast" alt="Linguagens mais usadas">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nicolas-barreto-50b010209/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/O-Nico">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="mailto:nicolas.barreto.barreto@hotmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=hotmail&logoColor=white" alt="Email">
  </a>
</p>

<p align="center">
  <strong>Principais Tecnologias</strong>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <!-- Adicione mais tecnologias conforme necessário -->
</p>



<h2>🎮 Jogo de Adivinhação</h2>
<p>Tente adivinhar o número que estou pensando entre 1 e 100!</p>

<input type="number" id="guessInput" placeholder="Digite seu palpite" />
<button onclick="checkGuess()">Adivinhar</button>

<p id="resultMessage"></p>

<script>
  const randomNumber = Math.floor(Math.random() * 100) + 1;
  let attempts = 0;

  function checkGuess() {
    const userGuess = parseInt(document.getElementById('guessInput').value);
    attempts++;

    if (userGuess === randomNumber) {
      document.getElementById('resultMessage').innerText = 
        `Parabéns! Você acertou o número ${randomNumber} em ${attempts} tentativas.`;
    } else if (userGuess < randomNumber) {
      document.getElementById('resultMessage').innerText = 
        'Tente um número maior!';
    } else if (userGuess > randomNumber) {
      document.getElementById('resultMessage').innerText = 
        'Tente um número menor!';
    }
  }
</script>



<p align="center">
 
<p align="center">
  <strong>Meu portfólio:</strong> <a href="https://github.com/O-Nico">Visite aqui</a>
</p>
