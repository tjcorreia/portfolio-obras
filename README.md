# Portefólio de Obras — Tiago Correia

Página estática com o portefólio de obras de engenharia civil de Tiago Correia, publicada via GitHub Pages:

🔗 **https://tjcorreia.github.io/portfolio-obras/**

## Funcionalidades

- Portefólio organizado por empregador/período (VHM, Wärtsilä/Citec, Bogas Construções, Tricivil, Toporama), com carrosséis de fotos, localização, cliente e métricas de cada obra.
- **Site bilingue (PT/EN)** com seletor manual no canto superior direito. Por defeito, mostra português para visitantes em Portugal ou com o browser configurado em português, e inglês nos restantes casos. A escolha do utilizador fica guardada no browser.
- Exportação da página para PDF (botão "Exportar PDF" / "Export PDF").

## Estrutura

```
index.html   - página principal (conteúdo PT + traduções em atributos data-en)
style.css    - estilos, incluindo layout de impressão
images/      - fotos das obras, organizadas por empregador
```

Para adicionar novas fotos, ver [INSTRUCOES-FOTOS.md](INSTRUCOES-FOTOS.md).

## Adicionar/editar traduções

Os textos traduzíveis têm um atributo `data-en="..."` no HTML com a versão em inglês; o texto visível por defeito no ficheiro é o português. O script no fundo do `index.html` faz a troca de idioma em tempo real (sem recarregar a página).
