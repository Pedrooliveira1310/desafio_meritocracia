📄 Sistema de Reajuste Salarial – TechZone
📌 Descrição

Este projeto consiste em um sistema simples desenvolvido com HTML, CSS e JavaScript que calcula o reajuste salarial de um funcionário com base no cargo ocupado e em seu histórico de faltas e atrasos.

O sistema permite que o usuário insira seus dados e, ao clicar em um botão, receba uma mensagem informando se terá direito ao aumento salarial ou não.

🎯 Objetivo

O objetivo da atividade é praticar:

Manipulação do DOM com JavaScript

Uso de estruturas condicionais (if e else if)

Conversão de valores numéricos

Cálculos matemáticos

Uso de innerHTML

Estilização com CSS

🛠️ Tecnologias Utilizadas

HTML5 → Estrutura da página

CSS3 → Estilização (tema estilo terminal/hacker)

JavaScript → Lógica do sistema e cálculo do reajuste

📋 Funcionalidades

O sistema solicita:

✅ Nome do funcionário

✅ Salário atual

✅ Cargo

✅ Número de faltas

✅ Número de atrasos

📊 Regras de Reajuste
Cargo	Percentual de Aumento
Aprendiz	0%
Analista de TI	10%
Gerente de TI	15%
Diretor de TI	20%
📌 Condição para receber o aumento

O funcionário só recebe o reajuste se:

Não tiver faltas (faltas === 0)

Não tiver atrasos (atrasos === 0)

Caso contrário, o sistema informa que ele não tem direito ao reajuste.

🧠 Lógica do Funcionamento

O usuário preenche os campos.

Ao clicar em "Gerar mensagem", a função gerarMensagem() é executada.

O sistema:

Captura os valores digitados.

Define a porcentagem de aumento conforme o cargo.

Calcula o novo salário.

Verifica se há faltas ou atrasos.

Exibe a mensagem correspondente na tela.

💻 Como Executar

Copie o código.

Cole em um arquivo com extensão .html (exemplo: index.html).

Abra o arquivo no navegador.

Preencha os dados e teste o sistema.

🎨 Interface

O layout foi desenvolvido com:

Fundo preto

Texto verde neon

Fonte estilo terminal (Courier New)

Criando um visual inspirado em sistemas hackers/terminal.

🚀 Possíveis Melhorias

Validação para impedir campos vazios

Exibir o valor do aumento separadamente

Formatar o salário no padrão brasileiro

Melhorar responsividade

Separar HTML, CSS e JS em arquivos diferentes

👨‍💻 Autor

Pedro de Oliveira.
