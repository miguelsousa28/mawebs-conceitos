# MA Webs, conceitos de site (06/08/2026)

## 06, Híbrido v2 (o conceito principal)

Ficheiro: `06-hibrido.html`. A v1 está no histórico do git se quiseres comparar.

### Tipografia
Fora o Archivo e o Space Mono. Entrou **Geist**, com Plus Jakarta Sans como reserva.
É a família mais próxima da SF Pro da Apple que existe em Google Fonts.
O que a faz parecer cara não é só a fonte: títulos a peso 500 com `letter-spacing -.05em`,
corpo a `-.011em`, e etiquetas pequenas na mesma família em vez de um mono à parte.

### Gradiente
Saiu o traço por baixo de "negócios". O gradiente está agora **dentro das palavras**
(`#2F3FD0 → #1E9B96`), com um deslocamento muito lento de 14s para não ficar estático.
Usado também nas etiquetas de secção, nos passos do processo e no logo.

### Alternativa ao vídeo da hero: "Parede de trabalho"
Saiu a placa 3D, que não pertencia ali. No lugar entrou o teu portefólio como imagem de topo:
três sites reais em molduras de browser, o principal ao centro e dois em perspetiva atrás,
inclinados. Tudo se move devagar conforme o rato.

- Mostra trabalho a sério no primeiro ecrã, que é o argumento mais forte que tens
- Não é preciso gravar nada, e as capturas trocam-se em cinco minutos
- Quando gravares o vídeo, substitui a moldura do centro sem mexer no resto

### Conceito do vídeo, se quiseres gravar

**"O Toque"**. Plano único, câmara fixa, luz baixa e lateral.
Uma mão pousa o telemóvel sobre a placa NFC no balcão. No instante do contacto,
uma onda de luz com o gradiente da marca sai da placa e atravessa a superfície.
O ecrã acende com o site do cliente. Corta. 8 a 10s, sem som, sem cortes.
Liga os dois serviços num só gesto. Precisas de um balcão escuro, um candeeiro quente
de lado, uma placa e um telemóvel.

Alternativa mais fácil, **"A Mesa"**: plano de cima, mãos a arrumar folhas com layouts,
um telemóvel e uma placa, tudo a encaixar na grelha do site.

### Processo preso no ecrã
A secção agarra o ecrã. A imagem da direita fica fixa e só o texto da esquerda avança
pelos quatro passos, com barras de progresso por baixo. Só depois de veres os quatro
é que o scroll segue para a secção seguinte. Em telemóvel desliga-se e fica em coluna.

### Portefólio
Seis projetos à vista, botão **Ver mais projetos** que revela mais nove com entrada escalonada,
e um botão **Ver portfólio completo** ao lado. Falta ligar esse botão a uma página real.

### Placas NFC, reescrito de raiz
A versão anterior era uma lista de especificações e não vendia nada. Agora:
- Abre pela dor: os melhores clientes saem sem deixar avaliação, e o concorrente ao lado tem 120
- **Demonstração ao vivo**: passa o rato pela placa e o telemóvel ao lado mostra o que o cliente vê,
  do ecrã bloqueado até à avaliação publicada
- Três tempos: encosta, abre, fica feito
- **Três packs com preço**, objeções respondidas no fim (prazo, e quem não tem NFC leva QR no verso)

### Falamos 15 minutos
Secção própria, com o guião da chamada minuto a minuto, o que ganhas mesmo que não trabalhes
connosco, e dois caminhos: WhatsApp com mensagem já escrita, ou email.

### Dynamic Island no header
Em cima é uma barra normal com os links. Ao fazer scroll encolhe para uma cápsula compacta
que mostra em que secção estás e reduz o botão ao ícone. Passa o rato por cima e volta a abrir.
Tudo com uma curva com ligeiro ressalto, como no iPhone.

### Footer
Descrição e colunas de links, linha fina, direitos reservados, e o wordmark **MA Webs**
gigante e esbatido cortado em baixo.

---

## Por decidir antes de publicar

1. **Número de WhatsApp.** Está `351900000000` de propósito, à espera do teu
2. **Preços das placas NFC.** Estão 49 / 189 / 329 euros como exemplo, não são teus
3. **Email.** Está `ola@mawebs.com`
4. **Capturas reais** dos sites, para trocar as imagens de exemplo
5. **Fotos das placas NFC**, três espaços já preparados
6. Para onde aponta o botão "Ver portfólio completo"

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
