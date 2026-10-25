# EmotiAI Vision — Guia passo a passo

Site-tutorial que explica, módulo por módulo, o código do projeto
[computacional-vision](https://github.com/<seu-usuario>/computacional-vision)
(EmotiAI Vision) — um sistema de visão computacional que estima postura
corporal e participação em sala de aula sem reconhecimento facial.

✋ **Ponto alto:** a seção "Teste pela sua câmera" mostra, ao vivo no navegador, o
sistema encontrando a pessoa e percebendo o gesto de braço levantado.

## Estrutura

```
├── index.html        # Estrutura da página e conteúdo do tutorial
├── css/
│   └── styles.css    # Todo o visual (tema claro, fonte Lexend, destaque amarelo)
└── js/
    ├── main.js        # Índice lateral, menu mobile e barra de progresso de leitura
    └── live-demo.js   # Demonstração ao vivo pela câmera
```

## Como abrir

- **Direto:** dê duplo clique em `index.html` — funciona offline, exceto a
  seção "Testar ao vivo", que precisa de internet para baixar o modelo do
  MediaPipe na primeira vez (vem de `cdn.jsdelivr.net` e
  `storage.googleapis.com`).
- **Publicado (recomendado):** ative o GitHub Pages neste repositório
  (Settings → Pages → branch `main`, pasta `/`) para gerar um link do tipo
  `https://<seu-usuario>.github.io/<nome-do-repositorio>/`, que abre em
  qualquer navegador, computador ou celular.

## Autoria

Tutorial produzido para a Atividade Prática Supervisionada (APS) — Ciência
da Computação, Universidade Paulista (UNIP), campus Limeira – SP.

- Ana Clara Alves Candido
- Luís Fillipe Lourenço de Faria
- Paloma Eduarda Paulino Figueiredo

Orientador: Danilo Rodrigues Pereira
