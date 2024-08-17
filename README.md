# Sistema Web de Portal de Empregos
Repositório destinado para o armazenamento do projeto de Portal de Empregos.

Links adicionais:
[Projeto de Portal de Empregos no Microsoft Planner](https://tasks.office.com/sesisenaispedu.onmicrosoft.com/pt-BR/Home/Planner/#/plantaskboard?groupId=05a234ff-ff93-43f3-8747-be6ad97af327&planId=_DgOSemx7EGJhpI5lBygGGQAAUNp);


>  ## _índice:_

- [Introdução](#introdução);
- [Objetivos do Projeto](#objetivos-do-projeto);
- [Funcionalidades](#funcionalidades);
- [Testes e Resultados](#testes-e-resultados);
- [Designs e Estilos](#designs-e-estilos);
- [Segurança de Dados](#segurança-de-dados);
- [Estrutura de Programação](#estrutura-de-programação);

>  ## _Introdução_
O crescente desemprego e a dificuldade em encontrar oportunidades de trabalho adequadas, bem como a escassez de funcionários qualificados, são desafios significativos no mercado de trabalho atual. Este projeto tem como objetivo fornecer soluções para esses problemas através da criação de um portal de empregos.

Nosso portal foi desenvolvido para facilitar a busca por novas oportunidades, especialmente para jovens que estão iniciando suas carreiras. Além disso, ele também visa ajudar empresas a encontrar candidatos qualificados de maneira mais eficiente e direcionada.

Com isso, criamos uma plataforma acessível e intuitiva que busca conectar candidatos a oportunidades de trabalho, bem como ajudar empresas a identificar e contratar os talentos necessários para o seu crescimento. O objetivo final é contribuir para um mercado de trabalho mais dinâmico e eficiente, beneficiando tanto os candidatos quanto as empresas.
<br>
> ## _Objetivos do Projeto_
**1. Específicos:**
     <br>- Objetivo: Criar uma plataforma de empregos online que permita a candidatos se cadastrarem, criarem currículos, e se candidatarem a vagas, além de permitir que empresas publiquem oportunidades de emprego e busquem candidatos qualificados.<br>
     - Explicação: O objetivo é claro e detalhado, definindo as principais funcionalidades que o site precisa oferecer.<br>

**2. Mensuráveis:**
     <br>- Objetivo: Alcançar 500 usuários cadastrados (candidatos e empresas) e 50 vagas de emprego publicadas no primeiro mês após o lançamento do site.<br>
     - Explicação: Esses números fornecem uma meta quantificável que pode ser usada para medir o sucesso inicial do site.<br>
     
**3. Atingíveis:**
     <br>- Objetivo: Desenvolver e lançar a plataforma dentro de um período de três meses, utilizando recursos e tecnologias disponíveis (Laravel, PostgreSQL) com uma equipe de desenvolvimento composta por 21 pessoas.<br>
     - Explicação: O prazo e os recursos estão alinhados com a capacidade da equipe, tornando o objetivo realista e alcançável.<br>
     
**4. Relevantes:**
     <br>- Objetivo: Contribuir para a redução do desemprego e facilitar a contratação de profissionais qualificados, atendendo às necessidades tanto dos candidatos quanto das empresas em busca de talentos.<br>
     - Explicação: O objetivo está alinhado com problemas reais do mercado de trabalho e tem um impacto significativo para os usuários.<br>
     
**5. Temporais:**
     <br>- Objetivo: Lançar a versão beta do portal de empregos em até três meses, com planos de implementar funcionalidades adicionais e realizar melhorias baseadas no feedback dos usuários durante os três meses subsequentes.<br>
     - Explicação: Estabelece um cronograma claro para o lançamento e desenvolvimento contínuo do projeto.<br>

<br>

> ## _Metodologia_
Para alcançar os objetivos propostos, seguimos uma abordagem metodológica estruturada em várias etapas, que envolveu desde a coleta de dados até o desenvolvimento e validação do sistema. As principais etapas incluem:
<br>
**Pesquisa e Levantamento de Dados:**

- Realizamos um levantamento detalhado de dados sobre as rotas, horários e padrões de uso do transporte público em Limeira. Essa pesquisa envolveu a análise de registros históricos, entrevistas com usuários e operadores do sistema, além da coleta de dados em tempo real via sensores e dispositivos de GPS.
- Analisamos os problemas mais comuns enfrentados pelos usuários, como atrasos, falta de informações precisas e dificuldades no planejamento de rotas.
<br>

**Desenvolvimento do Sistema:**

- Com base nos dados coletados, iniciamos o desenvolvimento de um sistema de gerenciamento inteligente de transporte público. Esse sistema foi construído utilizando uma combinação de tecnologias avançadas, como:
GPS para rastreamento em tempo real dos veículos.
- Big Data para processamento e análise de grandes volumes de informações, permitindo a identificação de padrões e anomalias.
- Machine Learning para prever atrasos e sugerir rotas alternativas com base nas condições atuais e históricas do tráfego.
<br>

**Testes e Validação:**

- Realizamos uma série de testes rigorosos para validar a eficácia do sistema em diferentes condições, como horários de pico, mudanças climáticas e interrupções inesperadas no serviço.
- Esses testes foram fundamentais para identificar falhas e realizar os ajustes necessários, garantindo que o sistema funcione de forma confiável e eficiente em situações reais.
<br>

**Implementação Piloto:**

- Implementamos o sistema em fase piloto em determinadas rotas e horários específicos para avaliar seu desempenho e coletar feedback dos usuários.
- Com base nos resultados obtidos na fase piloto, fizemos as otimizações necessárias antes da implementação em larga escala.
<br>

**Análise de Impacto:**

- Após a implementação, realizamos uma análise do impacto do sistema na qualidade do serviço de transporte público, avaliando aspectos como redução de atrasos, melhoria na satisfação dos usuários e eficiência operacional.

<br>

> ## _Funcionalidades_

<br>

> ## _Testes e Resultados_

<br>

> ## _Designs e Estilos_

<br>

> ## _Segurança de Dados_

<br>

> ## _Estrutura de Programação_
**Framework Laravel**
<br>
O portal de empregos foi desenvolvido utilizando o framework Laravel, uma poderosa ferramenta baseada em PHP que permite o desenvolvimento de aplicações web de forma rápida e segura. Laravel oferece uma arquitetura bem estruturada e organizada, facilitando a implementação de funcionalidades complexas, como autenticação de usuários, gerenciamento de dados e integração com APIs. Suas características, como o sistema de rotas simples, a utilização de Eloquent ORM para manipulação de banco de dados e o suporte a migrações, fazem dele uma escolha ideal para projetos que demandam escalabilidade e segurança.

<hr>

**Banco de Dados Postgresql**
<br>
Para o gerenciamento dos dados, optamos pelo PostgreSQL, um banco de dados relacional conhecido por sua robustez, desempenho e conformidade com o padrão SQL. PostgreSQL oferece suporte a transações complexas, integridade referencial e a capacidade de lidar com grandes volumes de dados, o que o torna perfeito para uma aplicação que precisa armazenar e gerenciar informações críticas, como perfis de candidatos, vagas de emprego, e dados empresariais. A combinação de Laravel com PostgreSQL garante que o sistema seja não apenas funcional, mas também seguro e eficiente.

<hr>

**Github**
<br>
Além disso, utilizamos o Git como sistema de controle de versão, permitindo o armazenamento seguro de todos os arquivos do projeto e da documentação. O Git não só facilita a colaboração entre os membros da equipe, como também assegura que todas as mudanças no código sejam registradas e possam ser revertidas, se necessário, garantindo assim um desenvolvimento mais organizado e controlado.


