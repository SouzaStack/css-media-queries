# Responsividade & Media Queries

## Responsividade?
A **responsividade** refere-se à capacidade de um site ou sistema se adaptar dinamicamente a diferentes dispositivos e tamanhos de tela, garantindo uma navegação intuitiva e eficiente.

----

## Media Queries?

As **media queries** são um recurso do CSS que permite aplicar diferentes estilos com base no tamanho da tela ou outras características do dispositivo. Com isso, conseguimos criar layouts que se ajustam automaticamente a diferentes resoluções.

### Exemplo de uso:

```
@media (max-width: 768px) {
  body {
    background-color: lightgray;
  }
}
```

No exemplo acima, o fundo do site ficará cinza quando a largura da tela for de até **768px**.

----

## Mobile First?

**Mobile First** é uma abordagem de desenvolvimento onde o design e a estrutura do site são inicialmente criados para dispositivos móveis e depois adaptados para telas maiores.

### Vantagens do Mobile First:

- [x] Melhor desempenho em dispositivos móveis;
- [x] Maior acessibilidade para usuários em diferentes telas;
- [x] SEO otimizado para mecanismos de busca.

### Exemplo de abordagem Mobile First:

```
body {
  font-size: 16px;
}

@media (min-width: 1024px) {
  body {
    font-size: 18px;
  }
}
```

No código acima, o tamanho da fonte será **16px** por padrão (dispositivos móveis) e aumentará para **18px** em telas maiores que **1024px**.

----

# Autores

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/61896274?v=4" width=115><br><sub>Fernanda Kipper</sub>](https://github.com/Fernanda-Kipper) |  [<img loading="lazy" src="https://avatars.githubusercontent.com/u/193841372?v=4" width=115><br><sub>Matheus Souza</sub>](https://github.com/SouzaStack) |
| :---: | :---: |