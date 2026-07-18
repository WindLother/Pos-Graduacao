# Pós-Graduação em Gerenciamento de Projetos e Processos

Repositório com os materiais, exercícios e projetos práticos desenvolvidos ao longo da pós-graduação, organizados por disciplina.

## Sobre

Este repositório reúne anotações, entregas e artefatos (dashboards, documentos, apresentações) produzidos durante o curso, servindo como portfólio de estudo e referência para consulta futura.

## Disciplinas

| # | Disciplina | Pasta |
|---|---|---|
| 01 | Fundamentos de Gerenciamento de Projetos | [`01-fundamentos-gerenciamento-projetos`](./01-fundamentos-gerenciamento-projetos) |
| 02 | Gestão com Pessoas, Comunicação e Motivação de Equipes em Projetos e Processos | [`02-gestao-pessoas-comunicacao-motivacao`](./02-gestao-pessoas-comunicacao-motivacao) |
| 03 | Gestão de Escopo e Cronograma | [`03-gestao-escopo-cronograma`](./03-gestao-escopo-cronograma) |
| 04 | Gestão de Riscos em Projetos e Processos | [`04-gestao-de-riscos`](./04-gestao-de-riscos) |
| 05 | Gestão de Desempenho e Estratégia | [`05-gestao-desempenho-estrategia`](./05-gestao-desempenho-estrategia) |
| 06 | Análise de Processos e Redesenho | [`06-analise-processos-redesenho`](./06-analise-processos-redesenho) |
| 07 | Scrum e Outras Metodologias Ágeis | [`07-scrum-metodologias-ageis`](./07-scrum-metodologias-ageis) |
| 08 | User Experience e Design Thinking | [`08-ux-design-thinking`](./08-ux-design-thinking) |
| 09 | Fundamentos de BPM, VMO e Gestão da Mudança | [`09-bpm-vmo-gestao-mudanca`](./09-bpm-vmo-gestao-mudanca) |
| 10 | Inteligência Artificial e Data Analytics em Projetos e Processos | [`10-ia-data-analytics`](./10-ia-data-analytics) |
| 11 | Modelagem de Processos com BPMN | [`11-modelagem-processos-bpmn`](./11-modelagem-processos-bpmn) |
| 12 | Tendências, Inovação e Criatividade em Projetos e Processos | [`12-tendencias-inovacao-criatividade`](./12-tendencias-inovacao-criatividade) |

## Estrutura do repositório

Cada disciplina segue o mesmo padrão de organização interna, para manter consistência e facilitar a navegação:

```
pos-graduacao/
├── README.md
├── 01-fundamentos-gerenciamento-projetos/
│   ├── README.md
│   ├── anotacoes/
│   ├── exercicios/
│   └── projetos/
├── 02-gestao-pessoas-comunicacao-motivacao/
│   └── ...
├── 03-gestao-escopo-cronograma/
│   └── ...
├── 04-gestao-de-riscos/
│   ├── README.md
│   ├── anotacoes/
│   ├── exercicios/
│   └── projetos/
│       └── dashboard-gerenciamento-riscos/
│           ├── README.md
│           ├── dashboard-riscos-construcao.html
│           └── assets/
│               ├── anexo-1-identificacao-riscos.png
│               ├── anexo-2-atitude-frente-riscos.png
│               ├── anexo-3-mapa-de-riscos.png
│               └── anexo-4-registro-riscos-simplificado.png
├── ...
└── 12-tendencias-inovacao-criatividade/
    └── ...
```

### Padrão de subpastas por disciplina

- **`anotacoes/`** — resumos, mapas mentais e anotações de aula (Markdown ou PDF).
- **`exercicios/`** — listas e atividades práticas propostas durante o módulo.
- **`projetos/`** — entregas maiores e estudos de caso, cada um em sua própria subpasta com um `README.md` explicando o contexto, o enunciado e como executar/visualizar o material.

Disciplinas sem produção de conteúdo em determinada categoria podem omitir a subpasta correspondente — a estrutura é um guia, não uma obrigação rígida.

## Sobre o projeto de Gestão de Riscos

A disciplina **Gestão de Riscos em Projetos e Processos** inclui um dashboard interativo de gerenciamento de riscos aplicado a um estudo de caso de construção civil (obra residencial), disponível em [`04-gestao-de-riscos/projetos/dashboard-gerenciamento-riscos`](./04-gestao-de-riscos/projetos/dashboard-gerenciamento-riscos).

O dashboard é um arquivo HTML único (sem dependências de build), que implementa:

- **Mapa de Riscos 5×5** interativo, com os riscos posicionados por arrasto (drag-and-drop) e recálculo automático de nível.
- **Identificação dos Riscos**, **Atitude Frente aos Riscos** e **Registro de Riscos Simplificado**, seguindo os anexos fornecidos no enunciado do estudo de caso.
- Seleção automática dos 3 riscos de maior severidade para o registro simplificado.

Para visualizar, basta abrir o arquivo `.html` diretamente no navegador — não é necessário nenhum servidor ou instalação.

## Como usar este repositório

1. Clone o repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/pos-graduacao.git
   ```
2. Navegue até a disciplina de interesse.
3. Arquivos `.html` (como dashboards) podem ser abertos diretamente no navegador; arquivos `.md` podem ser lidos no próprio GitHub ou em qualquer editor Markdown.

## Autor

Phillip.

## Licença

Uso pessoal e acadêmico. Sinta-se à vontade para consultar o conteúdo como referência, mas trabalhos avaliativos individuais não devem ser copiados diretamente.
