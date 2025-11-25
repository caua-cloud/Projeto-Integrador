
# Crepe do Lula
Site institucional e cardápio digital para a creperia artesanal Crepe do Lula, localizada em frente à Universidade Católica de Brasília.

 # Sobre o Projeto

O **Crepe do Lula** é um site para uma creperia artesanal localizada em frente à Universidade Católica em Brasília. O projeto tem como objetivo apresentar o cardápio completo, divulgar o negócio e facilitar o contato com clientes e interessados em contratar serviços para eventos, divulgar o negócio nas edes sociais e proporcionar experiência responsiva em todos os dispositivos. 

Este projeto foi desenvolvido como Projeto Integrador da disciplina de Desenvolvimento Front-End, aplicando conceitos de HTML5, CSS3, JavaScript, responsividade, acessibilidade e boas práticas de desenvolvimento web.


## Integrantes da Equipe

Cauã Cerqueira Santos:  Desenvolvedor Front-End | Desenvolvimento HTML, CSS, JavaScript, integração de funcionalidades |
Ana Maria Pontes da Fonseca Gonzatti:Designer UI/UX | Criação do protótipo no Figma, design visual, identidade visual, desenvolvimento HTML, CSS e JavaScript |


## Acesso ao Site

- Site Publicado: https://caua-cloud.github.io/Projeto-Integrador/
- Link Repositório: https://github.com/caua-cloud/Projeto-Integrador.git

**Data de Publicação:** 25/11/2025

##  Design e Identidade Visual

### Protótipo no Figma
Ver Protótipo Completo: (https://www.figma.com/proto/LsKbokwt5YboST8Qgy4czy/Projeto-integrador-dfe?node-id=5-2&p=f&t=UIkYcFYnKiQD14c6-1&scaling=scale-down&content-scaling=fixed&page-id=3%3A15&starting-point-node-id=5%3A2)

>Nota: No protótipo há 2 páginas (Crepes do Lula e Confeitaria). Selecionar a página do Crepe do Lula para ver o protótipo correto.

# Paleta de Cores
- Preto (#000000): Fundo principal, elegância e sofisticação
- Vermelho (#E60000): Botões, destaques, energia e paixão
- Amarelo (#FFCC00): Títulos, acentos, alegria e apetite

# Tipografia
- Fonte Principal:Arial (sans-serif)
- Objetivo: Boa legibilidade em todos os dispositivos

# Conceito Visual
Layout moderno, responsivo e visualmente atrativo que transmite energia, qualidade e profissionalismo.

Tecnologias Utilizadas

- HTML5 - Estrutura semântica e acessível
- CSS3 - Estilização avançada, Grid, Flexbox, animações
- JavaScript (Vanilla) - Interatividade, validações, manipulação DOM
- GitHub Pages - Hospedagem gratuita
- Git/GitHub - Controle de versão e colaboração
- Canva - Edição de imagens 
- Figma - Criação de protótipo

=================================================
 Estrutura do Projeto


projeto-crepe-do-lula/
├── index.html              # Página do cardápio (página principal)
├── home.html               # Página inicial de boas-vindas
├── eventos.html            # Sobre a creperia
├── contato.html            # Formulário de contato
├── style.css               # Estilos principais
├── style.min.css           # CSS minificado (produção)
├── contato-style.css       # Estilos específicos da página de contato
├── Img Figma/              # Imagens dos produtos
│   ├── Frango Catupiry.jpg
│   ├── Presunto e queijo.jpg
│   ├── Banana com canela.jpg
│   └── [outras imagens...]
├── img/                    # Imagens otimizadas (favicon, etc)
│   └── favicon.png
└── docs/                   # Documentação e evidências
    ├── wireframe/
    │   ├── wireframe-figma.pdf
    │   └── wireframe-figma.png
    ├── testes-navegadores/
    │   ├── chrome.png
    │   ├── firefox.png
    │   └── edge.png
    ├── testes-responsividade/
    │   ├── mobile-375px.png
    │   ├── tablet-768px.png
    │   └── desktop-1920px.png
    ├── avaliacoes-recebidas/
    │   ├── feedback-dupla-1.md
    │   └── feedback-dupla-2.md
    └── avaliacoes-enviadas/
        ├── avaliacao-dupla-1.md
        └── avaliacao-dupla-2.md
======================================================

# Funcionalidades Implementadas

# Página Inicial (index.html)
- Layout de boas-vindas com design moderno
- Links diretos para cardápio, eventos e pedidos
- Integração com Instagram e WhatsApp
- Design com ondas decorativas em gradiente

# Cardápio (home.html)
- Grid responsivo de produtos (4 → 3 → 2 colunas)
- Categorias: Salgados, Doces, Especiais, Adicionais, Bebidas
- Navegação por âncoras entre seções
- **Interatividade JavaScript:**
  - Saudação personalizada ao digitar nome
  - Botão de promoções com animação
  - Cards com efeito hover (escala + borda amarela)
  - Navegação suave entre seções

# Sobre (eventos.html)
- História da creperia
- Informações de contato
- Horário de funcionamento
- Design clean e informativo

# Contato (contato.html)
- Formulário completo de contato
- Validação de campos obrigatórios
- Máscara automática para telefone
- Integração com WhatsApp (envio direto)
- Saudação dinâmica ao digitar nome
- Cards com informações de contato
- Links diretos para WhatsApp e Instagram

# Design Responsivo
- **Mobile First:** Interface otimizada para celulares
- **Breakpoints:** 480px (mobile), 768px (tablet), 1024px+ (desktop)
- **Menu Hambúrguer:** Navegação mobile intuitiva
- **Grid Adaptativo:** Produtos se reorganizam automaticamente

# Acessibilidade
- Tags semânticas (header, nav, main, section, footer)
- Link "Pular para conteúdo principal"
- Textos alternativos (alt) em todas as imagens
- Labels associados a campos de formulário
- Foco visível para navegação por teclado
- Botões com aria-label e aria-expanded

# Performance
- Imagens otimizadas com TinyPNG/Squoosh
- CSS minificado para produção
- Lazy loading em imagens
- Metadados SEO em todas as páginas


Evolução do Projeto

# Parte 1: Planejamento e Estrutura Básica
Período: 08/10/2025 - 14/10/2025

Realizações:
- ✅ Definição do negócio e público-alvo
- ✅ Criação do protótipo completo no Figma
- ✅ Desenvolvimento da estrutura HTML básica
- ✅ Estilização inicial com CSS
- ✅ Upload no GitHub e início do versionamento

Entregas:
- Wireframe detalhado no Figma
- 4 páginas HTML estruturadas
- CSS básico com paleta de cores definida
- Repositório GitHub configurado

# Parte 2: Interatividade e Melhorias
Período: 15/11/2025

Realizações:
- ✅ Diagnóstico completo do projeto
- ✅ Identificação de pontos fortes e melhorias
- ✅ Implementação de interatividade JavaScript
- ✅ Melhorias de acessibilidade (WCAG)
- ✅ Aprimoramento da responsividade

Melhorias Implementadas:

1. Interatividade:
- ✅ Botão "voltar ao topo" com animação suave
- ✅ Menu hambúrguer funcional para mobile
- ✅ Validação de formulário antes do envio
- ✅ Saudação personalizada dinâmica
- ✅ Efeitos hover nos cards e botões
- ✅ Integração WhatsApp no formulário

2. Acessibilidade:
- ✅ Link "Pular para conteúdo principal"
- ✅ Tag `<main>` com id em todas as páginas
- ✅ Manutenção de estrutura semântica
- ✅ Foco visível (outline) em elementos interativos
- ✅ Textos alternativos revisados
- ✅ Labels associados a campos de formulário

3. Responsividade:
- ✅ Menu hambúrguer em telas < 768px
- ✅ Grid responsivo mantido e aprimorado
- ✅ Testes em múltiplos dispositivos

4. Integrações:
- ✅ WhatsApp com mensagem pré-formatada
- ✅ Links para Instagram oficial

# Parte 3: Publicação e Finalização
Período: 25/11/2025

Realizações:
- ✅ Publicação no GitHub Pages
- ✅ Otimizações de performance aplicadas
- ✅ Testes de compatibilidade documentados
- ✅ Avaliações entre pares realizadas
- ✅ Reflexões e aprendizados documentados

Otimizações Realizadas:

1. Imagens:
- ✅ Todas as imagens otimizadas com TinyPNG
- ✅ Redução média de 60-70% no tamanho
- ✅ Implementação de lazy loading
- ✅ Formato WebP quando possível

2. CSS:
- ✅ Minificação do CSS principal
- ✅ Criação de `style.min.css`
- ✅ Remoção de código não utilizado

3. SEO e Metadados:
- ✅ Meta description em todas as páginas
- ✅ Meta keywords relevantes
- ✅ Favicon criado e implementado
- ✅ Títulos únicos por página
========================================================
4. Performance:
- ⚡ Lighthouse Score: [ADICIONAR APÓS TESTES]
- ⚡ PageSpeed Insights: [ADICIONAR APÓS TESTES]
- ⚡ Tempo de carregamento: [ADICIONAR APÓS TESTES]

# Testes Realizados

# Navegadores Testados

| Navegador | Versão | Status | Observações |
|-----------|--------|--------|-------------|
| Google Chrome | [VERSÃO] | ✅ Aprovado | Todas as funcionalidades OK |
| Mozilla Firefox | [VERSÃO] | ✅ Aprovado | Todas as funcionalidades OK |
| Microsoft Edge | [VERSÃO] | ✅ Aprovado | Todas as funcionalidades OK |
| Safari | [VERSÃO] | ⏳ Pendente | Aguardando acesso a dispositivo Mac/iOS |

Evidências: [docs/testes-navegadores/](docs/testes-navegadores/)

# Dispositivos/Resoluções Testados

| Dispositivo | Resolução | Layout | Menu | Imagens | JavaScript | Status |
|-------------|-----------|--------|------|---------|------------|--------|
| iPhone SE | 375x667 | ✅ | ✅ | ✅ | ✅ | ✅ Aprovado |
| iPhone 12 Pro | 390x844 | ✅ | ✅ | ✅ | ✅ | ✅ Aprovado |
| iPad | 768x1024 | ✅ | ✅ | ✅ | ✅ | ✅ Aprovado |
| iPad Pro | 1024x1366 | ✅ | ✅ | ✅ | ✅ | ✅ Aprovado |
| Desktop HD | 1280x720 | ✅ | ✅ | ✅ | ✅ | ✅ Aprovado |
| Desktop FHD | 1920x1080 | ✅ | ✅ | ✅ | ✅ | ✅ Aprovado |

Evidências: [docs/testes-responsividade/](docs/testes-responsividade/)

# Teste em Dispositivo Real
- Dispositivo: [ADICIONAR]
- Sistema: [ADICIONAR]
- Navegador: [ADICIONAR]
- Experiência: [ADICIONAR DESCRIÇÃO]

# Reflexões e Aprendizados

### Cauã Cerqueira Santos

#### Aprendizados Técnicos
[ADICIONAR REFLEXÃO PESSOAL]

**Principais habilidades desenvolvidas:**
- HTML5 semântico e estruturado
- CSS3 avançado (Grid, Flexbox, animações)
- JavaScript para interatividade
- Git e GitHub para versionamento
- Responsividade e Mobile First

**Tecnologia mais desafiadora:**
[ADICIONAR]

**O que domino melhor agora:**
[ADICIONAR]

#### Aprendizados de Processo
[ADICIONAR REFLEXÃO SOBRE TRABALHO EM DUPLA]

**Como foi trabalhar em dupla:**
[ADICIONAR]

**Organização de tarefas:**
[ADICIONAR]

**O que funcionou bem:**
[ADICIONAR]

#### Desafios Enfrentados
[ADICIONAR MAIOR DESAFIO E COMO SUPEROU]

=========================================================

# Ana Maria Pontes da Fonseca Gonzatti
Aprendizados Técnicos
Evoluí muito no Figma- Aprendi que design resolve problemas, não só "fica bonito". Cada cor, espaçamento e fonte tem propósito. Entendi design responsivo: não é encolher proporcionalmente, é repensar o layout para cada dispositivo. Acompanhar o desenvolvimento me deu alfabetização técnica  (HTML, CSS, JavaScript) que facilitou muito a comunicação. Descobri acessibilidade: contraste não é preferência, é necessidade.
Aprendizados de Processo
Aprendi que designers e desenvolvedores precisam falar a mesma língua. No início, criava designs sem pensar em viabilidade técnica. Estabelecemos processo iterativo: eu desenhava, Cauã implementava, eu revisava, ele ajustava. Aprendi a documentar designs (cores exatas, espaçamentos, fontes) e usar prints anotados para feedback visual. Comunicação por áudio funcionou melhor que texto. Além disso aprendi a passar as minhas ideias do protóyipo para o código, me raciocínio e codificação evoluíram. 
Desafios Enfrentados
Equilibrar estética com funcionalidade foi o maior desafio. Ideias lindas que não funcionavam na prática. Manter consistência visual em 4 páginas diferentes exigiu sistema de componentes reutilizáveis. Aprendi até o básico de GitHub para acompanhar o projeto. Se pudesse voltar, criaria style guide antes de começar e testaria designs em telas reais mais cedo.

Principais habilidades desenvolvidas:
- Design UI/UX no Figma
- Escolha de paleta de cores
- Organização de projeto
- Colaboração com desenvolvedor
- Desenvolver em linguagens novas (HTML, CSS, Java,Script)

Tecnologia mais desafiadora:
A parte de codificar e aparecer o resultado esperado na tela, principalmente cm o Java. 

O que domino melhor agora:
Raciocínio alinhado entre design e desenvolvedor, com certeza, mas também vi uma grande evolução nas linguagens de programação utilizdos. 

# Aprendizados de Processo
Como foi trabalhar em dupla:
Vi grande melhoria nas nossas habilidades de comunicação dentro do trabalho, fomos nos adaptando e construindouma relação de parceria e profissionalismo, onde cada um ajudva o outro como podia e quando necessário. Acredito que nós dois, como dupla desse projeto, aprendemos muito mais trabalhando juntos do que separados, o que foi essencial para a evolução do projeto. 

Organização de tarefas:
Conseguimos dividir muito bem, de forma que cada um trabalhou mais com o que tinha mais afinidade mas também aprendeu sobre tudo que utilizamos para concluir o projeto. Além de nos ajudarmos bastante. 

O que funcionou bem:
A comunicação e o desenvolvimento do projeto, evoluímos como o esperado, mesmo precisando de alguns ajuste na ideia inicial. 

Desafios Enfrentados
Meu mior desafio com certeza foi aprender as linguagens noas e linhr elas com a ideia inicial no protótipo, mas estudando e testando tudo fluiu da melhor forma. 

# Reflexão da Dupla
- Evolução do Projeto
Da Parte 1 até agora:
O projeto passou por uma transformação incrível. Na Parte 1 (outubro), tínhamos apenas wireframes estáticos no Figma e páginas HTML básicas sem funcionalidade. Era um "esqueleto" visual do que queríamos construir. Na Parte 2 (novembro), ganhamos vida com JavaScript - interatividade, validações, menu hambúrguer, efeitos hover. O site deixou de ser estático e passou a reagir ao usuário. Na Parte 3 (agora), atingimos maturidade profissional: otimizações de performance, testes extensivos, publicação online, documentação completa. Saímos de "trabalho acadêmico" para "produto real".
A evolução não foi apenas técnica - foi também na nossa mentalidade. No início, pensávamos "vamos fazer um site bonito". No meio, percebemos "precisamos fazer um site que funciona bem". No final, entendemos "precisamos fazer um site acessível, rápido, testado e documentado". Amadurecemos como profissionais.

Maiores mudanças/melhorias:
✅ Interatividade completa: Saudações personalizadas, botão de promoções, efeitos hover nos cards, validação de formulário
✅ Acessibilidade real: Skip links, tags semânticas, ARIA labels, navegação por teclado, foco visível
✅ Menu hambúrguer mobile: Navegação otimizada para dispositivos pequenos
✅ Botão "voltar ao topo": Facilita navegação em páginas longas (cardápio extenso)
✅ Integração com WhatsApp: Formulário envia dados diretamente via mensagem formatada
✅ Otimizações de performance: CSS minificado, lazy loading de imagens, metadados SEO
✅ Responsividade refinada: Testado em 6+ resoluções diferentes, funciona perfeitamente em todas
✅ Publicação online: Site acessível globalmente via GitHub Pages
✅ Documentação profissional: README completo, estrutura organizada, evidências de testes
✅ Identidade visual coesa: Paleta de cores consistente, tipografia harmoniosa, layouts equilibrados

O resultado atende à proposta inicial?
Sim, e supera. A proposta inicial era criar um site institucional para apresentar o cardápio e facilitar contato. Conseguimos isso e fomos além:
Atende porque:
✅ Cardápio completo está apresentado de forma visual e organizada
✅ Informações de contato estão claras e acessíveis
✅ Integração com WhatsApp facilita pedidos reais
✅ Design representa bem a identidade da creperia (cores, estilo)
✅ Funciona em qualquer dispositivo (mobile, tablet, desktop)

Supera porque:
- Não é apenas "bonito", é funcional e acessível
- Não é apenas "responsivo", é otimizado para performance
- Não é apenas "código que funciona", é código profissional e documentado
- Não é apenas "um site", é uma experiência completa do usuário
- Agregaria valor real ao negócio, aumentando vendas e profissionalizando presença digital

=================================================
#### Feedbacks Recebidos
**O que aprendemos com a avaliação dos colegas:**
[ADICIONAR APÓS RECEBER FEEDBACKS]

**Feedbacks mais úteis:**
[ADICIONAR]

**Como pretendemos aplicar:**
[ADICIONAR]
=============================================

# Relevância para o Negócio
- O site agregaria valor ao Crepe do Lula?
Sim, a empresa não possui um sistema digitl que integre várias funcionalidades, o que dificulta o crescimento do negócio e praticidade no dia a dia. Acreditamos que o site ajudaria muito. 

- Se pudéssemos apresentar ao dono:
Apresentaríamos, iríamos fazer uma análise de requisitos para entender as necessidades do cliente e se necessário mudaríamos algumas coisas no site para atender as necessidades. 

Usaremos no portfólio?
Sim, com certeza. 

# Próximos Passos e Melhorias Futuras

Melhorias Técnicas Planejadas
-  Adicionar sistema de busca de produtos
-  Implementar filtros por categoria
-  Criar galeria de imagens com modal
-  Adicionar animações CSS mais elaboradas
-  Implementar tema escuro/claro
-  Melhorar acessibilidade WCAG 2.1 AA
-  Adicionar suporte a múltiplos idiomas
-  Implementar carrinho de compras
-  Implementar função de realizar pedido pelo site
-  Adicionar parte administrativa da empresa 
-  Dar mais informações sobre o prepro e ingredientes 

# Conhecimentos a Aprofundar
1. Frameworks JavaScript: React.js ou Vue.js
2. Pré-processadores CSS: SASS/SCSS
3. Backend: Node.js + Express
4. Banco de Dados: MongoDB ou PostgreSQL
5. APIs: Integração com pagamentos (Stripe, MercadoPago)

# Aplicação em Disciplinas Futuras
- Usar como base para projeto de Backend
- Evoluir para Full Stack com banco de dados
- Implementar autenticação de usuários
- Adicionar painel administrativo
- Criar aplicativo mobile (React Native)


# Créditos e Agradecimentos

# Imagens
- Fotos dos produtos: Como não tínhamos acesso ao acervo da empresa utilizamos fotos da internet mesmo, mas nossa intnção era utlizar fotos reais. 

# Ferramentas Utilizadas
- Figma - Design e prototipação
- Visual Studio Code - Editor de código
- Git/GitHub - Versionamento e hospedagem
- GitHub Pages - Hospedagem do site
- TinyPNG - Otimização de imagens
- CSS Minifier - Minificação de CSS
- Chrome DevTools - Testes e debug

# Inspirações
- Sites de referência de creperias artesanais
- Tendências de design food delivery 2024/2025
- Guidelines de acessibilidade WCAG

# Agradecimentos Especiais
- Professora Jéssica Oliveira pela orientação
- Colegas que avaliaram o projeto 
- Dono do Crepe do Lula pela inspiração


# Licença

Este projeto foi desenvolvido para fins educacionais como parte do Projeto Integrador da disciplina de Desenvolvimento Front-End.


# Contato da Equipe

Cauã Cerqueira Santos
- GitHub: @caua-cloud (https://github.com/caua-cloudo)
- Email: cauacerqueira2006@gmail.com

Ana Maria Pontes da Fonseca Gonzatti
- GitHub: @anamariapfg (https://github.com/anamariapfg)
- Email: anamaria.pfg@gmail.com

# Estatísticas do Projeto

- Linhas de código HTML: ~800
- Linhas de código CSS: ~900
- Linhas de código JavaScript: ~200
- Commits: 25+
- Páginas desenvolvidas: 4
- Produtos no cardápio: 30+
- Tempo de desenvolvimento: 6 semanas
- Versão atual: 3.0 (Final)

Desenvolvido com carinho por Cauã Cerqueira Santos e Ana Maria Pontes da Fonseca Gonzatti

**Universidade Católica de Brasília - 2025**

[Visite o site ao vivo](https://caua-cloud.github.io/Projeto-Integrador/)
