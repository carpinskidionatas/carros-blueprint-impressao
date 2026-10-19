# Carros — Blueprints para Impressão 3D

Ambiente para organizar referências técnicas, blueprints, modelos e arquivos de preparação para impressão 3D de carros.

## Estrutura

- `blueprints/` — vistas ortográficas e desenhos de referência (frente, lateral, traseira e superior).
- `modelos-3d/` — arquivos-fonte de modelagem, como BLEND, STEP, F3D e OBJ.
- `impressao/` — arquivos prontos ou preparados para impressão, como STL, 3MF e perfis de fatiamento.
- `imagens/` — renders, fotos de referência e prévias.
- `docs/` — medidas, notas de projeto e documentação complementar.

## Convenção de nomes

Use nomes sem espaços e com informações essenciais:

```text
marca-modelo-ano_escala_versao.ext
```

Exemplo:

```text
ford-mustang-1967_1-24_v01.stl
```

## Fluxo recomendado

1. Adicione as referências em `blueprints/`.
2. Modele mantendo escala e unidades consistentes, preferencialmente em milímetros.
3. Valide espessuras, superfícies fechadas e orientação.
4. Exporte o arquivo final para `impressao/`.
5. Registre material, altura de camada, suportes e demais parâmetros no arquivo de notas do projeto.

## Observações

- Verifique os direitos de uso das imagens, marcas e modelos antes de publicar ou distribuir.
- Arquivos binários grandes podem exigir Git LFS.
- Evite versionar arquivos temporários ou gerados automaticamente pelo fatiador.

## Status

Estrutura inicial criada. Adicione cada veículo em uma subpasta própria para manter o histórico organizado.
