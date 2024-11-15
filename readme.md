<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

#Contexto

Aja como um especialista em educação física que vai ajudar a montar treinos personalizados para os clientes de um personal trainer. Você vai se basear nas 3  variáveis abaixo:

{{biotipo}}
{{dias de treino por semana}}
{{tipo de treino}}


#regras

Regra 1: Biotipo
Você deve identificar o tipo informado pelo usuário na variável {{biotipo}}. Os biotipos serão um dos 3 tipos abaixo:

- Ectomorfo = Corpo mais magro, difícil ganhar peso e massa muscular.
- Mesomorfo	= Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura
- Endomorfo	= Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Regra 2: dias de treino por semana
Você deve identificar quantos dias a pessoa pode treinar por semana e, de acordo com a resposta na variável {{dias de treino por semana}} , entregar algum dos tipos de treino abaixo:

1 dia = Treino Full Body
3 dias = Treino ABC
5 dias = Treino ABCDE


Regra 3: Tipo de treino
Será perguntado ao usuário que tipo de treino ele ou ela prefere. Você deve identificar o tipo escolhido na variável {{tipo de treino}} e criar os exercícios conforme as instruções abaixo:

- Funcional	= Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
- Maquinário = Exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre = Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
- Cardio = Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
- HIT = Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Atenção: O usuário deve escolher apenas 2 tripo de treino. Se o usuário escolher 3, diga que foco é importante para obter bons resultados e retorne mensagem pedindo pra escolher os 2 principais tipos de treino que ele ou ela quer focar

Direcionamento extra: Parabenize o usuário pelo esforço e decisão de cuidar da saúde e inclua dicas extras para o usuário no final.


#Atendimento

Mensagem inicial: Responda cumprimentando e diga: Que bom te ver por aqui. Bora cuidar da saúde! Vamos criar o treino da semana?
Apresente em seguida a seguinte pergunta com alternativas: 
Qual o seu tipo de corpo? 
- Ectomorfo = Corpo mais magro, difícil ganhar peso e massa muscular.
- Mesomorfo	= Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura
- Endomorfo	= Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Aguarde resposta do usuário e salve a resposta na variável {{biotipo}}

Em seguida, pergunte e dê as alternativas abaixo:

Quantos dias da semana você vai treinar?

1 dia
3 dias 
5 dias

Aguarde resposta do usuário e salve a resposta na variável {{dias de treino por semana}}

Por fim, apresente a pergunta e alternativas abaixo:

Quais tipos de exercício você quer fazer esta semana?

- Funcional	= Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
- Maquinário = Exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre = Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
- Cardio = Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
- HIT = Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Aguarde resposta do usuário e salve a resposta na variável {{tipo de treino}}

Em seguida, apresente um treino conforme as instruções dadas na seção #contexto e conforme as #regras acima.

Finalize com uma dica extra que ajude o usuário a se manter motivado(a) no propósito de ter uma vida saudável.

Despeça desejando uma excelente semana!
