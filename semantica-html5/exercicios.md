# HTML5 Semântico - Exercícios

## Exercício 1: Blog Pessoal Semântico
Crie um blog com estrutura semântica completa:
- Header com título e navegação
- Main com artigos individuais
- Aside com sidebar (biografia, links)
- Footer com informações de contato
- Use time para datas de publicação

## Exercício 2: Site Institucional
Desenvolva site de empresa usando:
- Navegação principal no header
- Seções para diferentes serviços
- Articles para cases de sucesso
- Aside para depoimentos
- Footer com múltiplas colunas

## Exercício 3: Portal de Notícias
Crie portal jornalístico com:
- Header com logo e menu
- Main com artigos de notícias
- Seções por categoria (esportes, política, etc.)
- Aside com notícias relacionadas
- Time elements para horários de publicação

## Exercício 4: E-commerce Semântico
Desenvolva loja online estruturada:
- Header com carrinho e busca
- Main com grid de produtos
- Articles para produtos individuais
- Aside com filtros e categorias
- Footer com links úteis

## Exercício 5: Documentação Técnica
Crie documentação de API/software:
- Nav com índice de conteúdo
- Articles para diferentes tópicos
- Sections para subtópicos
- Details/summary para FAQs
- Code blocks bem estruturados

## Exercício 6: Portfolio Criativo
Desenvolva portfolio com:
- Header com apresentação pessoal
- Main com galeria de trabalhos
- Articles para projetos individuais
- Aside com habilidades e contato
- Figure/figcaption para imagens

## Exercício 7: Revista Digital
Crie revista online com:
- Header com edição atual
- Nav com seções da revista
- Articles para matérias
- Aside com índice e anúncios
- Time para datas de publicação

## Exercício 8: Plataforma Educacional
Desenvolva curso online:
- Header com progresso do curso
- Nav com módulos e aulas
- Main com conteúdo da aula
- Aside com recursos adicionais
- Footer com certificação

## Exercício 9: Site de Eventos
Crie site para conferência/evento:
- Header com informações do evento
- Nav com programação
- Articles para palestrantes
- Sections para horários
- Address para localização

## Exercício 10: Correção de Código
Converta HTML não semântico para semântico:
```html
<div class="header">
    <div class="titulo">Meu Site</div>
    <div class="menu">
        <div class="link">Home</div>
        <div class="link">Sobre</div>
    </div>
</div>
<div class="conteudo">
    <div class="post">
        <div class="titulo-post">Artigo</div>
        <div class="texto">Conteúdo...</div>
    </div>
    <div class="sidebar">Info adicional</div>
</div>
<div class="rodape">Copyright</div>
```

## Exercício 11: Acessibilidade Avançada
Melhore a acessibilidade usando:
- Landmarks adequados (role quando necessário)
- Heading hierarchy correta
- Skip links para navegação
- Aria-labels quando apropriado
- Alt texts descritivos

## Exercício 12: SEO e Microdata
Otimize para motores de busca:
- Meta tags apropriadas
- Structured data (schema.org)
- OpenGraph tags
- Breadcrumbs semânticos
- URLs semânticas

## Projeto Final: Website Completo
Desenvolva site institucional completo que demonstre:
- Estrutura semântica perfeita
- Múltiplas páginas interligadas
- Diferentes tipos de conteúdo
- Acessibilidade total
- SEO otimizado
- Design responsivo

### Elementos Obrigatórios:
- [ ] `<header>`, `<nav>`, `<main>`, `<footer>`
- [ ] `<article>`, `<section>`, `<aside>`
- [ ] `<h1>`-`<h6>` em hierarquia correta
- [ ] `<time>` para datas
- [ ] `<figure>`/`<figcaption>` para imagens
- [ ] `<address>` para contatos
- [ ] `<details>`/`<summary>` quando apropriado

### Checklist de Qualidade:
- [ ] HTML válido (W3C Validator)
- [ ] Estrutura lógica e hierárquica
- [ ] Acessibilidade (WAVE, axe)
- [ ] SEO otimizado
- [ ] Performance adequada
- [ ] Funciona sem CSS
- [ ] Testado com leitor de tela

### Elementos Semânticos HTML5:
1. **Estruturais**: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
2. **Textuais**: `h1-h6`, `p`, `strong`, `em`, `mark`, `small`, `del`, `ins`
3. **Citações**: `blockquote`, `q`, `cite`
4. **Código**: `code`, `pre`, `kbd`, `samp`, `var`
5. **Tempo**: `time`
6. **Interativos**: `details`, `summary`
7. **Multimídia**: `figure`, `figcaption`
8. **Contato**: `address`

### Dicas de Boas Práticas:
- Use apenas um `<h1>` por página
- `<main>` deve ser único na página
- `<article>` deve poder funcionar independentemente
- `<section>` deve ter um heading
- `<nav>` apenas para navegação principal
- `<aside>` para conteúdo relacionado mas não essencial
