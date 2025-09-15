---
weight: 200
weight: 1
title: "Resumo: Programação Orientada a Objetos"
icon: "folder"
date: "2025-09-15T00:34:57+01:00"
lastmod: "2025-09-15T00:34:57+01:00"
draft: false
ai_generated: true
ai_warning: "Conteúdo gerado com inteligência artificial. Pode conter imprecisões ou erros."
---

> ⚠️ **Aviso:** Este conteúdo foi gerado com ajuda de Inteligência Artificial (IA) e pode conter erros ou imprecisões.  
> Sempre verifique a informação antes de utilizar.

---

🎥 [Vídeo no Spotify](https://open.spotify.com/episode/5lxtq43Ko0gbhK4Lyk8zZ2) — gerado por IA com resumos do conteudo.  
Útil para uma revisão rápida dos temas tratados na disciplina.

<iframe src="https://open.spotify.com/embed/episode/5eHMwAlKNvebcWIMPD63na" width="100%" height="152" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

# 1. Evolução da Programação

Historicamente, a programação evoluiu de formas mais simples e diretas para abordagens mais complexas e organizadas, visando melhor manutenção e reusabilidade do código.

- **Baixo Nível**:  
  Linguagens que eram "formas bem simples de falar com o computador", sendo específicas para cada tipo de máquina, o que impedia a portabilidade do código.

- **Programação Linear**:  
  Caracterizada pela execução sequencial de instruções, "do início ao fim, sem desvios ou repetições."  
  Adequada para "programas simples."

- **Programação Estruturada**:  
  Introduziu a organização do código em blocos, utilizando estruturas de controle como `if`, `while` e `for`, facilitando a leitura e manutenção.

- **Programação Modular**:  
  Foca na divisão do programa em "módulos ou funções independentes", promovendo reutilização e organização do código.

- **Programação Orientada a Objetos (POO)**:  
  Baseia-se em "objetos que combinam dados e comportamentos", usando conceitos como classes, herança e encapsulamento.

---

# 2. O Problema da Dispersão de Responsabilidades

Antes da POO, a validação e outras responsabilidades eram frequentemente "espalhadas por todo o seu código". Isso gerava dificuldades quando era necessário modificar uma validação, pois "os outros programadores nem precisavam ficar sabendo disso" e tornava complexo "concentrar essa responsabilidade em um lugar só".

A POO busca resolver essa questão, agrupando dados e seus comportamentos relacionados, promovendo um código mais coeso e de fácil manutenção.

---

# 3. O que é um Objeto?

Na POO, um objeto é a unidade fundamental e pode ser entendido como:

> "Um objeto é uma coisa material ou abstrata que pode ser percebida pelos sentidos e descrita por meio de duas características: comportamentos e estado atual."

Todo objeto deriva de uma **Classe**, que funciona como um "molde usado para gerar o objeto."

## Componentes dos Objetos

- **Características (Atributos)**: "Que coisas eu tenho?"  
  Exemplo: Para uma caneta, atributos poderiam ser `Modelo`, `Cor`, `Ponta`, `Carga`, `Tampada`.

- **Comportamentos (Métodos)**: "Que coisas eu faço?"  
  Exemplo: Para uma caneta, métodos poderiam ser `Escrever`, `Rabiscar`, `Pintar`, `Tampar`, `Destampar`.

- **Estado Atual (Estado)**: "Como eu estou agora?"  
  Refere-se aos valores atuais dos atributos, como `carga: 90%` e `tampada: Sim`.

A **instanciação** é o processo de criar um objeto a partir de uma classe.  
Exemplo: `c1 = nova Caneta()`, onde `c1` é uma instância da classe `Caneta`. Objetos são acessados por referências na memória.

---

# 4. Classe vs. Objeto

- **Classe**: Define os atributos e métodos comuns que serão compartilhados por um objeto. É a **blueprint**.
- **Objeto**: É a instância de uma classe. É a **materialização do molde**.

---

# 5. Abstração

A abstração é um pilar da POO e é definida como:

> "Abstração é o processo de simplificar a complexidade do mundo real ao modelar objetos, focando apenas nos aspectos essenciais e ignorando os detalhes irrelevantes para o contexto atual."

Ao modelar objetos, não é necessário listar "todos" os atributos e métodos possíveis.  
O objetivo é representar a entidade de forma "simples, clara e funcional, capturando apenas o necessário para o problema que se quer resolver."

Isso significa que, como em um desenho que "abstrai características não essenciais para destacar a estrutura geral", a POO permite modelar entidades do mundo real focando no que é relevante para o problema em questão.
