# MA Webs, conceitos de site (06/08/2026)

## 06, Híbrido (o que pediste)

Tipografia e proporções do conceito 03 (Archivo + Space Mono, Suíço, preciso)
dentro do layout do conceito 04 (hero centrada, moldura dupla, cartões suaves, processo fixo).
Mais o que faltava de marca:

- **Gradiente de marca** `#3E4FD4 → #39B3AE`, com sublinhado a desenhar-se por baixo de "negócios" mal a página abre
- **Fundo WebGL que reage ao rato** (é isto que procuravas quando disseste "renders"): duas nuvens de cor a fluir devagar sobre branco quente, com uma luz que segue o cursor. Desliga-se sozinho fora do ecrã para não gastar bateria
- **3D**: placa NFC na hero que se inclina conforme o rato, cartões com inclinação suave, moldura do vídeo que cresce e endireita com o scroll
- Ficheiro: `06-hibrido.html`

---

## Conceito do vídeo da hero

Faltava isto e é a decisão que destranca a gravação. Três hipóteses, por ordem de recomendação.

### A. "O Toque" (recomendado)

Um plano único, câmara fixa, câmara lenta suave, luz baixa e lateral.
Uma mão pousa o telemóvel sobre a placa NFC no balcão. No instante do contacto,
uma onda de luz com o gradiente da marca sai da placa e atravessa a superfície.
O ecrã do telemóvel acende com o site do cliente. Corta.

- **Porquê:** liga os dois serviços num só gesto, sem explicar nada. Website e placa NFC no mesmo plano
- **Precisas de:** um balcão escuro, um candeeiro quente de lado, uma placa, um telemóvel com o site aberto
- **Duração:** 8 a 10s em loop, sem som, sem cortes
- **Truque:** grava o brilho separado com o telefone a filmar uma lanterna a passar, e sobrepõe. Ou deixa comigo em pós

### B. "A Mesa"

Plano de cima, mãos a arrumar folhas impressas com layouts, um telemóvel e uma placa NFC.
Tudo desliza e encaixa numa grelha que é exatamente a grelha do site.

- **Porquê:** casa com a tipografia suíça do 03, é o registo mais estúdio
- **Mais fácil de gravar**, menos impacto que a A

### C. Sem vídeo, só o render

A hero fica só com o fundo WebGL e a placa 3D a reagir ao rato.
O próprio site demonstra o toque NFC, sem gravar nada.

- **Porquê:** zero produção, funciona já hoje, e é o que está no `06-hibrido.html`
- **Contra:** não mostra um negócio real

**Sugestão:** publica com a C hoje, grava a A este fim de semana e troca. A moldura já está lá à espera.

---

# Os cinco conceitos base

Cinco direções para o site novo da agência. Todos calmos, muito branded e caros. Nada playful.
Abre o `index.html` para os ver lado a lado, ou cada ficheiro diretamente.

| # | Nome | Registo | Paleta |
|---|------|---------|--------|
| 01 | Noir Cinema | Preto de cinema, serifa fina, bronze | `#070707` `#E8E3D9` `#C0A176` |
| 02 | Editorial Quiet | Papel creme, serifa em itálico, barro | `#F4F1EA` `#141210` `#8A5A3B` |
| 03 | Archive Grid | Suíço, grelha à vista, azul tinta | `#FAF9F6` `#16181A` `#24304A` |
| 04 | Soft Monolith | Branco quente, sombras difusas, ardósia | `#F7F6F4` `#1B1D1F` `#4A5B6B` |
| 05 | Obsidian Luxe | Preto esverdeado, jade, cinematográfico | `#070A09` `#E6EAE7` `#9FB8AD` |

## O que já lá está

- Scroll animations reais em todos (revelações lentas, galerias presas, máscaras, empilhamento)
- Secção dedicada às **placas NFC custom**, com três espaços à espera das tuas fotos
- Serviços, trabalho, números, chamada de 15 minutos e rodapé
- Projetos com nomes reais: Mr. Burger, Raízes do Sobreiro, Gama Barbearia, Escola de Música da Malveira, Zenith Beauty Space, Casa da Rocha, AG Premier, Brah Ericeira
- Imagens dos projetos são de exemplo (picsum), trocam-se por capturas reais

## O que falta de ti

### 1. Vídeo ou imagem da hero
Cada conceito tem o espaço marcado e a sugestão escrita lá dentro. Resumo:

| # | Formato | Ideia |
|---|---------|-------|
| 01 | 16:9, loop 8s, sem som | Balcão escuro, mão a encostar o telemóvel na placa NFC, luz quente lateral |
| 02 | Vertical 4:5, foto | Montra ou balcão de cliente, placa NFC em primeiro plano |
| 03 | 21:9, loop 10s | Plano fixo, mão a encostar o telemóvel na placa |
| 04 | 16:9, loop 10s | Ecrã do site a ser percorrido, depois o telemóvel na placa |
| 05 | Vertical 3:4, loop 8s | Plano fechado da mão na placa, luz baixa |

### 2. Fotos das placas NFC
Três por conceito: placas no balcão, detalhe do material, telemóvel a encostar.

### 3. Decisões
- Qual dos cinco, ou que partes misturar
- Fica em MA Webs ou passa a MA Studios
- Preço a mostrar nas placas NFC, ou só "pedir orçamento"

## Depois de escolheres

O site final não vai para o Lovable. Fica em Next.js ou HTML estático, publicado por nós,
com as capturas reais dos projetos em vez das imagens de exemplo.
