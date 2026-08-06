# Prompt para gerar a imagem cinemática da hero

Cola no ChatGPT (ou noutro gerador de imagem). Está em inglês de propósito, os modelos respondem melhor.

---

## Prompt principal, recomendado

```
Cinematic wide product photograph, 16:9, shot on a 35mm lens at f/2.0.

Scene: a dark walnut counter in a small independent business at night, after closing.
On the counter, angled slightly toward camera, sits a matte black acrylic plaque about
9cm wide with a minimal engraved geometric monogram made of two interlocking letters,
M and A, sharing one diagonal stroke. Next to it, a modern smartphone lies face up,
screen glowing softly with an abstract clean website interface, no readable text.

Lighting: single warm tungsten key light from camera left at a low angle, creating a
long soft falloff across the counter. Deep shadows on the right. A faint cool rim light
separates the plaque from the background. Subtle practical bokeh lights far in the
background, heavily out of focus.

Mood: quiet, expensive, understated. Editorial product photography for a design studio.
Palette strictly monochrome: black, charcoal, warm grey, off-white. No colour accents
other than the warm tungsten glow.

Details: fine dust motes in the light beam, gentle film grain, natural micro-scratches
on the acrylic, shallow depth of field with the plaque tack sharp and the phone slightly
soft. Clean negative space in the upper third of the frame for a headline overlay.

No text, no logos other than the abstract monogram, no people, no watermarks.
Photorealistic, not an illustration, not 3D render style.
```

---

## Notas para ajustar

- **Espaço para o título.** A última instrução, "clean negative space in the upper third",
  é o que garante que o texto da hero assenta em cima sem competir. Se a imagem sair cheia,
  repete essa frase no fim.
- **Sem texto.** Os geradores insistem em inventar letras. Se aparecer texto, acrescenta
  no fim: `absolutely no lettering, no typography, no signage`.
- **Monograma.** Como é uma marca nova, o modelo não a conhece. A descrição
  "two interlocking letters M and A sharing one diagonal stroke" aproxima. Se sair mal,
  pede a imagem sem monograma nenhum e eu sobreponho o logótipo verdadeiro por cima.
- **Formato.** Pede 16:9 para a moldura da hero. Para o telemóvel, corre outra vez
  a trocar `16:9` por `4:5` e `wide` por `vertical`.

---

## Variantes, se quiseres testar outros ângulos

**1. Mais humano, com mão**
Troca a frase da cena por:
```
A hand enters from the right edge of the frame, holding a smartphone a few centimetres
above the black acrylic plaque, caught in the instant before contact. Only the hand and
forearm are visible, no face.
```

**2. Mais estúdio, menos loja**
```
Scene: a matte black acrylic plaque and a smartphone arranged on a seamless warm grey
paper backdrop, top-down flat lay, studio softbox lighting from above with a single
hard shadow to the lower right.
```

**3. Mais montra, mais contexto de negócio**
```
Scene: shot from inside a small shop looking out through the glass at dusk. In sharp
focus on the window ledge sits the black acrylic plaque. Beyond the glass, the street
is a warm blur of passing light trails.
```

---

## Depois de gerares

Manda-me o ficheiro e eu trato de:

- cortar para 16:9 e para 4:5
- baixar peso para carregar rápido
- montar na moldura da hero, com o texto por cima e a escurecer o suficiente para se ler
- marcar como conteúdo gerado por IA nos metadados, como manda o regulamento europeu
