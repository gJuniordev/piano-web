# 🎹 Piano Virtual

![Badge de Tecnologia: HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Badge de Tecnologia: CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Badge de Tecnologia: JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Um simulador de piano online e interativo, construído com **HTML**, **CSS** e **JavaScript** puro. Permite aos usuários tocar notas musicais tanto clicando nas teclas virtuais quanto utilizando o teclado do computador.

## ✨ Funcionalidades

* **Tocar Notas:** Reproduz o som correspondente ao clicar em uma tecla do piano ou pressionar a tecla mapeada no teclado.
* **Controle de Volume:** Possibilidade de ajustar o volume das notas tocadas através de um *slider*.
* **Visualização das Teclas:** Opção para mostrar ou ocultar os rótulos das teclas do teclado (ex: 'a', 's', 'd', etc.) no layout do piano virtual.
* **Feedback Visual:** As teclas virtuais ganham um efeito visual (`.active`) ao serem pressionadas.

## 💻 Tecnologias Utilizadas

O projeto é inteiramente construído com tecnologias *front-end* básicas:

* **HTML5:** Estruturação da interface do piano e dos controles.
* **CSS3:** Estilização moderna e responsiva da interface.
    * Uso de `linear-gradient` para o visual das teclas brancas e pretas.
    * Animação do *toggle switch* para visualização das teclas.
* **JavaScript:** Lógica de reprodução de áudio, mapeamento de eventos do teclado (`keydown`), e manipulação dos controles (volume e *toggle*).

## 🚀 Como Usar

### Pré-requisitos

Nenhum. Basta um navegador moderno (Chrome, Firefox, Edge, etc.).

### Instalação (Local)

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/gJuniordev/piano-web.git](https://github.com/gJuniordev/piano-web.git)
    cd piano-web
    ```
2.  Abra o arquivo `index.html` em seu navegador.

### Controles

| Ação | Teclas Mapeadas | Descrição |
| :--- | :--- | :--- |
| **Teclas Brancas** | `a`, `s`, `d`, `f`, `g`, `h`, `j`, `k`, `l`, `;` | Toca notas brancas. |
| **Teclas Pretas** | `w`, `e`, `t`, `y`, `u`, `o`, `p` | Toca notas pretas. |
| **Mouse** | Clicar em qualquer tecla virtual | Toca a nota correspondente. |
| **Volume** | Arrastar o *slider* de volume | Ajusta o `audio.volume` do JavaScript. |
| **Mostrar Teclas** | Clicar no *toggle switch* "Teclas" | Alterna a visibilidade dos rótulos. |

## 📁 Estrutura do Projeto
### Controles

| Ação | Teclas Mapeadas | Descrição |
| :--- | :--- | :--- |
| **Teclas Brancas** | `a`, `s`, `d`, `f`, `g`, `h`, `j`, `k`, `l`, `;` | Toca notas brancas. |
| **Teclas Pretas** | `w`, `e`, `t`, `y`, `u`, `o`, `p` | Toca notas pretas. |
| **Mouse** | Clicar em qualquer tecla virtual | Toca a nota correspondente. |
| **Volume** | Arrastar o *slider* de volume | Ajusta o `audio.volume` do JavaScript. |
| **Mostrar Teclas** | Clicar no *toggle switch* "Teclas" | Alterna a visibilidade dos rótulos. |

## 📁 Estrutura do Projeto

## 📸 Preview

<img width="911" height="519" alt="image" src="https://github.com/user-attachments/assets/819aa10d-6445-443f-8163-c9fbf619ef83" />

## 🎓 Contexto Educacional
Este projeto foi desenvolvido como parte da **Formação Web Developer** da [DIO.me](https://www.dio.me), com o objetivo de praticar.

## 👨‍💻 Autor
**Gilcélio Júnior - Juntamente a DIO.ME**
- 💼 [LinkedIn](https://www.linkedin.com/in/gilc%C3%A9lio-j%C3%BAnior-ab032924a/)
- 🐙 [GitHub](https://github.com/gJuniordev)
