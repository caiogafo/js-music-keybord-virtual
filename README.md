# 🎹 Piano Virtual

Um piano virtual simples e interativo, feito com **HTML, CSS e JavaScript**. Toque as notas clicando nas teclas da tela ou usando o teclado do computador.

## ✨ Recursos

- 17 teclas com sons individuais.
- Reprodução pelo clique ou pelo teclado do computador.
- Controle de volume.
- Opção para exibir ou ocultar as letras das teclas.
- Destaque visual ao tocar uma nota.

## 🎼 Como tocar

Use as teclas abaixo para tocar as notas correspondentes:

| Teclas brancas | Teclas pretas |
|:---:|:---:|
| `A` `S` `D` `T` `Y` `U` `K` `L` `;` | `W` `E` `F` `G` `H` `J` `O` `P` |

Você também pode clicar diretamente nas teclas do piano. Ajuste o volume pelo controle no topo e use o seletor **Teclas** para mostrar ou esconder as letras.

## 🚀 Como executar

Não é necessário instalar dependências nem compilar o projeto:

1. Baixe ou clone este repositório.
2. Abra `index.html` no navegador.

Para uma experiência melhor durante o desenvolvimento, abra a pasta com uma extensão de servidor local, como o **Live Server** do VS Code.

## 🧰 Tecnologias

- HTML5
- CSS3
- JavaScript
- Áudios `.wav` individuais para cada nota
- Fonte [Poppins](https://fonts.google.com/specimen/Poppins)

## 📁 Estrutura do projeto

```text
.
├── index.html
└── src/
    ├── scripts/
    │   └── engine.js
    ├── styles/
    │   ├── main.css
    │   └── reset.css
    └── tunes/
        ├── a.wav
        ├── w.wav
        └── ... outros sons das teclas
```

## 🎧 Sobre os sons

Os arquivos de áudio ficam em `src/tunes/`. Cada arquivo usa como nome a tecla que reproduz aquele som — por exemplo, `a.wav` corresponde à tecla `A`.

---

Feito para aprender e se divertir com música no navegador. 🎶
