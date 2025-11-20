# Dica para usar cursor customizado

- O formato GIF nem sempre é suportado como cursor em todos os navegadores. Prefira PNG ou CUR.
- O tamanho ideal é até 32x32 pixels.
- Exemplo de uso no CSS:

```css
body, html, a, button, input, textarea, select, * {
    cursor: url('images/zUS4f79.png'), auto !important;
}
```

- Certifique-se que o arquivo `images/zUS4f79.png` existe na pasta e está acessível.
- Se quiser usar GIF, tente:

```css
cursor: url('images/zUS4f79.gif'), auto !important;
```

Mas PNG é mais garantido!
