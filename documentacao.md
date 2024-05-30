# Documentação do Projeto

## 1. Introdução
&emsp;&emsp;O projeto para "y-HACK: Fashion, People and Planet" é uma solução inovadora que melhore a rastreabilidade dos processos na cadeia produtiva da moda, utilizando tecnologias de blockchain.

&emsp;&emsp;Durante o evento y-HACK, focado em moda, pessoas e sustentabilidade, a equipe irá desenvolver um sistema que permite medir a sustentabilidade dos produtos através do registro detalhado e imutável de cada etapa da produção de um SKU (Stock Keeping Unit).

## 2. Visão Geral
### Visão Geral do Projeto: Combate ao Greenwashing na Indústria da Moda

#### Problema a Ser Resolvido
O _greenwashing_ é uma prática em que empresas promovem produtos como ecologicamente sustentáveis sem de fato adotarem práticas ambientais responsáveis. Isso engana os consumidores e mina a confiança em produtos verdadeiramente sustentáveis. Na indústria da moda, essa prática é particularmente preocupante devido ao impacto ambiental significativo da produção de roupas e acessórios.

#### Solução Proposta
A equipe Baobá propõe uma solução inovadora de software baseado em microserviços e blockchain para garantir a autenticidade das alegações de sustentabilidade na indústria da moda através da rastreabilidade do processo de produção. Nossa solução se baseia na tecnologia blockchain para criar um sistema transparente e confiável, onde cada etapa da produção é registrada e verificada.

#### Impacto Esperado
- **Aumento da Confiança do Consumidor**: Com uma fonte confiável de verificação de sustentabilidade, os consumidores poderão fazer escolhas informadas e apoiar marcas que realmente adotam práticas ecológicas.
- **Redução do Greenwashing**: Empresas serão desestimuladas a praticar o greenwashing, pois não poderão registrar alegações falsas sem serem detectadas.
- **Incentivo a Práticas Sustentáveis**: Produtores e indústrias serão incentivados a adotar práticas verdadeiramente sustentáveis para participar do mercado de moda sustentável.



## 3. Persona

| **Persona**            | **Nome**            | **Descrição**                                                                                   | **Objetivos**                                                                                      | **Desafios**                                                                                                | **Necessidades**                                                                                               |
|------------------------|---------------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **Entusiasta da Moda** | Mariana Lopes       | Estudante de design de moda, 24 anos, interessada em práticas de moda sustentável e ética.      | Aprender mais sobre a origem dos produtos de moda que consome e promover práticas sustentáveis.    | Acessar informações confiáveis e detalhadas sobre a cadeia produtiva dos produtos de moda.                   | Ferramentas que permitam a visualização fácil e detalhada da rastreabilidade e sustentabilidade dos produtos.  |
| **Ambientalista**      | Pedro Fernandes     | Ambientalista e consultor de sustentabilidade, 35 anos, focado em práticas industriais verdes. | Ajudar empresas a adotar práticas mais sustentáveis e rastrear o impacto ambiental dos produtos.  | Coletar dados precisos e confiáveis sobre a cadeia produtiva para avaliar a sustentabilidade das operações. | Acesso a dados completos e imutáveis sobre a produção e rastreamento de SKUs, integrados com relatórios e análises. |

Estas personas ajudarão a guiar o desenvolvimento do projeto, garantindo que as funcionalidades e a experiência do usuário atendam às necessidades dos principais públicos-alvo.


## 4. Funcionalidades
1. **Registro em Blockchain**: Implementação de uma plataforma baseada em blockchain que atua como intermediário entre produtores, indústrias e confecções. Essa plataforma registrará de forma imutável os selos de sustentabilidade de cada etapa do processo de produção.

2. **Verificação de Selos de Sustentabilidade**: Cada participante do processo (produtores de matéria-prima, indústrias de manufatura, confecções) terá seus selos de sustentabilidade e responsábilidade social verificados e registrados na blockchain. Alguns dos principais selos de sustentabilidade e responsabilidade social que serão considerados incluem:
   - **Global Organic Textile Standard (GOTS)**
   - **Fair Trade Certified**
   - **Bluesign**
   - **OEKO-TEX Standard 100**
   - **Cradle to Cradle Certified**
   - **Better Cotton Initiative (BCI)**

3. **Checagem por Agentes**: Um agente especializado será responsável por verificar cada parte do processo de produção. O produto final será checado com base na conformidade de todos os agentes envolvidos, garantindo que todos os selos de sustentabilidade registrados estejam corretos e válidos.

4. **Transparência e Acessibilidade**: Consumidores terão acesso a um histórico detalhado do produto, podendo verificar a autenticidade dos selos de sustentabilidade e responsabilidade social diretamente. Isso será possível através de um microserviço, o qual acessará a rede blockchain para realizar as validações.

5. **Bloqueio de Produtos Não Conformes**: Caso qualquer parte do processo de produção não atenda aos critérios de sustentabilidade registrados, o produto será bloqueado de ser vendido como sustentável. Isso evita a comercialização indevida de produtos que não são realmente ecológicos ou não seguem boas práticas sociais.

## 5. Arquitetura
Visão geral da arquitetura do projeto, incluindo a estrutura de pastas e arquivos, banco de dados utilizado, e como as diferentes partes do sistema se comunicam.


## 6. Próximos passos

