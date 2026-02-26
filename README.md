# 🎸 Red Hot Chili Peppers - Fan Site

Bem-vindo ao repositório do projeto **RHCP Fan Page**! Este é um site responsivo e dinâmico dedicado a uma das maiores bandas de rock do mundo. O projeto foi desenvolvido para consolidar conhecimentos em design responsivo, manipulação de componentes de framework e estilização avançada com pré-processadores.

## 📌 Sobre o Projeto

O site oferece uma interface moderna onde os fãs podem explorar:

* **História e Introdução:** Um breve resumo sobre a trajetória da banda.
* **Integrantes:** Um carrossel interativo apresentando Anthony Kiedis, Flea, Chad Smith e John Frusciante.
* **Shows Icônicos:** Uma seção dedicada a apresentações históricas, como o Rock in Rio 2001.
* **Discografia e Links Oficiais:** Navegação facilitada para as principais plataformas de streaming e site oficial.

---

## 🚀 Tecnologias Utilizadas

Para este projeto, foram aplicadas tecnologias que garantem performance, organização de código e responsividade:

### 📑 HTML5

A base estrutural do site foi construída com HTML semântico, garantindo acessibilidade e uma boa indexação por motores de busca (SEO).

### 🎨 SCSS (Sass)

A estilização foi feita utilizando **SCSS**, permitindo uma manutenção muito mais eficiente do CSS através de:

* **Variáveis:** Para gerenciar cores (como o vermelho característico da banda) e fontes.
* **Aninhamento (Nesting):** Facilitando a leitura da hierarquia dos seletores.
* **Mixins:** Para reaproveitamento de blocos de código.

### ⚡ Bootstrap 5.3

Utilizado para acelerar o desenvolvimento do layout responsivo e componentes complexos:

* **Grid System:** Para organizar as seções de forma fluida em qualquer tamanho de tela.
* **Navbar:** Menu de navegação responsivo com dropdown.
* **Carousel:** Implementado nas seções de "Integrantes" e "Shows" para uma navegação visual rica.

### 📜 JavaScript

O JavaScript foi utilizado principalmente para a lógica de interatividade dos componentes do Bootstrap (como o funcionamento dos carrosséis e o menu hambúrguer no mobile).

---

## 🖼️ Demonstração Visual

### Interface Principal

### Carrossel de Integrantes

---

## 📂 Estrutura de Pastas

```text
/
├── index.html          # Página principal
├── discografia.html    # Página de álbuns
├── CSS/
│   ├── style.css       # CSS compilado
│   └── style.scss      # Código fonte Sass
├── imagens/            # Assets de imagem e ícones (SVG/PNG)
└── JS/                 # Scripts personalizados (se houver)

```

---

## 🛠️ Como rodar o projeto

1. **Clone o repositório:**
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git

```


2. **Abra o arquivo `index.html**` diretamente no seu navegador ou utilize a extensão **Live Server** no VS Code para visualizar as alterações em tempo real.
3. **Para modificar estilos:** Certifique-se de ter o Sass instalado para compilar o arquivo `.scss` para `.css`.
```bash
sass --watch CSS/style.scss CSS/style.css

```



---

## 📝 Licença

Este projeto foi desenvolvido para fins de estudo e prática. Sinta-se à vontade para usar como base para os seus próprios projetos de fã!

---

**Desenvolvido com 🤘 por Matheus Siqueira**
