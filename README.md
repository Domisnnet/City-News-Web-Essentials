![GitHub repo size](https://img.shields.io/github/repo-size/Domisnnet/City-News-Web-Essentials?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/Domisnnet/City-News-Web-Essentials?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Domisnnet/City-News-Web-Essentials?style=for-the-badge)

<h2 id="sobre-o-projeto">1. 📰 Notícias Cidade: Portal de Informação 📰</h2>

![Status do Deploy](https://img.shields.io/badge/Status-Online-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML%20%7C%20CSS-blueviolet)
[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/City-News-Web-Essentials/blob/main/LICENSE)

![Notícias Cidade](src/imagens/noticias-cidade.png)

Bem-vindo ao **Notícias Cidade**! Este projeto simula um portal de notícias completo e dinâmico. A aplicação foca na organização de múltiplas editorias (Brasil, Internacional, Economia, Saúde, etc.) utilizando um layout de múltiplas colunas. É um estudo avançado de posicionamento e containers, ideal para entender como portais de grande conteúdo estruturam suas informações para o usuário final.

---

## 📚 Tabela de Conteúdo

| 📰 O Projeto | 🛠️ Técnico | 🤝 Comunidade |
| :---: | :---: | :---: |
| [![1. Sobre](https://img.shields.io/badge/1%20-%20Sobre-4CAF50)](#sobre-o-projeto) | [![5. Destaques](https://img.shields.io/badge/5%20-%20Destaques-607D8B)](#destaques-tecnicos) | [![9. Código](https://img.shields.io/badge/9%20-%20Código-795548)](#codigo-fonte) |
| [![2. Techs](https://img.shields.io/badge/2%20-%20Techs-2196F3)](#tecnologias-utilizadas) | [![6. Instalação](https://img.shields.io/badge/6%20-%20Instala%C3%A7%C3%A3o-009688)](#instalacao) | [![10. Créditos](https://img.shields.io/badge/10%20-%20Créditos-607D8B)](#créditos) |
| [![3. Acessar](https://img.shields.io/badge/3%20-%20Acessar-FF9800)](#como-acessar) | [![7. Contribuir](https://img.shields.io/badge/7%20-%20Contribuir-3F51B5)](#como-contribuir) | [![11. Licença](https://img.shields.io/badge/11%20-%20Licença-E91E63)](#licenca) |
| [![4. Funções](https://img.shields.io/badge/4%20-%20Funções-9C27B0)](#funcionalidades) | [![8. FAQ](https://img.shields.io/badge/8%20-%20FAQ-FFC107)](#faq) | [![12. Perfil](https://img.shields.io/badge/12%20-%20Perfil-212121)](#perfil-do-github) |

---

<h2 id="tecnologias-utilizadas">2. ⚙️ Tecnologias Utilizadas</h2>

| Camada | Tecnologias | Descrição |
| :--- | :--- | :--- |
| **Estrutura** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Organização semântica por IDs para controle preciso de layout. |
| **Estilo** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Uso intensivo de floats, clears e estilização de listas. |
| **UI/UX** | ![Design](https://img.shields.io/badge/Visual-Editorial-orange?style=flat-square) | Paleta de cores e tipografia baseada em jornais digitais. |

---

<h2 id="como-acessar">3. 🚀 Como Acessar</h2>

Acesse o portal e navegue pelas notícias em tempo real:

<div align="left">
  <a href="https://domisnnet.github.io/City-News-Web-Essentials/" target="_blank">
    <img alt="Botão Acessar" src="src/imagens/botão.webp" height="70" width="70" />
  </a>
</div>

---

<h2 id="funcionalidades">4. 🧩 Funcionalidades Principais</h2>

O portal oferece uma experiência completa de leitura e interação:

| Funcionalidade | Descrição |
| :--- | :--- |
| 🏠 **Home de Destaques** | Área principal com a notícia mais importante do momento. |
| 📑 **Categorias Variadas** | Menu de navegação que segmenta o conteúdo por temas. |
| 🎙️ **Painel de Entrevistas** | Seção dedicada a conversas com especialistas e personalidades. |
| 📬 **Newsletter (News)** | Formulário de cadastro para recebimento de notícias por e-mail. |
| 🖼️ **Miniaturas de Notícias** | Listas visuais com ícones que facilitam a leitura rápida. |

---

<h2 id="destaques-tecnicos">5. 💻 Destaques Técnicos</h2>

A engenharia deste projeto foca no equilíbrio de colunas:

### 📐 Layout de Três Colunas
O desafio técnico consistiu em equilibrar as divs `#primario`, `#secundario` e `#lateral` para que coexistissem lado a lado, utilizando propriedades de largura percentual e `float: left`.

### 🔄 Limpeza de Fluxo (`Clear`)
Implementação de `clear: both` no rodapé e em containers específicos para garantir que o layout não quebre quando o conteúdo de uma coluna for maior que o da outra.

---

<h2 id="instalacao">6. 🚀 Instalação e Configuração Local</h2>

```bash
# Clonar o repositório
git clone https://github.com/Domisnnet/City-News-Web-Essentials.git(https://github.com/Domisnnet/City-News-Web-Essentials.git)

# Acessar a pasta
cd City-News-Web-Essentials
```

---

<h2 id="como-contribuir">7. 🤝 Como Contribuir</h2>

Siga os passos abaixo para adicionar novas editorias ou melhorias:

| Fase | Ação | Link / Comando |
| :---: | :--- | :--- |
| **01** | **Fork** | [![Fork](https://img.shields.io/badge/-Fazer%20Fork-blue?style=flat-square&logo=github)](https://github.com/Domisnnet/City-News-Web-Essentials/fork) |
| **02** | **Branch** | `git checkout -b feature/NovaEditoria` |
| **03** | **Commit** | `git commit -m 'feat: adição da página de tecnologia'` |
| **04** | **Push** | `git push origin feature/NovaEditoria` |
| **05** | **PR** | [![Abrir PR](https://img.shields.io/badge/-Abrir%20PR-green?style=flat-square&logo=git)](https://github.com/Domisnnet/City-News-Web-Essentials/compare)

### 🐛 Encontrou um problema?
Se algo não estiver funcionando como esperado, não hesite em abrir um chamado:

[![Issues Abertas](https://img.shields.io/github/issues/Domisnnet/City--News--Web--Essentials?style=flat-square&color=red&logo=github)](https://github.com/Domisnnet/City-News-Web-Essentials/issues)
[![Report Bug](https://img.shields.io/badge/Reportar-Erro-critical?style=flat-square&logo=github)](https://github.com/Domisnnet/City-News-Web-Essentials/issues/new)

---

<h2 id="faq">8. 🧠 Perguntas Frequentes</h2>

<details>
<summary><strong>Por que os links das categorias não carregam ❓</strong></summary>
<p>🔗 <strong>Resposta:</strong> Este é um template estrutural. As páginas individuais (saude.html, ciencia.html, etc.) devem ser criadas seguindo o modelo da <code>index.html</code>.</p>
</details>

<details>
<summary><strong>O formulário de Newsletter envia e-mails ❓</strong></summary>
<p>📧 <strong>Resposta:</strong> Não. É uma interface de front-end. Para funcionar, precisaria de uma integração com serviços como Mailchimp ou um backend em PHP/Node.js.</p>
</details>

<details>
<summary><strong>Como alterar a cor do topo ❓</strong></summary>
<p>🎨 <strong>Resposta:</strong> Basta editar o seletor <code>#topo</code> no arquivo <code>css/estilo.css</code> e modificar a propriedade <code>background</code>.</p>
</details>

---

<h2 id="codigo-fonte">9. 💻 Código Fonte</h2>

Analise a folha de estilo e a estruturação dos IDs:

[![Repositório](https://img.shields.io/badge/Repositório-Domisnnet%2FCity--News--Web--Essentials-1DB954?style=for-the-badge&logo=github)](https://github.com/Domisnnet/City-News-Web-Essentials)


---

<h2 id="créditos">10. 📝 Créditos & Reconhecimentos</h2>

O **Notícias Cidade** reflete as melhores práticas de layouts de portais clássicos:

| Atribuição | Responsável / Recurso | Descrição |
| :--- | :--- | :--- |
| **Dev & Arquitetura** | **DomisDev** | Estruturação de colunas e hierarquia de informação. |
| **Imagens** | **Banco de Imagens** | Fotos ilustrativas (táxi, doutor, tecnologia) para o portal. |
| **Base Teórica** | **Web Layouts** | Estudo de interfaces editoriais de alta densidade. |
| **Apoio Técnico** | **Google Gemini** | Padronização King-Domfy e refinamento documental. |

---

<h2 id="licenca">11. 📄 Licença</h2>

Este projeto está sob a [![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/City-News-Web-Essentials/blob/main/LICENSE)

---

<h2 id="perfil-do-github">12. 👨‍💻 Perfil do GitHub</h2>

<a href="https://github.com/Domisnnet"> 
  <img src="src/imagens/DomisDev.png" width="90" alt="Acessar perfil GitHub"> 
</a>
