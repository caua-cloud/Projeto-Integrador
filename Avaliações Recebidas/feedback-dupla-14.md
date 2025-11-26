📄 Avaliação do Projeto “Crepe do Lula” (Projeto-Integrador)
Nome do Projeto: Crepe do Lula
Dupla Avaliada: Cauã Cerqueira Santos & Ana Maria Pontes da Fonseca Gonzatti
Link GitHub: https://github.com/caua-cloud/Projeto-Integrador (GitHub)
Link GitHub Pages: https://caua-cloud.github.io/Projeto-Integrador/ (GitHub)
Avaliadores: Cauã Cerqueira Santos e Ana Maria Maria Pontes da Fonseca Gonzatti 
Data da Avaliação: 25/11/2025
________________________________________
1️ Estrutura e Organização do Código (15 pontos)
Pontuação atribuída: 14 / 15
Justificativa:
•	A estrutura de pastas é clara e bem organizada — há pastas para documentação (docs/), imagens (Img Figma/), e os arquivos principais (HTML, CSS). (GitHub)
•	A nomenclatura é consistente e descritiva (ex: home.html, eventos.html, contato.html, style.css). (GitHub)
•	HTML parece bem estruturado e legível (usa HTML5, tags semânticas). No README é explícito que HTML5 e CSS3 foram usados. (GitHub)
•	CSS e JS estão separados (vê-se style.css, e não inline) e há também versão minificada (style.min.css). (GitHub)
•	README existe e é bastante detalhado, com descrição, tecnologias, estrutura, funcionalidades, etc. (GitHub)
Sugestões de melhoria:
•	Poderia haver um pouco mais de modularização, por exemplo separando scripts JS em arquivos próprios (se o JS estiver embutido no HTML agora, ou mesmo em um pequeno arquivo mas isolado). Isso ajuda manutenção.
•	Comentários no CSS / HTML ou uso de pré-processadores (como SCSS) poderiam tornar o projeto mais profissional, mas para o escopo está muito bom.
________________________________________
2️ Design Visual e Identidade (15 pontos)
Pontuação atribuída: 13 / 15
Justificativa:
•	O design do site é atrativo e tem identidade clara: as cores (preto, vermelho, amarelo) dão um ar forte e coerente, com contraste adequado. (GitHub)
•	A tipografia é consistente (Arial), legível, e suficiente para um site institucional simples. (GitHub)
•	O layout parece bem estruturado e fluido, e de acordo com o que foi planejado no Figma. O README referencia o protótipo no Figma, o que mostra planejamento de design. (GitHub)
Sugestões de melhoria:
•	Apesar de funcional e coerente, o design é relativamente simples — poderia ganhar em sofisticação com fontes customizadas, mais identidade visual (logo, favicon), e talvez animações leves ou transições suaves.
•	A paleta de cores funciona, mas poderia haver mais variação ou contraste em alguns elementos para ligar melhor hierarquia visual (por exemplo, diferentes tons ou variações para seções distintas).
________________________________________
3️ Responsividade (15 pontos)
Pontuação atribuída: 13 / 15
Justificativa:
•	De acordo com o README, o site foi construído com abordagem Mobile First. Breakpoints declarados: 480px (mobile), 768px (tablet), 1024px+ (desktop). (GitHub)
•	A galeria de imagens (“grid responsivo de produtos”) adapta o número de colunas conforme o tamanho da tela. (GitHub)
•	Menu hambúrguer funciona no mobile, conforme o documento. (GitHub)
Sugestões de melhoria:
•	Seria ideal verificar se a responsividade funciona bem em tamanhos intermediários (entre 480px e 768px) — às vezes há layouts “quebrados” nessas faixas.
•	Poderia haver melhoria em touch targets (botões, links) para dispositivos móveis menores — por exemplo, margens/paddings maiores para facilitar toque.
•	Testes documentados mostram evidências, mas falta informação se foram feitos em múltiplos navegadores/dispositivos reais — é importante para garantir que a responsividade funciona fora do DevTools.
________________________________________
4️ Interatividade e JavaScript (15 pontos)
Pontuação atribuída: 12 / 15
Justificativa:
•	Há várias interatividades implementadas com JavaScript: saudação personalizada ao digitar nome, animação em botão de promoções, efeitos de hover nos cards, navegação suave (smooth scroll), validação de formulário, máscara de telefone, integração com WhatsApp, botão “voltar ao topo”. (GitHub)
•	O JavaScript parece estar organizado, funcionais sem menção a erros. O README indica interações bem pensadas. (GitHub)
Sugestões de melhoria:
•	Seria bom separar o JavaScript em arquivo(s) .js em vez de inline ou dentro do HTML (se for o caso), para modularidade e manutenção.
•	Comentários no código JS ajudariam na legibilidade e compreensão.
•	Poderiam ser adicionadas funcionalidades mais avançadas, como animações suaves de carregamento (“loading states”), feedback visual mais sofisticado, ou até alguma funcionalidade dinâmica extra (por exemplo, filtro ou busca no cardápio, carrinho de pedidos fictício, etc.), se fizer sentido para o escopo.
________________________________________
5️ Acessibilidade (10 pontos)
Pontuação atribuída: 9 / 10
Justificativa:
•	O projeto usa tags semânticas (header, nav, main, footer, etc.) conforme descrito no README. (GitHub)
•	Imagens têm alt, formulários têm labels, há link “Pular para conteúdo principal”, os elementos interativos possuem aria-label / aria-expanded. (GitHub)
•	Foco visível para navegação por teclado e contraste de cores parece atender bem os requisitos. (GitHub)
Sugestões de melhoria:
•	Poderia haver um teste com leitor de tela (screen reader) para verificar a usabilidade real.
•	Verificar o contraste de cores com ferramentas de acessibilidade (WCAG) para garantir conformidade, especialmente textos sobre fundo colorido.
•	Talvez adicionar mais atributos ARIA onde fizer sentido (por exemplo, para menus, modais, se houver).
________________________________________
6️ Funcionalidade e Usabilidade (15 pontos)
Pontuação atribuída: 13 / 15
Justificativa:
•	Todas as páginas parecem acessíveis e funcionais (home, cardápio, eventos, contato). Os links funcionam e a navegação parece intuitiva. README menciona integração com WhatsApp, links para redes sociais, animações, etc. (GitHub)
•	A experiência de usuário (UX) parece bastante boa: menu, navegação, visual atraente, responsividade, formulários validados. (GitHub)
Sugestões de melhoria:
•	Embora o site seja funcional, algumas funcionalidades poderiam ser polidas: por exemplo, exibir feedback após o envio do formulário (“mensagem enviada!”), estados de carregamento, verificação de erros (se o WhatsApp não abrir, ou o campo obrigatório não preenchido).
•	Se quiser ir além do escopo atual, implementar funcionalidades mais completas (como um mini sistema de “pedidos”, ou um carrinho de cardápio fictício) poderia tornar a experiência mais rica — embora talvez fuja do escopo original.
________________________________________
7️ Performance e Otimização (10 pontos)
Pontuação atribuída: 8 / 10
Justificativa:
•	Imagens foram otimizadas (indicado no README — “Imagens otimizadas com TinyPNG/Squoosh”) e há uso de lazy-loading. (GitHub)
•	CSS minificado para produção (style.min.css) está presente. (GitHub)
•	Metadados SEO incluídos, favicon implementado, de acordo com README. (GitHub)
Sugestões de melhoria:
•	Verificar tempo real de carregamento: ideal seria fazer um teste com Lighthouse ou PageSpeed para confirmar se realmente carrega em menos de 3 s.
•	Poderia haver minificação / concatenação dos scripts JS (se houver vários arquivos), e compressão adicional (como gzip/brotli) se for para produção real.
•	Garantir que todas as imagens usam formatos otimizados (ex: WebP) e que não há imagens grandes desnecessárias.
________________________________________
8️ Documentação e Git (5 pontos)
Pontuação atribuída: 5 / 5
Justificativa:
•	Existe um README bem completo com descrição do projeto, tecnologias, estrutura, funcionalidades, técnicas, paleta de cores — tudo bem documentado. (GitHub)
•	Histórico Git mostra 59 commits — indica desenvolvimento incremental e uso do versionamento corretamente. (GitHub)
•	Há documentação adicional: pasta docs/ com evidências, wireframes, testes de responsividade, testes de navegador, avaliações recebidas/enviadas — demonstra preocupação com rastreabilidade e processo. (GitHub)
________________________________________
📊 Resumo da Avaliação
Critério	Pontuação (máx)	Atribuída
1. Estrutura e Organização	15	14
2. Design Visual e Identidade	15	13
3. Responsividade	15	13
4. Interatividade e JS	15	12
5. Acessibilidade	10	9
6. Funcionalidade e Usabilidade	15	13
7. Performance e Otimização	10	8
8. Documentação e Git	5	5
TOTAL	100	87 / 100
________________________________________
⭐ Pontos Fortes
1.	Organização e estrutura clara do projeto
O repositório está muito bem organizado: com pastas separadas para documentação, imagens, código, e com nomenclatura consistente. Isso facilita manutenção e leitura por terceiros. Exemplo: home.html, contato.html, style.css, pasta docs/ com evidências. (GitHub)
2.	Design com identidade e usabilidade
A paleta de cores (preto, vermelho, amarelo) está bem pensada e transmite a identidade da creperia. O layout é funcional, coerente e visualmente atraente. O protótipo no Figma demonstra planejamento visual prévio. (GitHub)
3.	Boa documentação e histórico de versionamento
O README é completo e informativo; há evidências de planejamento (wireframe, testes, protótipo) e registro de commits regulares. Isso demonstra prática de boas metodologias de desenvolvimento. (GitHub)
________________________________________
🔧 Oportunidades de Melhoria
1.	Modularização e organização do JavaScript
Separar o JS em arquivos próprios (ex: script.js) e adicionar comentários aumentariam a clareza e manutenção do código, especialmente se o projeto crescer.
2.	Aprimorar experiência do usuário com feedback e estados
Por exemplo, ao enviar o formulário de contato, mostrar uma mensagem de “sucesso” ou “erro”; implementar um “loading” ao enviar ou processar algo, para tornar a experiência mais polida e profissional.
3.	Testes reais de responsividade e performance
Embora haja evidências de testes (screenshots no docs/), seria recomendável testar em dispositivos físicos e usar ferramentas como Lighthouse ou PageSpeed para medir performance e acessibilidade, garantindo que o site realmente entrega bom desempenho e conformidade.
________________________________________
💬 Comentário Final
Parabéns pelo excelente trabalho! 👏
O projeto “Crepe do Lula” demonstra claramente dedicação, bom planejamento e atenção aos detalhes — desde o design visual até a estrutura do repositório e documentação. A identidade visual é forte, o site está bem organizado, responsivo e funcional. É visível que vocês aplicaram boas práticas de desenvolvimento front-end, versionamento e documentação.
Com algumas melhorias sugeridas — especialmente em modularização do código, refinamento da UX e testes mais robustos — o projeto pode ficar ainda mais profissional. Continuem assim, vocês têm muito potencial! 🚀
