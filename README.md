# README do Projeto - Educa AI

## Sumário
- [Introdução](#introdução)
- [Objetivo do Projeto](#objetivo-do-projeto)
- [Funcionalidades Implementadas](#funcionalidades-implementadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Status do Projeto](#status-do-projeto)
- [28 de Abril](#diário-de-progresso--28-de-abril-de-2025)
- [29 de Abril](#diario-de-progresso--29-de-abril-de-2025)

## Introdução
Projeto de desenvolvimento do site "Educa AI", uma solução tecnológica voltada para a gestão escolar. O projeto está sendo construído respeitando práticas modernas de design responsivo, usabilidade e organização visual.

## Objetivo do Projeto
Construir um site que seja visualmente moderno, organizado e funcional, com uma experiência fluida tanto no desktop quanto no mobile, utilizando HTML, CSS e Bootstrap.

## Funcionalidades Implementadas
- Estrutura de menu responsivo com botão "Login" posicionado corretamente em diferentes resoluções.
- Seção "Sobre" planejada para conter carrossel de imagens e caracterização dos serviços.
- Estruturação das seções com uso de `<section>` para melhor organização e navegação.
- Adaptação automática do estilo do menu:
  - Bordas arredondadas estilo cápsula no desktop.
  - Bordas retangulares no mobile para melhor aproveitamento da tela.

## Estrutura do Projeto
- **Cabeçalho (Header)**:
  - Logo Educa AI.
  - Menu de navegação responsivo.
  - Botão "Login" separado conforme breakpoint.

- **Sessão Sobre (Em construção):**
  - Carrossel de slides ilustrativos.
  - Caracterização dos serviços oferecidos.

## Tecnologias Utilizadas
- HTML5
- CSS3
- Bootstrap 5.3.5
- Bootstrap Icons

## Status do Projeto
- Estrutura inicial do cabeçalho finalizada.
- Carrossel em desenvolvimento.
- Seção "Sobre" sendo estruturada.
- Projeto em andamento com atualizações contínuas.

## Diário de Progresso – 28 de abril de 2025

Hoje, avancei no desenvolvimento do projeto **Educa AI**, focando principalmente na seção inicial do site e no carrossel de destaque. Durante o processo, explorei novas abordagens de layout e interatividade, buscando uma experiência mais próxima da usada no site da Apple.

Tentei implementar um carrossel com **slides parcialmente visíveis**, permitindo que o próximo slide aparecesse nas laterais, como referência direta ao carrossel do site da Apple. Para isso, fiz diversos ajustes no `Bootstrap Carousel`, aplicando `display: flex`, `overflow: visible` e outras técnicas para posicionamento. No entanto, essa abordagem acabou comprometendo o funcionamento das transições automáticas dos slides, o que me fez optar por retornar ao formato tradicional de carrossel, com uma imagem centralizada e transição total entre os slides.

No fim, mantive o carrossel com layout mais simples e funcional, **com as imagens centralizadas e ocupando boa parte da tela**, o que garantiu estabilidade e boa aparência, mesmo sem o efeito de pré-visualização dos slides vizinhos.

Além disso, trabalhei em pequenos ajustes visuais na seção **"Sobre"**, principalmente no alinhamento e tentativa de arredondamento das bordas para deixar a apresentação mais moderna e amigável. Essas mudanças foram sutis, mas ajudam a dar um ar mais polido à interface.

# Diario de Progresso – 29 de abril de 2025

Hoje, avancei de forma significativa no desenvolvimento do site **Educa AI**, focando na construção e refinamento das seções **Planos**, **Funcionalidades** e **Contato**, priorizando a organização visual, a usabilidade e a consistência da identidade visual do projeto.

## Ilustrações
Foram criadas ilustrações personalizadas para representar:
- Os três planos (**Professor**, **Coordenador** e **Escola**);
- Cada funcionalidade do sistema (**Planejamento**, **Avaliações**, **Frequência**, **Perfil do Aluno**, **Relatórios**, **Horários**).

As imagens foram padronizadas para manter **proporção uniforme (1:1)**, garantindo consistência visual entre os cards e os conteúdos das abas.

A imagem do plano *Escola* foi substituída, trocando uma fachada genérica por uma ilustração de educadores, alinhando-se com o estilo dos demais cards.

---

## Seção Planos
- Reestruturamos a disposição dos planos utilizando `d-flex`, `flex-wrap` e `gap-4`, resolvendo o problema de espaçamento insuficiente entre os cards.
- Limitamos a largura dos cards para **380px**, melhorando a responsividade e o equilíbrio visual no desktop e no mobile.
- Definimos e detalhamos três planos:
  - **Professor**: uso individual com acesso a todos os recursos.
  - **Coordenador**: gestão de múltiplas turmas, disciplinas e organização de horários.
  - **Escola**: plano institucional para múltiplos usuários e suporte ampliado.
- Escrevemos descrições objetivas e inserimos **ícones de verificação (`bi-check-circle-fill`)** nos benefícios, aprimorando a comunicação visual.

---

## Seção Funcionalidades
- Estruturamos a seção de funcionalidades usando **abas (`tab-pane`)**, proporcionando uma navegação prática e segmentada entre os recursos.
- Cada funcionalidade foi apresentada com:
  - Uma ilustração exclusiva,
  - Um título descritivo,
  - Um parágrafo explicativo claro.
- Funcionalidades criadas:
  - **Planejamento** de aulas alinhado à BNCC e DCRFOR;
  - **Avaliações** personalizadas e inclusivas;
  - **Frequência** de alunos registrada de forma prática;
  - **Perfil do Aluno** com acompanhamento individualizado;
  - **Relatórios** completos para gestão pedagógica;
  - **Horários** para organização eficiente da semana escolar.

Já foi registrado o direcionamento futuro para estudar a implementação de um **menu carrossel horizontal** na navegação mobile dessa seção.

---

## Seção Fale Conosco
- Criamos a seção **Fale Conosco**, que ainda não existia no projeto.
- Implementamos um **formulário de contato** funcional, contendo os campos:
  - Nome completo,
  - E-mail,
  - Telefone,
  - Mensagem.
- Aplicamos estilos consistentes com a identidade visual do projeto e mantivemos a responsividade para diferentes tamanhos de tela.

---

## Estilo e Design
- Ajustamos as cores de fundo das seções **Planos** e **Fale Conosco** para tons suaves de azul, reforçando a identidade visual do Educa AI.
- Uniformizamos altura, proporções e espaçamentos internos dos cards e ilustrações.
- Refinamos a hierarquia visual para melhor fluidez de leitura, especialmente no mobile.

---

## Direcionamentos
- Mantivemos a abordagem visual baseada em **ilustrações** para garantir empatia e clareza na comunicação.
- Registramos a intenção futura de implementar um **carrossel de funcionalidades** para navegação no mobile, caso a complexidade permita.

---