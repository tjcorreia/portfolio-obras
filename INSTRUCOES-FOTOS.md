# Como adicionar fotos ao portefólio

## Pasta de imagens

Cada employer tem a sua subpasta dentro de `images/`:

```
images/
  bogas/
  tricivil/
  wartsilä/
  vhm/
```

## Convenção de nomes de ficheiro

Usa o prefixo indicado abaixo + número sequencial (01, 02, 03...):

### Bogas Construções
| Obra | Prefixo |
|---|---|
| Loteamento das Alagoas | `alagoas-01.jpg` |
| Urbanização Quinta do Zagão | `zagao-01.jpg` |
| Loteamento da Soila | `soila-01.jpg` |
| Loteamento do Fojo | `fojo-01.jpg` |
| Loteamento da Tapada | `tapada-01.jpg` |
| Moradia privada Carregal (820m2) | `eduardo-abrantes-01.jpg` |
| Moradia privada Póvoa Sto. António | `abilio-sa-01.jpg` |
| Reab. Currelos (930m2) | `jose-vaz-serra-01.jpg` |
| Quinta da Roda | `quinta-roda-01.jpg` |
| Reab. Oliveirinha (110m2) | `walker-01.jpg` |

### Tricivil
| Obra | Prefixo |
|---|---|
| PLUS Beja | `plus-beja-01.jpg` |

### Wärtsilä
| Obra | Prefixo |
|---|---|
| Peru - Lote 8 | `peru-lote8-01.jpg` |
| Peru - Lote 1AB | `peru-lote1ab-01.jpg` |
| Madeira - CTV III | `madeira-ctv3-01.jpg` |
| Cabo Verde - Palmarejo | `caboverde-palmarejo-01.jpg` |
| Gabão - PG2 Total | `gabao-pg2-01.jpg` |
| Moçambique - CTRG | `mocambique-ctrg-01.jpg` |
| Argentina - Costanera | `argentina-costanera-01.jpg` |
| Marrocos - Dakhla | `marrocos-dakhla-01.jpg` |

### VHM
| Obra | Prefixo |
|---|---|
| ETAR Ílhavo | `etar-ilhavo-01.jpg` |
| ETAR Leiria | `etar-leiria-01.jpg` |
| Condomínio Torricentro | `torricentro-01.jpg` |
| Hospital CUF Coimbra | `cuf-01.jpg` |
| Fórum Aveiro / FNAC | `fnac-aveiro-01.jpg` |

## Como ativar uma foto no HTML

No `index.html`, cada card tem um comentário como este:

```html
<div class="card-photo">
  <!-- img src="images/bogas/alagoas-01.jpg" alt="Loteamento das Alagoas" -->
  Foto a adicionar
</div>
```

Para ativar a foto:
1. Copia a imagem para a pasta correta (ex: `images/bogas/alagoas-01.jpg`)
2. No `index.html`, remove o `<!--` e `-->` e apaga o texto "Foto a adicionar":

```html
<div class="card-photo">
  <img src="images/bogas/alagoas-01.jpg" alt="Loteamento das Alagoas">
</div>
```

## Formato recomendado
- Formato: JPEG ou WebP
- Proporção: 16:9 (ex: 800x450px)
- Tamanho: máximo 300KB por foto para carregamento rápido no GitHub Pages

## Publicar no GitHub Pages

1. Cria um repositório GitHub (ex: `portfolio-obras`)
2. Faz upload de todos os ficheiros desta pasta
3. Em Settings > Pages, seleciona `main` branch e pasta `/ (root)`
4. O portefólio ficará disponível em `https://SEU-USERNAME.github.io/portfolio-obras/`
