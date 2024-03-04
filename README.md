## Relatório: Integração do SonarQube com Projetos .NET
Neste documento, investigamos métodos para aprimorar a segurança e a integridade do código por meio da utilização conjunta do SonarQube, Docker e .NET Core. O SonarQube serve para examinar o código e apontar falhas relativas à segurança e qualidade, ao passo que o Docker proporciona um ambiente segregado e gerenciável para operar o SonarQube. O enfoque deste guia é na avaliação de uma aplicação ASP.NET Core 3.0 com o auxílio do SonarQube, com o objetivo de detectar e solucionar eventuais vulnerabilidades no código.


## Tecnologia e Conceitos
sonarQube: Uma ferramenta de análise estática de código que identifica bugs, vulnerabilidades, e problemas de código em geral. Ele fornece insights valiosos para melhorar a qualidade do código e a manutenibilidade do software.

Projetos .NET: Refere-se a projetos de software desenvolvidos na plataforma .NET da Microsoft. Isso inclui aplicativos de desktop, aplicativos da web, serviços, e outras soluções que utilizam a estrutura e as linguagens de programação fornecidas pelo .NET.

SonarScanner for .NET: Uma extensão do SonarQube para projetos .NET, que automatiza o processo de análise estática do código. Ele é usado para escanear o código-fonte, identificar problemas de qualidade e enviar os resultados para o servidor do SonarQube.

## Aprendizados

Configuração do SonarQube: Aprendemos como configurar o SonarQube em projetos .NET, incluindo a instalação do SonarScanner for .NET e a integração com o ambiente de desenvolvimento.

Personalização das Regras de Análise: Exploramos as melhores práticas para personalizar as regras de análise do SonarQube, ajustando-as para atender às necessidades específicas do projeto e da equipe de desenvolvimento.

Interpretação de Resultados: O artigo ofereceu insights sobre como interpretar os resultados da análise estática gerados pelo SonarQube, destacando a importância de priorizar e abordar os problemas identificados.

Melhores Práticas e Configurações: Foi discutido um conjunto de melhores práticas e configurações recomendadas para otimizar a integração do SonarQube com projetos .NET, visando melhorar a qualidade do código e facilitar o processo de desenvolvimento.


Print do Dashbaord principal

<img width="1185" alt="Screenshot 2024-03-03 at 22 02 54" src="https://github.com/MrSchipRozen/AtividadeProgSonar/assets/99350292/5cc4867a-fb70-4727-86af-db5e7137fcdc">

Print do erro

<img width="910" alt="Screenshot 2024-03-03 at 22 03 54" src="https://github.com/MrSchipRozen/AtividadeProgSonar/assets/99350292/ca949784-2d33-44b8-acc6-dc5505a312e0">
