# 📊 Data Planner: Trilha de Estudos & Planner Diário em Análise de Dados

O **Data Planner** é uma aplicação web desenvolvida para organizar, acompanhar e motivar a rotina de estudos em Análise de Dados. O projeto resolve a dor da inconsistência na aprendizagem, unificando a gestão de conteúdos com o registro do tempo real de dedicação por matéria.

🔗 **Acesse a aplicação online:** [https://maria-apsguiar.github.io/Data-Planner/](https://maria-apsguiar.github.io/Data-Planner/)

---

## ⚡ Usabilidade & Principais Funcionalidades

A ferramenta foi projetada com foco na experiência do usuário (UX), sem necessidade de cadastros ou instalações — todos os dados são salvos com privacidade no próprio navegador (`localStorage`).

---

### 1. ⏱️ Temporizador Diário & Vinculação por Curso
* **Gestão Flexível de Horas:** Dê **Play (▶)** para iniciar seus estudos, **Pause (⏸)** para pausas e **Finalizar Dia (⏹)** para encerrar o ciclo.
* **Rastreamento Individual:** Antes de iniciar a contagem, é possível selecionar qual curso em andamento você vai estudar. O tempo contado é acumulado tanto no total do dia quanto **especificamente no histórico daquela matéria**.
* **Proteção de Dados:** Ao clicar em *Finalizar Dia*, a aplicação solicita confirmação para evitar perdas acidentais de tempo registrado.
* **Modo Segundo Plano:** A contagem continua rodando mesmo enquanto você assiste a aulas em outras abas, exibindo o tempo direto no título da janela (ex: `⏱️ 01:30:00 - Planner`).

---

### 2. 📅 Agenda Diária Dinâmica
* **Acompanhamento Automático:** Cursos marcados como "Em andamento" entram direto na agenda do dia selecionado.
* **Métrica de Dedicação por Matéria:** Exibe o tempo exato acumulado em cada curso no dia (ex: `⏱️ Tempo estudado hoje: 1h 30m`).
* **Check-in Inteligente:** Botão simples para confirmar a conclusão do dia, com lembretes visuais em tarefas síncronas/obrigatórias (como o Canvas da Generation).

---

### 3. 🔥 Dashboard Semanal (Últimos 7 Dias) & Gamificação
* **Histórico dos Últimos 7 Dias:** Painel responsivo que exibe seu desempenho diário com indicadores visuais:
  * 🔥 **Foguinho:** Dias com 1 hora ou mais de estudo.
  * ✅ **Check Verde:** Dias com estudo registrado.
  * ⚪ **Bolinha:** Dias sem registro.
* **Ofensiva (Streak):** Contador de dias seguidos de check-in para manter a motivação e constância.

---

### 4. 📚 Curadoria & Categorias de Conteúdo
A lista principal organiza os materiais para facilitar a navegação:
* 📌 **Acompanhamento Diário:** Foco diário síncrono.
* 🎯 **Cursos Principais:** Certificações e formação base.
* 🛠️ **Lições / Aulas Práticas:** Ferramentas hands-on (Google Colab, Draw.io, Diagrams.net, Pandas, Python, etc.).
* 🇬🇧 **Links úteis para Inglês:** Guia de apps recomendados para prática diária (Duolingo, HelloTalk).
* 💡 **Bolsas, Cursos e Links Úteis:** Plataformas complementares (Mimo, Livro de Estatística da USP, Santander, DIO, Rocketseat, etc.).
* 🔒 **Transparência e Acesso Restrito:** Conteúdos exclusivos de bootcamp possuem aviso explicativo transparente sem expor URLs privadas.

---

### 5. 📝 Anotações Rápidas & Estado dos Cursos
* **Três Estados:** Alterne com um clique entre **Pendente (⚪)**, **Em andamento (⏳)** e **Concluído (✓)**.
* **Bloco de Notas Integrado:** Cada card possui uma área expansível para salvar comandos, trechos de código e lembretes rápidos.
* **Backup Geral:** Botões de **`📥 Exportar`** e **`📤 Importar`** para transferência simples de dados via arquivo `.json`.

---

## 🛠️ Tecnologias Utilizadas
* **Frontend:** HTML5, CSS3 (CSS Variables, Flexbox, CSS Grid) e JavaScript Vanilla.
* **Persistência de Dados:** Web Storage API (`localStorage`).
* **Versionamento & Deploy:** Git, GitHub e GitHub Pages.

---
*Projeto desenvolvido por estudante para estudantes. Bons estudos! 🚀*