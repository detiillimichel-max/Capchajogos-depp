# Capchajogos-depp
# 🚦 CAPTCHA das Fases · 20 Níveis de Semáforos

> **"Clique nos semáforos, prove que não é um robô… e entre no loop infinito da verificação humana."**

Um jogo web de meta‑humor que transforma o clássico desafio **CAPTCHA** em uma aventura de 20 fases. Cada fase apresenta uma grade 3×3 com imagens (emojis) – você precisa identificar e clicar em **todos os semáforos** (🚦 ou 🚥) para avançar. Ao completar a fase 20, o jogo **recomeça na fase 1 com todas as posições embaralhadas**, garantindo desafios infinitos e diferentes a cada ciclo.

![Prévia do jogo](https://via.placeholder.com/800x400?text=CAPTCHA+Game+Preview)  
*(substitua pela imagem real do seu projeto, se desejar)*

---

## 🎮 Como jogar

1. **Objetivo** – Em cada fase, clique em **todos os semáforos** escondidos entre outros ícones (carros, animais, objetos, etc.).  
2. **Controles** – Use o mouse ou toque na tela (mobile) para clicar nas cartas.  
3. **Progresso** – Após clicar nos 3 semáforos da fase, você avança automaticamente para a próxima.  
4. **Ciclo completo** – Ao final da fase 20, o jogo **retorna à fase 1** com uma **nova disposição aleatória** dos ícones.  
5. **Erros** – Clicar em algo que não é semáforo gera uma mensagem de erro e conta um “erro de robô” (apenas para humor – sem punição de progresso).  

---

## 🧠 Mecânicas e meta‑humor

- **Posições sempre diferentes** – Cada fase (e cada reinício) embaralha completamente a grade, usando um algoritmo de Fisher‑Yates. Você nunca enfrenta o mesmo layout duas vezes.  
- **20 fases + looping infinito** – Avance até a fase 20 e veja o jogo “resetar” para a fase 1 com novos posicionamentos, criando a ilusão de um CAPTCHA infinito.  
- **Mensagens sarcásticas** – O jogo provoca o jogador com frases como *“'🍕' NÃO é um semáforo! Robôs confundem…”* e *“Você já clicou nesse semáforo! Avance clicando nos outros.”*  
- **Contador de “erros de robô”** – Apenas para rir da sua própria “humanidade duvidosa”. Não bloqueia o progresso.

---

## 🛠️ Tecnologias utilizadas

- **HTML5** – Estrutura semântica e acessível.  
- **CSS3** – Layout responsivo, animações de clique e tremores (para erros), sombras divertidas.  
- **JavaScript (ES6)** – Lógica do jogo, geração procedural das grades, gerenciamento de fases, embaralhamento e loop infinito.

Nenhuma dependência externa – puro vanilla, pronto para rodar localmente ou em qualquer servidor web.

---

## 🚀 Como executar

1. **Baixe os arquivos** – salve o conteúdo em um arquivo `index.html`.  
2. **Abra no navegador** – duplo clique ou use “Abrir com” no seu browser favorito.  
3. **Comece a jogar** – clique nos semáforos e tente completar os 20 ciclos (ou apenas divirta-se com o humor meta).

> 💡 Dica: O jogo funciona perfeitamente em desktop (mouse) e mobile (toque). Não requer internet após carregado.

---

## 📁 Estrutura do projeto

© 2026 Michel Detilli.
Todos os direitos reservados. 
É permitido jogar online. É proibida a cópia, distribuição ou uso comercial do código sem autorização.
