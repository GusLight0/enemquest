# 🚀 ENEM Quest - Gamificação de Estudos

> **O Passo a Passo para sua Aprovação.** Transforme sua preparação para o ENEM em uma jornada épica de RPG.

![Status](https://img.shields.io/badge/Status-Concluído-success)
![License](https://img.shields.io/badge/License-MIT-blue)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20JS-yellow)

## 📖 Sobre o Projeto

**ENEM Quest** é uma aplicação web focada em estudantes que desejam organizar seus estudos de forma interativa e motivadora. Utilizando conceitos de **Gamificação**, o sistema transforma tarefas de estudo (como resolver simulados, assistir aulas e revisar conteúdos) em missões que geram XP (Experiência) e permitem subir de nível.

O design adota uma estética **Cyberpunk / Dark Mode**, focado em reduzir o cansaço visual e manter o usuário engajado com elementos visuais modernos e responsivos.

---

## ✨ Funcionalidades Principais

### 🎮 Sistema de Gamificação
*   **Níveis e XP:** Ganhe experiência ao completar tarefas e suba do Nível 1 (Fundação) ao Nível 6 (Aprovação).
*   **Missões Variadas:** Tarefas divididas em categorias: *Estratégia*, *Exame (Simulados)*, *Revisão* e *Boss (Desafios Finais)*.
*   **Barra de Progresso:** Visualização em tempo real do quanto falta para o próximo nível.

### 👤 Perfil do Candidato
*   **Customização:** Escolha seu Avatar, Nickname e a Cor do Tema (Neon Cyan, Roxo, Gold, etc.).
*   **Metas:** Defina seu "Curso Alvo" (ex: Medicina, Direito, Engenharia) para calibrar a dificuldade.
*   **Persistência de Dados:** Todo o progresso é salvo automaticamente no navegador (LocalStorage).

### 🛠 Ferramentas de Estudo
*   **Countdown:** Contagem regressiva automática para o dia da prova.
*   **Curadoria de Vídeos:** Área dedicada com aulas e dicas selecionadas do YouTube, com busca inteligente (ignora acentos).
*   **Quiz Interativo:** Batalhas contra "Chefes" em formato de quiz com questões reais/simuladas.

---

## 🎨 Design e UI/UX

*   **Tema:** Dark Mode com acentos Neon (Cyberpunk).
*   **Responsividade:** Layout totalmente adaptável para Desktop, Tablets e Smartphones.
*   **Interatividade:** Animações suaves (Fade-in, Hover effects), Modais e Transições.
*   **Visualização:** Cards de missões em formato "Retrato" (estilo Stories/Post) com imagens imersivas.

---

## 🚀 Como Executar

Este projeto é **estático** (não requer backend ou banco de dados complexo), o que o torna extremamente leve e fácil de rodar.

### Pré-requisitos
*   Um navegador web moderno (Chrome, Firefox, Edge, Safari).

### Passo a Passo
1.  Clone este repositório ou baixe os arquivos.
2.  Certifique-se de que a pasta `assets/img` contém as imagens das missões.
3.  Abra o arquivo `index.html` no seu navegador.

```bash
# Exemplo de estrutura de pastas recomendada
/Passar no ENEM
│
├── index.html          # Código Principal
├── README.md           # Documentação
└── assets
    └── img             # Imagens (banner.png, tarefa1.png, etc.)
```

---

## 💻 Tecnologias Utilizadas

*   **HTML5:** Estrutura semântica e acessível.
*   **CSS3:** Variáveis CSS (:root), Flexbox, CSS Grid, Animações (@keyframes) e Media Queries.
*   **JavaScript (Vanilla):** Lógica de jogo, manipulação do DOM, LocalStorage e filtros de busca.

---

## ⚙️ Personalização (Para Desenvolvedores)

Se você quiser adicionar novas missões, edite a constante `LEVELS` no final do arquivo `index.html`:

```javascript
{
    id: 105, 
    title: "Nova Missão de Física", 
    image: "./assets/img/nova-imagem.png", 
    desc: "Descrição da tarefa...", 
    type: "review", 
    xp: 300 
}
```

Para mudar a data do ENEM, altere a constante:
```javascript
const ENEM_DATE = new Date('2026-11-01T13:00:00');
```

---

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias no código ou novas ideias de missões.

---

<p align="center">
  Feito com 💻 e ☕ para estudantes de todo o Brasil.
</p>