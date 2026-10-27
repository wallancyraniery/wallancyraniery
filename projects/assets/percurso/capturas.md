# Origem das capturas do Percurso

Capturas reais de Chrome headless, sem composição ou edição de pixels. Conteúdo e nomes exclusivamente fictícios, já presentes no protótipo. Não são evidência de uso institucional ou validação profissional.

**Aplicação:** [educacao_inclusiva](https://github.com/wallancyraniery/educacao_inclusiva), commit `e7098ca5f9898039889187ee6bb3cb9ba78e51f2`.

**Ambiente:** Next.js em desenvolvimento, executado em `http://127.0.0.1:3107`, sem deploy. Navegador restrito a requisições locais. Nesta recaptura desktop foi usada temporariamente a configuração `devIndicators: false` do Next.js 16; ela foi removida da cópia da aplicação após a sessão.

**Viewport de origem:** 1440 × 1100, escala de dispositivo 1. Capturas de página inteira podem excluir a barra de rolagem e ter altura maior que o viewport. Avisos demonstrativos preservados. O indicador de desenvolvimento foi desativado por configuração, sem edição das imagens.

| Captura | Rota | Enquadramento | Dimensões do PNG | Bytes |
| --- | --- | --- | --- | --- |
| [painel-inicial-desktop.png](painel-inicial-desktop.png) | `/` | viewport | 1440 × 1100 | 190,241 |
| [analise-objetivos-desktop.png](analise-objetivos-desktop.png) | `/objetivos` | página inteira | 1425 × 1268 | 235,379 |
| [banco-atividades-desktop.png](banco-atividades-desktop.png) | `/atividades` | viewport | 1440 × 1100 | 253,819 |
| [documento-demonstrativo-desktop.png](documento-demonstrativo-desktop.png) | `/pei` | página inteira | 1425 × 1727 | 345,077 |

## Estados registrados

- Painel: estado demonstrativo inicial; data, contadores e percentual são exemplos fixos.
- Objetivos: estado inicial do componente, com três sugestões predefinidas como selecionadas.
- Atividades: catálogo inicial, sem filtros ou decisões; enquadramento do viewport, sem ocultação de falhas.
- Documento: uma seleção real no catálogo (“Três cenas, uma história”) seguida do link “Continuar para documento”; PDI padrão, sem edição das observações fictícias existentes. A prévia usa três objetivos fixos, sem refletir as edições da tela anterior.

## Integridade e data

- `painel-inicial-desktop.png` — 2026-10-27T01:17:49-03:00; SHA-256 `035f61cbbd00e0187ee919b839503f1a421d8353e45e2211a0f2a8e6fdd6f39f`.
- `analise-objetivos-desktop.png` — 2026-10-27T01:18:05-03:00; SHA-256 `064afd6ef79ec03125a3ba9a71ece35bdd0b01cac828227439800fd5dbb857c4`.
- `banco-atividades-desktop.png` — 2026-10-27T01:18:15-03:00; SHA-256 `262a30186059319b4daf405be472f365cdfde6635b854d9115e6931345f3a420`.
- `documento-demonstrativo-desktop.png` — 2026-10-27T01:18:36-03:00; SHA-256 `34a41706a217c21d89bd7273fcd7e40d0685df26dd3235a4fb2e3c7700771506`.

## Alcance da verificação

As quatro rotas também foram observadas em viewport 390 × 844. Não houve overflow horizontal do documento ou exceção de execução registrada nessa passagem. A navegação de etapas usa rolagem horizontal local no celular. As capturas mobile e os registros de execução foram mantidos como evidências temporárias fora do repositório, sem ampliar esta galeria.

Isso não é teste de dispositivo físico, leitor de tela, acessibilidade integral ou avaliação pedagógica. O estado é efêmero e reinicia ao atualizar. As imagens não representam documentos oficiais.

[Voltar à apresentação](../../percurso.md)
