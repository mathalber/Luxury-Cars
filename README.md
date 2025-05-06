const fs = require('fs');

const novoConteudo = `
# Projeto Web Básico

Este é um projeto front-end com HTML, CSS e JavaScript.

## 📁 Estrutura

- \`index.html\`
- \`style.css\`
- \`script.js\`

## 🔧 Como usar

Abra o arquivo \`index.html\` no navegador.

## 🧑‍💻 Autor

[Matheus Alberto](https://github.com/mathalber)
`;

fs.writeFile('README.md', novoConteudo, (err) => {
  if (err) throw err;
  console.log('README.md atualizado com sucesso!');
});