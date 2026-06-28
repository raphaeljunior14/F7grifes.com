# Manto F.C Store – Loja Online

Este repositório contém o site institucional da **Manto F.C Store**, uma loja online com foco em produtos para torcedores — exibindo camisas, acessórios e mais em um layout moderno e responsivo.

🔗 **Acesse o site ao vivo:**  
https://luizrogeriopx.github.io/MantoFCstore/

---

## ⚽ Sobre o projeto

O **Manto F.C Store** é um site de vitrine para uma loja de artigos esportivos voltada a torcedores de futebol. A página apresenta:

- Navegação simples e objetiva  
- Carrinho de compras visual  
- Opções de entrega e retirada  
- Informações de suporte e contato  
- Visual leve e acessível  

O layout é pensado para ser claro e funcional para todos os visitantes.

---

## 🛠 Tecnologias utilizadas

Este projeto foi construído com as seguintes tecnologias:

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
</p>

---

## 🗂 Estrutura do projeto

MantoFCstore/ <br/>
├─ index.html <br/>
├─ css/ <br/>
│ └─ style.css <br/>
├─ js/ <br/>
│ └─ script.js <br/>
└─ imagens/ <br/>

---


## 👤 Autor Projeto Original
Ronald Andrade
GitHub: https://github.com/ronaldandrade25/ra-moda-masculina

## 👤 Editor Projeto Manto F.C Store
Luiz Rogério
GitHub: https://github.com/luizrogeriopx
Projeto online: https://luizrogeriopx.github.io/MantoFCstore/


---

## 💻 Alterações feitas no projeto

Fiz uma evolução significativa no código original para transformar a loja em uma plataforma mais robusta e focada em conversão. Aqui estão os pilares das alterações:"

1. Evolução da Estrutura de Dados (Data Schema)
De Imagem Única para Galeria: O objeto de produto foi alterado de imagem: "url" para imagens: ["url1", "url2", ...]. Isso permitiu a implementação de um sistema de galeria dinâmica por card.

Atributo de Seleção: Adicionei a obrigatoriedade do atributo tamanho no objeto enviado ao carrinho.

2. Engenharia de UX e Interface (UI)
Navegação de Miniaturas: Criei um componente de tabs dentro de cada card. Ao clicar nas miniaturas, a imagem principal é trocada com uma transição de opacidade (fade-in/out) via JavaScript, sem recarregar a página.

Seletor de Tamanho Obrigatório: Implementei um seletor (P ao EXG) com validação de estado. Se o usuário tentar comprar sem selecionar, o sistema dispara um Modal de Alerta Customizado (substituindo o alert nativo) e uma animação de shake (trepidação) nos botões.

3. Refatoração do Carrinho (Sidebar)
Box Model e Respiro: Redefini o sistema de paddings e margins. Agora, o carrinho utiliza um distanciamento fixo (25px a 30px), garantindo que nenhum elemento toque as bordas, seguindo padrões de design Mobile-First.

Estilização de Componentes: O botão de fechar foi transformado em um elemento circular dinâmico, e os itens do carrinho agora são renderizados como "cards" individuais com fundos contrastantes para melhor leitura.

4. Otimização de Animações
Web Animations API (Fly Effect): Substitui transições CSS simples por uma animação via JavaScript utilizando coordenadas dinâmicas (getBoundingClientRect). O produto agora "voa" em uma parábola perfeita do card até o ícone do carrinho, independentemente da rolagem da página.

Feedback Visual: Adicionei a classe .bump que faz o ícone do carrinho pulsar no momento exato em que o "voo" termina.

5. SEO e Rodapé (Footer)
Semântica: Adicionei as tags <meta name="description"> e reestruturei o rodapé para utilizar uma seção <footer> semântica, com grid responsivo e paleta de cores Navy/Black Premium.

---

## 📄 Licença

Este projeto está sob a licença MIT — livre para estudo, adaptação e uso pessoal.


---


## 💻 Como testar o projeto

1. Faça o clone do repositório:
```bash
git clone https://github.com/luizrogeriopx/MantoFCstore.git


