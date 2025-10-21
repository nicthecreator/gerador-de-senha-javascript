# 🔒 Gerador de Senhas Avançado

Um projeto simples e eficaz em JavaScript puro para gerar senhas seguras. Inclui opções de personalização e um medidor de força de senha em tempo real.

![Image](https://github.com/user-attachments/assets/3af90876-55fd-4356-add6-cfee744c30d2)

---

## ✨ Funcionalidades

* **Geração de Senhas Aleatórias:** Cria senhas fortes e únicas com base nos critérios do usuário.
* **Controle de Comprimento:** Permite ao usuário definir o comprimento exato da senha (ex: de 4 a 64 caracteres).
* **Opções de Personalização:**
    * Incluir Letras Maiúsculas (A-Z)
    * Incluir Letras Minúsculas (a-z)
    * Incluir Números (0-9)
    * Incluir Caracteres Especiais (`!@#$%^&*()_+-=`)
* **Medidor de Força:** Analisa a senha gerada e exibe um indicador visual (Ex: Fraca, Média, Forte, Muito Forte) e uma barra de progresso.
* **Copiar com Um Clique:** Botão para copiar a senha gerada diretamente para a área de transferência.
* **Design Responsivo:** Funciona em dispositivos móveis e desktops.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias:

* **HTML5:** Estrutura semântica do projeto.
* **CSS3:** Estilização, animações e layout (utilizando Flexbox/Grid).
* **JavaScript (ES6+):** Lógica principal do aplicativo, incluindo a geração da senha e o algoritmo de cálculo de força.

---

## 🚀 Como Usar

1. Acessando a versão online (Recomendado)
Você pode acessar a calculadora diretamente pelo link do GitHub Pages:

➡️ https://nicthecreator.github.io/gerador-de-senha-javascript/


Como este é um projeto de front-end puro, não há necessidade de instalação de dependências.

1.  Clone este repositório:
    ```bash
    git clone https://github.com/nicthecreator/gerador-de-senha-javascript.git
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd seu-repositorio
    ```
3.  Abra o arquivo `index.html` no seu navegador de preferência.

E pronto! Você já pode gerar suas senhas.

---

## 📈 Lógica de Força da Senha

O medidor de força da senha é calculado com base em alguns critérios principais:

1.  **Comprimento:** Senhas mais longas são exponencialmente mais fortes.
2.  **Variedade de Caracteres:** A pontuação aumenta para cada tipo de caractere incluído (maiúsculas, minúsculas, números, símbolos).
3.  **Entropia (Simplificada):** O cálculo combina o comprimento e a variedade para dar uma estimativa da dificuldade de quebra da senha.

A barra de segurança muda de cor (vermelho, amarelo, verde) com base na pontuação final.
