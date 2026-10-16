# O Cortiço em maquete

Maquete 3D interativa do romance *O Cortiço*, de Aluísio Azevedo, feita para o trabalho "O Cortiço como Organismo Vivo".

**Grupo:** Victor, Cássio, Sérgio e Enzo R. · turma 62-2

## Como usar

- Arraste para girar a maquete e role (ou pince) para aproximar.
- Clique num prédio ou numa etiqueta para abrir a ficha: o lugar, a mudança do personagem, trechos do livro, conceitos (Determinismo, Zoomorfização, Positivismo, Meio social) e a conexão com hoje.
- `Esc` ou o botão × fecham a ficha.

## Rodar localmente

É um site estático, sem build. Abra `index.html` no navegador ou rode:

```bash
npx serve .
```

## Publicar na Vercel

1. Em vercel.com, clique em **Add New → Project** e importe este repositório.
2. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios.
3. Clique em **Deploy**.

A maquete usa Three.js r128 carregado por CDN (cdnjs e jsDelivr), então precisa de internet para abrir.

## Fonte das citações

AZEVEDO, Aluísio. *O cortiço*. Capítulo indicado em cada trecho. Fases marcadas "após o cap. X" resumem o final do livro, sem citação direta.
