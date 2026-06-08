# Design System Rigal Engenharia

Sistema visual e verbal para uma empresa de engenharia que precisa transmitir rigor tecnico, previsibilidade e confianca para contratos de maior valor, incluindo poder publico, empresas, incorporadoras/incubadoras e clientes particulares que buscam uma obra conduzida com seguranca.

## 1. Essencia Da Marca

**Posicionamento**
Rigal Engenharia e Construcao deve ser percebida como uma parceira tecnica para obras que exigem responsabilidade, controle e acabamento. O visual precisa parecer institucional o bastante para conversar com prefeituras e serio o bastante para reduzir o medo natural de quem esta prestes a investir alto em uma obra.

**Promessa central**
Engenharia com controle tecnico para transformar projetos em obras bem conduzidas, com previsibilidade, criterio e confianca.

**Percepcao desejada**
- Solida, tecnica e confiavel.
- Premium, mas sem ostentacao.
- Proxima, mas nunca informal demais.
- Moderna, mas com cara de engenharia real, nao de startup generica.

**Principios visuais**
- **Precisao:** alinhamentos, grids, linhas finas e proporcoes claras.
- **Controle:** hierarquia forte, pouco ruido visual e secoes bem delimitadas.
- **Confiança:** fotos reais, provas concretas e linguagem objetiva.
- **Valor:** dourado usado com moderacao, como assinatura de autoridade.

## 2. Publicos E Direcao De Conversao

**Publicos principais**
- Orgaos publicos, como prefeituras e secretarias.
- Empresarios que precisam reformar, expandir ou construir com risco controlado.
- Incubadoras, empresas e instituicoes que precisam de obra funcional e documentada.
- Clientes particulares de ticket alto que valorizam acabamento, acompanhamento e responsabilidade tecnica.

**Medos que o design deve reduzir**
- Obra atrasar.
- Orcamento sair do controle.
- Contratar uma equipe sem responsabilidade tecnica.
- Nao entender o andamento da obra.
- Ter retrabalho, improviso ou acabamento abaixo do esperado.

**Mensagem que deve aparecer na landing page**
Nao vender apenas "obra". Vender conducao tecnica, previsibilidade, responsabilidade e uma experiencia mais segura para quem nao pode errar na escolha da construtora.

## 3. Sistema De Cores

### Paleta Principal

| Token | Hex | Papel |
| --- | --- | --- |
| Azul Rigal | `#0E325B` | Cor principal. Fundos institucionais, botoes primarios, titulos fortes e overlays sobre fotos. |
| Ouro Engenharia | `#B88917` | Acento premium. Linhas, icones, divisores, numeradores e detalhes de autoridade. |
| Branco | `#FFFFFF` | Base limpa, respiro, fundos de conteudo e contraste. |
| Dourado Claro | `#F0BE43` | Destaques pontuais, hover, indicadores e pequenos elementos de conversao. |

### Paleta Expandida

| Nome | Hex | Uso recomendado |
| --- | --- | --- |
| Azul 950 | `#061A31` | Hero escuro, rodape, overlays densos e textos sobre dourado claro. |
| Azul 900 | `#0B2748` | Variacao profunda para faixas e navegacao. |
| Azul 800 | `#0E325B` | Principal da marca. |
| Azul 700 | `#164876` | Estados de hover e superficies tecnicas. |
| Azul 100 | `#EAF0F7` | Fundos suaves e blocos de informacao. |
| Ouro 700 | `#8C650E` | Texto dourado em fundo claro quando `#B88917` ficar pouco contrastado. |
| Ouro 600 | `#B88917` | Acento principal. |
| Ouro 400 | `#D6A72D` | Suporte para graficos, tags e detalhes. |
| Ouro 300 | `#F0BE43` | Destaque luminoso, sem virar fundo dominante. |
| Ouro 100 | `#FFF4D7` | Alertas suaves e fundos de pequenas chamadas. |
| Grafite | `#151A1F` | Texto principal em fundos claros. |
| Aco | `#52606D` | Texto secundario, legendas e metadados. |
| Concreto | `#EEF1F4` | Fundos frios e divisores de pagina. |
| Linha | `#D7DEE7` | Bordas, tabelas e separadores. |

### Proporcao De Uso

Para a landing page, a composicao deve seguir esta proporcao aproximada:

- 50% a 60% branco e concreto claro.
- 25% a 30% azul profundo.
- 8% a 12% ouro envelhecido.
- 3% a 5% dourado claro.
- 5% grafite e tons de apoio.

O ponto importante: **o amarelo/dourado nao deve dominar a pagina**. Em engenharia premium, ele funciona melhor como sinal de precisao e valor.

### Regras De Contraste

- Texto branco em `#0E325B`: aprovado para titulos e corpo.
- Texto azul `#0E325B` em `#F0BE43`: aprovado e excelente para CTA claro.
- Texto branco em `#B88917`: evitar em textos pequenos. Use apenas para elementos grandes ou troque por `#061A31`.
- Texto `#B88917` em branco: usar com cautela. Para textos pequenos, prefira `#8C650E`.

## 4. Tipografia

### Fontes

**Titulos:** Michroma  
**Texto:** Manrope

Michroma tem uma presenca tecnica, geometrica e futurista. Ela deve ser usada como assinatura, nao como fonte de tudo. Manrope traz clareza, leitura confortavel e equilibrio comercial.

### Hierarquia Recomendada

| Elemento | Fonte | Desktop | Mobile | Peso | Line-height |
| --- | --- | --- | --- | --- | --- |
| Hero H1 | Michroma | 44-58px | 32-38px | 400 | 1.08 |
| H2 | Michroma | 30-38px | 26-30px | 400 | 1.16 |
| H3 | Manrope | 21-24px | 19-22px | 700 | 1.25 |
| Corpo grande | Manrope | 18-20px | 17-18px | 400/500 | 1.65 |
| Corpo | Manrope | 16px | 16px | 400/500 | 1.65 |
| Legenda | Manrope | 13-14px | 13px | 500 | 1.45 |
| Numeros/metricas | Michroma | 32-48px | 28-36px | 400 | 1 |

**Regras**
- Nao usar Michroma em paragrafos longos.
- Usar caixa alta apenas em labels, tags e pequenos elementos.
- Manter letter-spacing em `0`, especialmente em botoes e textos pequenos.
- Titulos podem ser quebrados em linhas curtas para parecerem mais arquitetonicos.

## 5. Grid, Espacamento E Layout

**Grid**
- Desktop: 12 colunas, max-width entre 1180px e 1240px.
- Tablet: 8 colunas.
- Mobile: 4 colunas.

**Sistema de espacamento**
Base de 8px:
`4, 8, 12, 16, 24, 32, 48, 64, 80, 96, 128`

**Secoes**
- Hero: altura minima de 680px no desktop, com indicio da proxima secao visivel.
- Secoes principais: padding vertical de 88px a 120px.
- Mobile: padding vertical de 56px a 80px.

**Raio de borda**
- Elementos pequenos: 4px.
- Cards e formularios: 6px.
- Maximo geral: 8px.

Esse limite mantem a linguagem mais precisa e menos "app casual".

## 6. Composicoes Visuais

### Composicao 1: Institucional Premium

Uso: hero, apresentacao da empresa, rodape.

- Fundo azul `#061A31` ou foto real com overlay azul.
- H1 em branco com Michroma.
- Linha fina em ouro `#B88917`.
- CTA primario em `#F0BE43` com texto `#061A31`.
- Provas logo abaixo do texto: "Prefeitura de Sao Paulo", "Prefeitura de Sao Jose dos Campos", "Empresas e obras particulares".

### Composicao 2: Engenharia Documentada

Uso: metodo, processo, etapas e acompanhamento.

- Fundo branco ou concreto `#EEF1F4`.
- Titulos em azul.
- Numeros em Michroma dourado.
- Cards com borda fina `#D7DEE7`.
- Linhas horizontais e verticais lembrando desenho tecnico.

### Composicao 3: Case De Obra

Uso: portfolio, antes/depois e provas.

- Foto grande com proporcao 16:9 ou 4:3.
- Tarja inferior azul com nome do projeto.
- Tags pequenas: "Comercial", "Residencial", "Fachada", "Reforma", "Execucao".
- Botao secundario: "Ver detalhes da obra".
- Evitar muitos filtros. A prova precisa parecer real.

### Composicao 4: Conversao Direta

Uso: formulario e CTA final.

- Fundo azul profundo.
- Formulario branco com borda 1px e raio 6px.
- Campos amplos, labels objetivos e CTA em dourado claro.
- Microcopy abaixo do botao: "Retorno para avaliacao inicial e orientacao tecnica."

## 7. Fotografia E Assets

O acervo atual tem fotos reais de obras, fachadas, interiores e entregas. Isso e uma vantagem forte para credibilidade.

**Tratamento recomendado**
- Corrigir perspectiva quando a foto estiver muito inclinada.
- Aumentar levemente contraste e nitidez.
- Reduzir saturacao em 5% a 15% para ficar mais institucional.
- Aplicar overlay azul entre 55% e 72% quando houver texto sobre imagem.
- Usar fotos de obra finalizada como hero quando possivel.

**Recortes**
- Hero: 16:9 ou 21:9, com area livre para texto.
- Cards de cases: 4:3.
- Galeria mobile: 1:1 ou 4:5.
- Antes/depois: pares com mesma proporcao.

**Evitar**
- Fotos muito escuras sem correcao.
- Imagens com muitos objetos pessoais ou bagunca visual.
- Zoom excessivo em detalhes que nao contam uma historia.
- Banco de imagem generico de capacete e planta se houver foto real da Rigal.

## 8. Componentes

### Navegacao

- Fundo transparente sobre hero ou branco apos scroll.
- Logo a esquerda.
- Links curtos: "Servicos", "Metodo", "Cases", "Contato".
- CTA de navegacao: "Solicitar avaliacao".

### Botoes

**Primario**
- Fundo `#F0BE43`.
- Texto `#061A31`.
- Altura: 52px a 56px.
- Peso: Manrope 800.
- Raio: 4px ou 6px.
- Uso: CTA principal.

Texto recomendado:
- "Solicitar avaliacao tecnica"
- "Falar sobre minha obra"
- "Agendar conversa tecnica"

**Secundario**
- Fundo transparente.
- Borda `#B88917`.
- Texto `#FFFFFF` em fundo azul ou `#0E325B` em fundo claro.
- Uso: portfolio, metodo, cases.

**Terciario**
- Link com sublinhado tecnico ou seta curta.
- Uso: "Ver case", "Entender processo".

### Cards

Cards devem ser discretos, com borda fina. Evitar sombra pesada.

- Fundo: branco.
- Borda: `1px solid #D7DEE7`.
- Raio: 6px.
- Padding: 24px a 32px.
- Titulo em Manrope 700.
- Icone linear em ouro.

### Blocos De Prova

Usar metricas ou credenciais com visual contido:

- "Atuacao com prefeituras"
- "Obras comerciais e residenciais"
- "Acompanhamento tecnico"
- "Execucao e reforma com responsabilidade"

Quando houver numeros reais, substituir por metricas especificas. Nao inventar quantidade de obras, anos ou valores.

### Formularios

Campos essenciais:
- Nome.
- WhatsApp.
- Cidade.
- Tipo de obra.
- Estagio: ideia, projeto, orcamento, obra em andamento.
- Mensagem.

Visual:
- Labels visiveis.
- Campos com altura minima de 48px.
- Borda `#C9D3DF`.
- Estado focus com borda `#B88917` e sombra sutil.

### Linha Do Processo

Etapas sugeridas:
1. Avaliacao inicial.
2. Leitura tecnica do escopo.
3. Planejamento e proposta.
4. Execucao acompanhada.
5. Entrega e fechamento.

Cada etapa deve ter numero em Michroma, titulo curto e texto claro.

## 9. Voz E Copy

**Tom**
Formal, direto e consultivo. Deve parecer uma conversa com um engenheiro que entende a responsabilidade do investimento.

**Palavras-chave**
- Controle tecnico.
- Previsibilidade.
- Responsabilidade.
- Execucao.
- Obra bem conduzida.
- Criterio.
- Acompanhamento.
- Confianca.

**Evitar**
- "Somos os melhores".
- "Qualidade garantida" sem prova.
- "Transformamos sonhos" como mensagem principal.
- Excesso de termos emotivos.
- Promessas absolutas de prazo e custo.

### Hero Copy Para Landing Page

**Opcao principal**

Titulo:  
Engenharia para obras que exigem confianca do projeto a entrega.

Subtitulo:  
A Rigal conduz reformas e construcoes com criterio tecnico, planejamento e acompanhamento proximo para reduzir incertezas em cada etapa da obra.

CTA primario:  
Solicitar avaliacao tecnica

CTA secundario:  
Ver obras realizadas

**Opcao mais premium**

Titulo:  
Sua obra conduzida com rigor tecnico e previsibilidade.

Subtitulo:  
Da avaliacao inicial a execucao, a Rigal estrutura cada decisao para proteger o investimento e entregar uma obra mais segura.

**Opcao institucional**

Titulo:  
Engenharia e construcao para clientes que nao podem errar na execucao.

Subtitulo:  
Atuamos em obras publicas, comerciais e particulares com responsabilidade tecnica, comunicacao clara e foco em resultado.

## 10. Estrutura Recomendada Para A Landing Page

1. **Hero com prova imediata**  
   Foto real de obra, headline forte, CTA e credenciais.

2. **Barra de confianca**  
   "Atendimento a orgaos publicos", "Obras comerciais", "Reformas e construcoes", "Acompanhamento tecnico".

3. **Problema**  
   Mostrar que obra de alto valor exige controle, nao improviso.

4. **Servicos**  
   Reformas, construcoes, fachadas, adequacoes comerciais, acompanhamento tecnico.

5. **Metodo Rigal**  
   Processo em 5 etapas para reduzir incerteza.

6. **Cases reais**  
   Cards com fotos do acervo atual e contexto de cada obra.

7. **Por que a Rigal**  
   Responsabilidade tecnica, comunicacao, planejamento, execucao e acabamento.

8. **FAQ de objecoes**  
   Prazo, orcamento, cidades atendidas, tipos de obra, como comeca.

9. **CTA final**  
   Formulario curto com chamada para avaliacao tecnica.

## 11. Direcao Para UI Da Landing Page

**Header**
- Logo sobre azul profundo no hero.
- Ao rolar, fundo branco com borda inferior clara.

**Hero**
- Foto real full-bleed ou ocupando toda a largura.
- Overlay azul.
- Texto alinhado a esquerda.
- H1 com largura maxima de 760px.
- Bloco de prova abaixo do CTA.

**Cards de servico**
- Sem excesso de sombra.
- Icone linear dourado.
- Titulo objetivo: "Reformas comerciais", "Construcao residencial", "Adequacao de fachada".

**Cases**
- Mostrar imagem antes de texto.
- Nome do case em Manrope 700.
- Tags tecnicas.
- Pequena descricao do desafio.

**Formulario**
- Deve parecer seguro e facil.
- Nada de muitos passos no primeiro contato.
- CTA com beneficio especifico.

## 12. Checklist De Consistencia

Antes de publicar qualquer peca da Rigal, conferir:

- O azul principal aparece como ancora visual?
- O dourado esta sendo usado como acento, nao como preenchimento dominante?
- A foto comunica obra real e confianca?
- Existe prova concreta perto do primeiro CTA?
- A tipografia Michroma esta restrita a titulos e numeros?
- Os cards tem borda fina e raio maximo de 8px?
- O texto promete controle e criterio, sem prometer o que nao pode ser garantido?
- O usuario entende em menos de 5 segundos que a Rigal faz engenharia/construcao?

