# Logica-JS4

# <body>
  <h1>Resolução dos Desafios do Curso de Lógica de Programação 💡</h1>

  <p>Praticar a lógica de programação, incluindo conceitos como <strong>variáveis</strong>, <strong>condicionais (if-else)</strong>, <strong>loops (while)</strong> e <strong>interações com o usuário (alert, prompt)</strong>, é essencial para sua carreira de desenvolvimento de software.</p>
  <p>Esses fundamentos fornecem a base para <em>resolver problemas de forma estruturada</em>, <em>tomar decisões no código</em>, <em>criar iterações controladas</em> e <em>interagir eficazmente com os usuários</em>.</p>
  <p>Compreender esses conceitos não apenas facilita o aprendizado de novas linguagens e tecnologias, mas também capacita você a <strong>criar soluções inovadoras</strong>, <strong>depurar eficientemente</strong> e <strong>manter a qualidade</strong> ao longo do ciclo de vida do software.</p>
  <p>Portanto, investir tempo nesses princípios desde cedo é fundamental para <strong>construir uma base sólida e bem-sucedida</strong> no campo da programação.</p>


<body>

  <h1>Desafios com Interações JavaScript</h1>

  <div class="desafio">
    <h2>Desafio 1 — Alterar título da página</h2>
    <div class="enunciado">Altere dinamicamente o conteúdo da tag <code>h1</code> da página para exibir o texto "Hora do Desafio".</div>
    <pre>
document.querySelector("h1").textContent = "Hora do Desafio";
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: O título exibido no topo da página será "Hora do Desafio".</div>
  </div>

  <div class="desafio">
    <h2>Desafio 2 — Console ao clicar</h2>
    <div class="enunciado">Crie uma função que exibe no console a mensagem "O botão foi clicado" quando o botão for pressionado.</div>
    <pre>
function mostrarConsole() {
  console.log("O botão foi clicado");
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: A mensagem será registrada no console do navegador.</div>
  </div>

  <div class="desafio">
    <h2>Desafio 3 — Mostrar alerta</h2>
    <div class="enunciado">Crie uma função que exiba um alerta com a mensagem "Eu amo JS" ao clicar em um botão.</div>
    <pre>
function mostrarAlerta() {
  alert("Eu amo JS");
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: O usuário verá um alerta com a frase "Eu amo JS".</div>
  </div>

  <div class="desafio">
    <h2>Desafio 4 — Cidade lembrança</h2>
    <div class="enunciado">Crie uma função que pede o nome de uma cidade com <code>prompt</code> e exibe um alerta com a mensagem "Estive em {cidade} e lembrei de você".</div>
    <pre>
function perguntarCidade() {
  const cidade = prompt("Digite o nome de uma cidade do Brasil:");
  alert("Estive em " + cidade + " e lembrei de você.");
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: Ao digitar "Salvador", será exibido "Estive em Salvador e lembrei de você".</div>
  </div>

  <div class="desafio">
    <h2>Desafio 5 — Soma de números</h2>
    <div class="enunciado">Crie uma função que pede dois números inteiros e exibe o resultado da soma em um alerta.</div>
    <pre>
function somarNumeros() {
  const num1 = parseInt(prompt("Digite o primeiro número inteiro:"));
  const num2 = parseInt(prompt("Digite o segundo número inteiro:"));
  const resultado = num1 + num2;
  alert("O resultado da soma é: " + resultado);
}
    </pre>
    <div class="resposta">🟢 Exemplo de resposta: Ao inserir 2 e 3, o alerta exibirá "O resultado da soma é: 5".</div>
  </div>

</body>
