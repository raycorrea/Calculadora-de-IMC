💡 Calculadora de IMC com Dicas de Saúde — Projeto Vitta
Este é um projeto em Python desenvolvido como uma aplicação interativa de terminal que calcula o IMC (Índice de Massa Corporal) do usuário, classifica o resultado com base nas diretrizes da OMS e oferece dicas de saúde personalizadas de acordo com a classificação obtida.

🚀 Funcionalidades
Solicita dados do usuário: nome, idade, peso e altura.

Calcula automaticamente o IMC usando a fórmula: peso / (altura²).

Exibe a classificação do IMC com cores diferenciadas no terminal (peso normal, sobrepeso, obesidade etc.).

Fornece dicas de saúde personalizadas com base na classificação do IMC.

Alerta o usuário sobre a importância de procurar um profissional de saúde.

Possui opção de repetir o processo para múltiplas pessoas.

🎯 Tecnologias utilizadas
Python 3

Biblioteca padrão (time)

ANSI escape codes para colorização no terminal

📌 Exemplo de Execução

+--------------------------------------------------------------------------------+
|                                 Olá, boas-vindas!                              |
+--------------------------------------------------------------------------------+
| Qual o seu nome? Rayan
| Qual a sua idade? 28
| Qual o seu peso? 64
| Qual a sua altura? (ex: 1.70) 1.74
+--------------------------------------------------------------------------------+

+--------------------------------------------------------------------------------+
|                                 Olá, Rayan!                                    |
|                          Analisando seus dados...                              |
+--------------------------------------------------------------------------------+
                             Seu IMC é: 21.14
Classificação: Peso normal
Vamos ver algumas boas práticas saudáveis para a sua classificação de IMC.
+--------------------------------------------------------------------------------+

+--------------------------------------------------------------------------------+
|                                Dicas de Saúde                                  |
+--------------------------------------------------------------------------------+
| Alimentação: Mantenha uma dieta equilibrada.                                   |
| Moderação: Evite excessos e consuma fibras, frutas e vegetais.                 |
| Exercícios: Pratique atividades físicas regularmente.                          |
| Sono e bem-estar: Priorize boas noites de sono e controle o estresse.         |
+--------------------------------------------------------------------------------+

🧠 Desafios enfrentados
Durante o desenvolvimento deste projeto, alguns pontos exigiram mais atenção:

Formatação do Terminal: Utilizar os códigos ANSI para dar cor e formatar visualmente as mensagens foi um desafio interessante. Garantir que tudo se mantivesse alinhado e legível exigiu testes manuais e ajustes cuidadosos no layout.

Validação de Dados: Ainda que o programa funcione bem, ele não lida com exceções. Um desafio não resolvido foi o tratamento de entradas inválidas (como letras ao invés de números), o que poderia causar erros durante a execução.

Modularização: A lógica do código está toda centralizada em um único bloco. Foi um aprendizado entender como isso pode ser organizado de forma mais limpa, usando funções ou classes para facilitar manutenções futuras.

Mensagens e Interação: Pensar nas mensagens para o usuário e como deixar a experiência acolhedora, didática e responsável (reforçando a importância de um profissional de saúde) foi um ponto importante do projeto.

📈 Melhorias futuras

Implementar tratamento de exceções para entradas inválidas.

Refatorar o código em funções para maior organização.

Criar uma interface gráfica simples com Tkinter ou uma versão web com Flask.

Adicionar suporte a banco de dados para armazenar histórico de IMCs.

🤝 Contribuição
Sinta-se à vontade para sugerir melhorias, abrir issues ou contribuir com o projeto! Qualquer feedback é bem-vindo :)

🧑‍⚕️ Aviso importante
Esta aplicação é educativa e informativa, não substitui orientação profissional médica ou nutricional. Consulte sempre especialistas para diagnóstico e tratamento adequados.
