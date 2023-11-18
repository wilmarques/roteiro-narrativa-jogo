# roteiro-narrativa-jogo

## Atividade

Atividade avaliativa da matéria Roteiro e Narrativa

- [x] Rascunho com as principais ideias
  - Caracterização de personagens
  - Espago e Tempo
- [x] Sinopse com Enredo sintético
- Roteiro
  - Um tutorial mostrando a dinâmica do jogo
  - Ou o início da primeira fase do jogo

Os elementos centrais da narrativa são:

- o ponto de vista do narrador;
- as personagens (identificação de seu papel na narrativa);
- espago e tempo
- O conflito principal;
- situações-chave;
- a resolução da história

## Como gerar o PDF

Exemplo gerando para o arqivo `ideia.md`:

```bash
docker run --rm --volume "`pwd`:/data" --user `id -u`:`id -g` pandoc/latex ideia.md -o ideia.pdf
```
