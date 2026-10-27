# 👾 The Life of Liana · Interactive 8-Bit Scrapbook

Um web app narrativo e interativo estilo *arcade retrô (8-bit / pixel art)* criado para coletar memórias, datas e histórias de amigos próximos de **Liana Oliveira**. 

Guiado pela personagem autoral **★ Estrela Torta**, o jogo conduz o jogador por diálogos com efeito de máquina de escrever, dinâmicas de respiração interativa, adivinhação cósmica e uma mecânica de "troca de segredos" — recompensando o jogador com memórias exclusivas e arquivando tudo em um scrapbook digital com persistência local e em nuvem.

---

## 🕹️ Experiência & Mecânicas do Jogo

- **Estética Chiptune / Arcade 8-Bit:**
  - Tipografia retrô com a fonte [`Press Start 2P`](https://fonts.google.com/specimen/Press+Start+2P).
  - Efeito visual de *scanlines* de TV de tubo (CRT), animações de wobble, pulso e confetes customizados em HTML5 Canvas.
  - Ilustrações e ícones desenhados manualmente em SVG pixelado.
  - Diálogos com efeito sonoro visual de digitação (*typewriter effect* com cursor piscante).

- **Fluxo Narrativo & Perguntas:**
  1. **Intro & Start:** Apresentação da Estrela Torta.
  2. **Identificação & Detecção de Gênero:** Coleta de nome e apelido carinhoso, com respostas personalizadas e piadas contextualizadas.
  3. **Palpite Cósmico:** *"Você sabe quantos anos vive uma estrela?"* com respostas dinâmicas baseadas na escala do palpite.
  4. **Mini-game de Respiração:** *"Cheirar a flor (inspirar) e assoprar a vela (expirar)"* interativo.
  5. **Idade & Signo Astrológico:** Cálculo automático do signo zodiacal através do dia e mês de nascimento, com leitura personalizada do signo cruzada com a energia geminiana da Liana.
  6. **Endereço Postal Opcional:** Coleta de endereço para envios futuros de cartas físicas (com opção de pular).
  7. **O Mercado de Segredos (A Troca):**
     - *"Segredo só se troca por segredo"*: validação do tamanho do texto (mínimo de palavras) para garantir memórias reais e detalhadas.
     - Personas exclusivas com roteiros sob medida: `emanuel` (Manel), `valdenor` (Valdy), `pedro hugo` e `liara` (Chali).
     - Roteiro geral poético sobre a infância de Liana no mar para os demais amigos.
  8. **Tela de Conquista:** Validação final e celebração visual em confetes pixelados.

- **Painel Administrativo Secreto (`Scrapbook Admin`):**
  - Acesso protegido por senha digitada na tela de nome.
  - Visualização de todas as respostas registradas em cards limpos com data/hora.
  - Exportação direta de todas as respostas em arquivo **CSV** formatado.
  - Opção para limpeza segura do banco local.

---

## 🛠️ Stack Tecnológica

- **Frontend:** HTML5, CSS3 puro (Grid, Flexbox, Keyframe Animations), Vanilla JavaScript (Zero dependências externas).
- **Gráficos & Renderização:** HTML5 Canvas (sistema de partículas de confetes e formas geométricas) + SVGs vetoriais pixel-art inline.
- **Tipografia:** Google Fonts (`Press Start 2P`).
- **Persistência de Dados Local:** Web Storage API (`localStorage`).
- **Integração em Nuvem:** Google Apps Script Web App (`fetch` assíncrono enviando JSON para planilha do Google Sheets via `POST`).

---

## 🚀 Como Executar o Projeto

Como o projeto é construído em um único arquivo autônomo (`single-file web app`), ele não requer compiladores, bundlers ou instalação de pacotes `npm`.

### Opção 1: Execução Local
1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
