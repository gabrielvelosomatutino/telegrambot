## Chatbot Telegram ETL com AWS em Python
Este repositório contém um conjunto abrangente de códigos em Python para facilitar a extração, transformação e carga (ETL) de informações de um chatbot no Telegram, utilizando serviços da Amazon Web Services (AWS). O processo é projetado para ser eficiente e escalável, incorporando diversas etapas fundamentais.

## **Funcionalidades Principais**

**1. Ingestão de Dados**
Os scripts de ingestão oferecem meios eficazes para extrair dados do chatbot no Telegram. Essa etapa é essencial para manter a integridade e a atualidade das informações.

**2. API Gateway e Lambda**

A integração da API Gateway com funções Lambda proporciona uma arquitetura serverless ágil. As requisições do chatbot são processadas de maneira eficiente, garantindo respostas rápidas e confiáveis.

**3. Armazenamento no Amazon S3**

Os dados extraídos são armazenados de forma segura no Amazon S3, oferecendo durabilidade, escalabilidade e gerenciamento simplificado. Isso assegura que as informações estejam prontamente disponíveis para as fases subsequentes do pipeline de dados.

**4. Event Bridge e Lambda para ETL

O AWS Event Bridge é empregado para orquestrar e automatizar a execução das tarefas de ETL. As funções Lambda são acionadas em resposta a eventos específicos, facilitando a transformação eficiente dos dados.

**5. Athena para Apresentação de Dados**

Para explorar e analisar os dados armazenados, utilizamos o Amazon Athena. Isso oferece uma maneira flexível e eficaz de executar consultas SQL diretamente nos dados do S3, facilitando a obtenção de insights valiosos.

**Como Utilizar**

Ingestão de Dados: Execute os scripts de ingestão para capturar dados do chatbot no Telegram.

API Gateway e Lambda: Configure a API Gateway e as funções Lambda para processar as requisições do chatbot.

Armazenamento no Amazon S3: Configure o Amazon S3 para o armazenamento seguro dos dados extraídos.

Event Bridge e Lambda para ETL: Configure as regras no Event Bridge para acionar as funções Lambda responsáveis pela transformação de dados.

Athena para Apresentação de Dados: Configure consultas no Amazon Athena para análise e apresentação dos dados conforme necessário.

Certifique-se de seguir as práticas recomendadas de segurança da AWS e configurar as permissões apropriadas para garantir a integridade e a privacidade dos dados.

**Contribuições**

Contribuições para a melhoria deste projeto são bem-vindas. Sinta-se à vontade para enviar pull requests com correções de bugs, sugestões de novas análises ou melhorias na documentação.

**Contato**

Para mais informações ou dúvidas relacionadas a este projeto, entre em contato com [Gabriel Veloso] via e-mail: [velosogabriel5@gmail.com].
