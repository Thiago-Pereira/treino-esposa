# 🌸 Treino & Definição Feminina

Web App mobile-first (estilo PWA em arquivo único) para acompanhamento de treino semanal focado em **definição muscular, queima calórica e cardio descomplicado**.

---

## ✨ Destaques do Projeto

- **Foco em Emagrecimento e Definição:** Rotina de 3x por semana (Glúteos & Posteriores, Superiores & Postura, Pernas Completas & Core).
- **Cardio Descomplicado ("Anti-Tédio"):** Estratégias confortáveis e eficazes sem precisar correr (caminhada inclinada na esteira assistindo série/podcast, cardio express de 12 min pós-treino e metas de passos).
- **Rastreador de Séries Interativo:** Marcação de séries concluídas com persistência automática no `localStorage`.
- **Cronômetro Flutuante com Som e Vibração:** Timer automático de descanso ao marcar séries concluídas, com aviso sonoro (Web Audio API) e vibração no smartphone.
- **Design Rose / Magenta Moderno:** Interface escura e elegante, com suporte a safe-area para iOS (entalhe/notch) e Android.
- **Zero Dependências:** Funciona 100% offline em qualquer navegador móvel ou desktop.

---

## 🚀 Como Publicar no GitHub Pages

1. Crie um novo repositório no seu GitHub (exemplo: `treino-esposa`).
2. No seu terminal, na pasta deste projeto:
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit do app de treino"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
   git push -u origin main
   ```
3. No GitHub:
   - Vá em **Settings** > **Pages**.
   - Em **Build and deployment** > **Source**, selecione **Deploy from a branch**.
   - Escolha a branch `main` e a pasta `/ (root)`.
   - Clique em **Save**.
4. Em instantes, o link público do app estará disponível! No celular, basta abrir no Safari ou Chrome e clicar em **"Adicionar à Tela de Início"** para usá-lo como um aplicativo nativo.
