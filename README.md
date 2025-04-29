# README do Projeto - Educa AI

## Sumário
- [Introdução](#introdução)
- [Objetivo do Projeto](#objetivo-do-projeto)
- [Funcionalidades Implementadas](#funcionalidades-implementadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Status do Projeto](#status-do-projeto)
- [28 de Abril](#diário-de-progresso--28-de-abril-de-2025)

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
