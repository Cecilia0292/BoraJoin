# BoraJoin 🎆

## **Nome dos integrantes:** 👨‍💻  
+ _Scrum Master: Steven Jobs_  
+ _Product Owner: Steven Jobs_  
+ _Scrum Team: Desenvolvedor Flutter – Wesley_  
+ _Scrum Team: Tester – Jim_  
+ _Scrum Team: Desenvolvedora Angular – Ruthe_
+ _Scrum Team: Especialista em Marketing – Carla_
+ _Scrum Team: DBA (Administrador de Banco de Dados) – Dom_

---

## Tecnologias utilizadas: 👨‍💻  
* 👉 **Flutter**: para desenvolvimento multiplataforma de aplicativos móveis com visual atraente e responsivo  
* 👉 **Angular**: para construção da interface web dinâmica e interativa  
* 👉 **Java + Spring Boot**: formando o backend da aplicação, responsável pelo processamento de dados, segurança, integração com serviços externos e gerenciamento das funcionalidades essenciais do sistema
* 👉 **PostgreSQL**: banco de dados relacional utilizado para armazenar informações dos usuários, eventos, confirmações de presença e histórico de interações


---

## Descrição do projeto:  
#### *BoraJoin é um sistema completo para criação e gerenciamento de eventos, disponível tanto como aplicativo móvel quanto como página web.*  
#### *Sua proposta é oferecer uma experiência intuitiva, acessível e prática para qualquer pessoa — mesmo aquelas sem familiaridade com tecnologia. Com o BoraJoin, organizar eventos como casamentos, chás de bebê, festas de aniversário ou confraternizações se torna simples e agradável.*  
#### *A interface amigável e os recursos personalizados permitem que cada detalhe da comemoração seja planejado com facilidade, tornando cada evento único e inesquecível.*  
#### ***Junte-se. Comemore. BoraJoin.***

---

##**📋 Product Backlog**: Foram listados pelo menos 24 itens que foram transformadas em sprints pelo Product Owner na primeira Sprint Planning.

---
## **Sprints ♾️:**

## 🌀 Sprint 1 – Setup do Projeto ♾️  
**📅 Data inicial e final:** 04/08/2025 – 14/08/2025  

### 🎯 Objetivo da Sprint  
Configurar o ambiente de desenvolvimento, repositório, banco de dados e ferramentas de controle de versão para iniciar o projeto BoraJoin com base sólida e integrada entre web, mobile e backend.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Instalou e configurou o ambiente Flutter  
  - Criou o projeto base do app móvel  
  - Definiu a estrutura inicial de navegação e pastas  
  - Implementou tela de boas-vindas com layout responsivo

- **Ruthe (Angular):**  
  - Configurou o ambiente Angular  
  - Criou o projeto base da interface web  
  - Implementou a página inicial com design responsivo  
  - Estabeleceu rotas principais para navegação

- **Jim (Tester):**  
  - Definiu os critérios de aceitação para o setup  
  - Criou os primeiros testes automatizados para validação de rotas e componentes  
  - Testou a responsividade das telas iniciais no app e web

- **Dom (DBA):**  
  - Instalou e configurou o PostgreSQL  
  - Criou os primeiros esquemas e tabelas para usuários e eventos  
  - Documentou a estrutura inicial do banco e definiu padrões de nomenclatura

- **Carla (Marketing):**  
  - Criou identidade visual preliminar do BoraJoin  
  - Elaborou o slogan e texto de apresentação do projeto  
  - Definiu canais de comunicação e estilo de linguagem para o público-alvo

- **Steven Jobs (Scrum Master & Product Owner):**  
  - Facilitou reuniões de planejamento e alinhamento  
  - Definiu os critérios de aceitação e metas da Sprint  
  - Organizou o Product Backlog inicial com 25 itens  
  - Configurou o repositório no GitHub e integrou ferramentas de CI/CD

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Configuração dos ambientes, estrutura inicial e primeiras telas           |
| Testes          | 1 dia   | Validação de rotas, responsividade e funcionamento básico                 |
| Revisão         | 2 dias  | Ajustes finos no layout, estrutura de pastas e documentação inicial       |
| Deploy          | 1 dia   | Publicação da versão inicial em ambiente de homologação                   |

### 📝 Observações

- Todos os ambientes foram integrados com **GitHub Actions** para facilitar o CI/CD nas próximas Sprints.  
- A comunicação entre os membros foi feita via **Discord** e **Trello**, com reuniões diárias de 15 minutos.  
- O backend em **Java + Spring Boot** foi iniciado paralelamente com endpoints simulados para testes iniciais.  
- A estrutura de navegação e rotas foi padronizada entre web e mobile para garantir consistência na experiência do usuário.

---
## 🧭 Sprint 2 – Cadastro e Login 🔐  
**📅 Data inicial e final:** 15/08/2025 – 28/08/2025  

### 🎯 Objetivo da Sprint  
Implementar as funcionalidades de cadastro de usuário, login com autenticação segura e estrutura básica de criação de eventos.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Desenvolveu telas de cadastro e login no app  
  - Implementou validação de campos e feedback visual  
  - Iniciou integração com backend via API REST

- **Ruthe (Angular):**  
  - Criou componentes de cadastro e login na interface web  
  - Estabeleceu comunicação com backend usando HTTPClient  
  - Aplicou validações reativas nos formulários

- **Jim (Tester):**  
  - Criou testes automatizados para fluxo de login e cadastro  
  - Testou casos de erro e sucesso nos dois ambientes  
  - Validou segurança básica (senhas, redirecionamentos)

- **Dom (DBA):**  
  - Criou tabelas de usuários com criptografia de senha  
  - Documentou estrutura de autenticação  
  - Otimizou queries de login e verificação de duplicidade

- **Carla (Marketing):**  
  - Criou conteúdo para onboarding de novos usuários  
  - Elaborou mensagens de boas-vindas e instruções iniciais  
  - Definiu tom de voz para comunicação com o usuário

- **Steven Jobs (Scrum Master & Product Owner):**  
  - Refinou backlog com base em feedback da Sprint 1  
  - Validou critérios de aceitação com o time  
  - Facilitou reuniões de alinhamento técnico

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 7 dias  | Implementação de cadastro, login e estrutura de eventos                   |
| Testes          | 2 dias  | Validação de autenticação e segurança                                     |
| Revisão         | 3 dias  | Ajustes visuais, integração e documentação técnica                        |
| Deploy          | 2 dias  | Publicação em ambiente de homologação com testes de carga                 |

### 📝 Observações

- Utilizado **Kanban híbrido** com limites de WIP para melhorar fluxo contínuo.  
- Ferramentas: **Postman** para testes de API, **Notion** para documentação.  
- Feedback dos testes levou à inclusão de mensagens de erro mais claras.  
- Primeira versão funcional do sistema com login e cadastro foi entregue com sucesso.

---
## 🗓️ Sprint 3 – Criação de Eventos ♾️  
**📅 Data inicial e final:** 26/08/2025 – 05/09/2025  

### 🎯 Objetivo da Sprint  
Desenvolver a funcionalidade de criação de eventos, permitindo ao usuário cadastrar informações como nome, data, local e tipo de evento, com suporte tanto na interface web quanto no aplicativo móvel.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou a tela de criação de eventos com campos dinâmicos  
  - Implementou seleção de data e local com componentes nativos  
  - Adicionou animações sutis para melhorar a experiência do usuário

- **Ruthe (Angular):**  
  - Desenvolveu o formulário de criação de eventos na interface web  
  - Aplicou máscaras de input para data e hora  
  - Implementou validação de campos obrigatórios e feedback visual

- **Jim (Tester):**  
  - Testou a criação de eventos com diferentes tipos de dados  
  - Validou comportamento em casos de campos vazios ou inválidos  
  - Realizou testes de usabilidade com foco na clareza do processo

- **Dom (DBA):**  
  - Criou modelo de dados para armazenar eventos com campos personalizáveis  
  - Implementou relacionamentos entre usuários e eventos  
  - Otimizou queries para busca e filtragem de eventos

- **Carla (Marketing):**  
  - Criou conteúdo explicativo sobre como criar eventos  
  - Elaborou exemplos de uso para diferentes tipos de celebrações  
  - Iniciou campanha de divulgação da nova funcionalidade

- **Steven Jobs (Scrum Master & Product Owner):**  
  - Validou critérios de aceitação com base em testes exploratórios  
  - Facilitou reuniões de revisão e refinamento do backlog  
  - Acompanhou integração entre frontend, backend e banco de dados

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Implementação dos formulários e lógica de criação de eventos              |
| Testes          | 1 dia   | Validação de campos, comportamento e integração com backend               |
| Revisão         | 2 dias  | Ajustes visuais, melhorias na UX e revisão de código                      |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações

- Criado modelo de dados no backend para armazenar eventos com campos personalizáveis.  
- Utilizado serviço de geolocalização para sugestão de locais próximos.  
- A funcionalidade foi testada em diferentes navegadores e dispositivos móveis.  
- Feedback positivo dos usuários sobre a clareza e simplicidade do processo de criação.
  
---
## 🗓️ Sprint 4 – Listagem e Visualização de Eventos ♾️  
**📅 Data inicial e final:** 06/09/2025 – 16/09/2025  

### 🎯 Objetivo da Sprint  
Implementar a listagem dos eventos criados e permitir a visualização detalhada de cada evento, com layout atrativo, navegação fluida e filtros inteligentes para facilitar a busca.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Desenvolveu a tela de listagem com cards interativos para cada evento  
  - Implementou navegação para a tela de detalhes do evento  
  - Adicionou filtros por data e tipo de evento

- **Ruthe (Angular):**  
  - Criou componente de listagem com visual limpo e responsivo  
  - Implementou página de detalhes com informações completas do evento  
  - Adicionou funcionalidade de busca por nome e tipo

- **Jim (Tester):**  
  - Testou a exibição correta dos dados dos eventos  
  - Validou a navegação entre listagem e detalhes  
  - Verificou o funcionamento dos filtros e busca em diferentes navegadores

- **Dom (DBA):**  
  - Otimizou queries para listagem com paginação e ordenação por data  
  - Criou índices para acelerar buscas por nome e tipo de evento  
  - Garantiu consistência dos dados exibidos nas telas

- **Carla (Marketing):**  
  - Criou conteúdo para destacar eventos em destaque e populares  
  - Elaborou sugestões de categorias para facilitar a navegação dos usuários  
  - Iniciou campanha de engajamento com foco em eventos locais

- **Steven Jobs (Scrum Master & Product Owner):**  
  - Validou critérios de aceitação com base na experiência do usuário  
  - Facilitou reuniões de alinhamento entre frontend e backend  
  - Acompanhou testes exploratórios e refinamento de funcionalidades


### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação das telas de listagem e visualização de eventos                   |
| Testes          | 1 dia   | Validação da navegação, filtros e exibição correta dos dados              |
| Revisão         | 2 dias  | Ajustes visuais, melhorias na performance e revisão de código             |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações

- Utilizado scroll infinito na listagem para melhor performance em dispositivos móveis  
- Backend otimizado com paginação e ordenação por data  
- Filtros e busca foram ajustados para oferecer resultados relevantes com rapidez  
- Feedback inicial indicou alta aceitação da interface de visualização
---
## 🗓️ Sprint 5 – Edição e Exclusão de Eventos ♾️  
**📅 Data inicial e final:** 17/09/2025 – 27/09/2025  

### 🎯 Objetivo da Sprint  
Permitir que os usuários editem ou excluam eventos já criados, garantindo flexibilidade, controle total sobre suas comemorações e consistência entre as interfaces web e mobile.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Implementou a funcionalidade de edição com preenchimento automático dos dados existentes  
  - Adicionou botão de exclusão com confirmação via pop-up  
  - Garantiu que as alterações fossem refletidas imediatamente na listagem

- **Ruthe (Angular):**  
  - Desenvolveu a interface de edição com campos reativos e validação  
  - Criou modal de confirmação para exclusão de eventos  
  - Atualizou a listagem para refletir mudanças em tempo real

- **Jim (Tester):**  
  - Testou os fluxos de edição e exclusão em diferentes cenários  
  - Validou mensagens de erro e sucesso  
  - Verificou se os dados atualizados estavam sendo corretamente salvos e exibidos

- **Dom (DBA):**  
  - Atualizou o modelo de dados para suportar edição segura e exclusão lógica  
  - Implementou rotas específicas para PUT e DELETE com controle de integridade  
  - Garantiu que apenas o criador do evento pudesse realizar alterações

- **Carla (Marketing):**  
  - Criou conteúdo explicativo sobre como editar ou cancelar eventos  
  - Elaborou mensagens de aviso para convidados em caso de alterações importantes  
  - Sugeriu boas práticas para manter eventos atualizados e claros

- **Steven Jobs (Scrum Master & Product Owner):**  
  - Validou critérios de aceitação com foco na segurança e clareza das ações  
  - Facilitou sessões de revisão e refinamento de funcionalidades  
  - Acompanhou testes exploratórios e ajustes finais antes do deploy

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Implementação das funcionalidades de edição e exclusão de eventos         |
| Testes          | 1 dia   | Validação dos fluxos, mensagens e persistência dos dados                  |
| Revisão         | 2 dias  | Ajustes visuais, revisão de segurança e tratamento de erros               |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações

- Implementado controle de permissões para garantir que apenas o criador do evento possa editá-lo ou excluí-lo  
- Backend atualizado com rotas específicas para PUT e DELETE  
- Exclusão lógica aplicada para preservar histórico e permitir recuperação futura  
- Interface ajustada para evitar exclusões acidentais com duplo aviso

---
  
## 🗓️ Sprint 6 – Convites e Compartilhamento de Eventos ♾️  
**📅 Data inicial e final:** 28/09/2025 – 08/10/2025  

### 🎯 Objetivo da Sprint  
Desenvolver a funcionalidade de envio de convites e compartilhamento de eventos com amigos e familiares por diferentes canais, promovendo engajamento e alcance das comemorações.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou botão de compartilhamento nativo para WhatsApp, e-mail e redes sociais  
  - Implementou tela de envio de convite com campo para e-mail dos convidados  
  - Adicionou animações de feedback ao enviar convite com sucesso

- **Ruthe (Angular):**  
  - Desenvolveu componente de compartilhamento com links personalizados  
  - Criou formulário para envio de convites por e-mail com mensagem personalizada  
  - Estilizou os convites com identidade visual do evento

- **Jim (Tester):**  
  - Testou envio de convites com diferentes formatos de e-mail  
  - Validou funcionamento dos botões de compartilhamento em navegadores e dispositivos móveis  
  - Verificou se os links gerados estavam corretos e funcionais

- **Dom (DBA):**  
  - Criou estrutura para armazenar convites enviados e status de entrega  
  - Implementou geração de tokens únicos para cada link compartilhado  
  - Garantiu rastreabilidade e segurança dos acessos aos eventos via convite

- **Carla (Marketing):**  
  - Criou templates de convite com linguagem amigável e visual atrativo  
  - Elaborou sugestões de mensagens para diferentes tipos de eventos  
  - Iniciou campanha de incentivo ao compartilhamento em redes sociais

- **Steven Jobs (Scrum Master & Product Owner):**  
  - Validou critérios de aceitação com foco na clareza e funcionalidade dos convites  
  - Facilitou sessões de alinhamento entre frontend, backend e marketing  
  - Acompanhou testes exploratórios e ajustes finais antes do deploy

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação dos fluxos de convite e compartilhamento                          |
| Testes          | 1 dia   | Validação de envio, links e compatibilidade entre plataformas             |
| Revisão         | 2 dias  | Ajustes visuais, revisão de mensagens e testes de usabilidade             |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações

- Utilizado serviço de e-mail com template HTML para convites personalizados  
- Links de eventos incluem token único para garantir segurança e rastreabilidade  
- Compartilhamento otimizado para dispositivos móveis com pré-visualização do evento  
- Feedback inicial indicou aumento no engajamento após implementação da funcionalidade

---

## 🗓️ Sprint 7 – Confirmação de Presença (RSVP) ♾️  
**📅 Data inicial e final:** 09/10/2025 – 19/10/2025  

### 🎯 Objetivo da Sprint  
Implementar o sistema de confirmação de presença (RSVP), permitindo que convidados confirmem participação nos eventos e que os organizadores acompanhem os status em tempo real com clareza e praticidade.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou tela de confirmação com opções de “Sim”, “Não” e “Talvez”  
  - Implementou visualização de status de presença para o organizador  
  - Adicionou animações e mensagens de agradecimento após confirmação

- **Ruthe (Angular):**  
  - Desenvolveu componente de RSVP com design intuitivo  
  - Implementou lógica para atualizar status em tempo real  
  - Criou painel para o organizador visualizar lista de confirmados

- **Jim (Tester):**  
  - Testou diferentes respostas de convidados e atualização de status  
  - Validou mensagens de confirmação e comportamento em caso de erro  
  - Verificou se o organizador recebia os dados corretamente no painel

- **Dom (DBA):**  
  - Estruturou tabelas para armazenar status de presença por evento e convidado  
  - Implementou lógica de atualização eficiente e segura  
  - Garantiu integridade dos dados em múltiplas confirmações

- **Carla (Marketing):**  
  - Criou mensagens de incentivo à confirmação antecipada  
  - Elaborou conteúdo explicativo sobre como funciona o RSVP  
  - Iniciou campanha de engajamento com foco em participação ativa

- **Steven Jobs (Scrum Master & Product Owner):**  
  - Validou critérios de aceitação com foco na clareza do fluxo de confirmação  
  - Facilitou sessões de refinamento e alinhamento entre as áreas  
  - Acompanhou testes exploratórios e ajustes finais antes do deploy

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação do sistema de RSVP e painel de visualização                       |
| Testes          | 1 dia   | Validação de respostas, atualizações e mensagens                          |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica e testes de usabilidade                |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações

- Implementado sistema de notificações para o organizador ao receber novas confirmações  
- Backend atualizado com controle de status por evento e por convidado  
- Interface preparada para futuras integrações com lembretes automáticos  
- Feedback inicial indicou aumento na taxa de confirmação após envio dos convites
  
---
## **Sprint 8 – Lista de Presentes e Sugestões** ♾️  
**Data inicial e final:** 20/10/2025 – 30/10/2025  

### 🎯 Objetivo da Sprint  
Desenvolver a funcionalidade de lista de presentes, permitindo que o organizador sugira itens e os convidados escolham o que desejam oferecer. Integrar ações de marketing para divulgação da nova funcionalidade e garantir estrutura de dados eficiente no banco.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou tela de lista de presentes com visual por categorias  
  - Implementou seleção de presente com reserva automática  
  - Adicionou animações de confirmação e visualização de itens já escolhidos  

- **Ruthe (Angular):**  
  - Desenvolveu componente de sugestão de presentes com campo de descrição e link externo  
  - Implementou sistema de marcação de itens como “reservado” ou “disponível”  
  - Estilizou a lista com ícones e cores para facilitar a navegação  

- **Jim (Tester):**  
  - Testou o fluxo de sugestão, reserva e visualização dos presentes  
  - Validou comportamento em casos de itens duplicados ou já reservados  
  - Verificou se os dados estavam sendo corretamente atualizados no backend  

- **Carla (Marketing):**  
  - Criou campanha de divulgação da nova funcionalidade nas redes sociais  
  - Produziu conteúdo visual e textual destacando a praticidade da lista de presentes  
  - Planejou ação de engajamento com usuários para coleta de feedback pós-lançamento  

- **Dom (DBA):**  
  - Modelou tabelas específicas para armazenar sugestões, reservas e histórico de presentes  
  - Otimizou queries para garantir performance na visualização em tempo real  
  - Implementou sistema de versionamento para alterações nos itens da lista  


### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação da lista de presentes, lógica de reserva e estrutura de dados     |
| Testes          | 1 dia   | Validação de seleção, reserva e visualização dos itens                    |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica, testes de usabilidade e revisão de queries |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Sistema permite adicionar links de lojas online para facilitar a compra dos presentes.  
- Backend inclui controle de disponibilidade e histórico de alterações.  
- Campanha de marketing será lançada junto ao deploy para maximizar alcance.  
- Banco de dados preparado para escalabilidade e segurança dos dados dos presentes.
  
---

## **Sprint 9 – Comentários e Interações nos Eventos** ♾️  
**Data inicial e final:** 31/10/2025 – 10/11/2025  

### 🎯 Objetivo da Sprint  
Adicionar uma seção de comentários nos eventos, permitindo que convidados interajam, deixem mensagens e façam perguntas diretamente na página do evento. Integrar estratégias de engajamento e garantir estrutura de dados segura e eficiente.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou área de comentários com avatar, nome e mensagem  
  - Implementou envio em tempo real com feedback visual  
  - Adicionou opção de apagar ou editar comentários próprios  

- **Ruthe (Angular):**  
  - Desenvolveu componente de comentários com rolagem automática  
  - Implementou sistema de ordenação por data e destaque para organizador  
  - Estilizou os comentários com bolhas de conversa e ícones personalizados  

- **Jim (Tester):**  
  - Testou envio, edição e exclusão de comentários  
  - Validou comportamento em tempo real e sincronização entre dispositivos  
  - Verificou se os comentários estavam corretamente associados ao evento  

- **Carla (Marketing):**  
  - Criou campanha de engajamento incentivando convidados a interagir nos eventos  
  - Produziu conteúdo explicativo sobre a nova funcionalidade para redes sociais  
  - Planejou ação de coleta de feedback sobre usabilidade da área de comentários  

- **Dom (DBA):**  
  - Modelou tabelas para armazenar comentários com controle de autor e timestamps  
  - Implementou sistema de moderação com flags para ocultação de conteúdo  
  - Otimizou queries para garantir performance em eventos com alto volume de interação  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação da área de comentários, lógica de interação e estrutura de dados  |
| Testes          | 1 dia   | Validação de envio, edição, exclusão e sincronização                      |
| Revisão         | 2 dias  | Ajustes visuais, revisão de segurança, testes de usabilidade e queries    |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Implementado sistema de moderação para o organizador ocultar comentários indesejados.  
- Backend atualizado com timestamps e controle de autor por comentário.  
- Campanha de marketing será lançada junto ao deploy para incentivar uso da funcionalidade.  
- Banco de dados preparado para suportar grande volume de interações com segurança e agilidade.

---
## **Sprint 10 – Galeria de Fotos do Evento** ♾️  
**Data inicial e final:** 11/11/2025 – 21/11/2025  

### 🎯 Objetivo da Sprint  
Criar uma galeria de fotos para cada evento, permitindo que o organizador e os convidados compartilhem imagens antes, durante e após a comemoração. Integrar estratégias de divulgação visual e garantir estrutura de armazenamento segura e eficiente.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Desenvolveu tela de galeria com visual em grade e rolagem suave  
  - Implementou upload de imagens com compressão automática  
  - Adicionou visualizador em tela cheia com zoom e swipe  

- **Ruthe (Angular):**  
  - Criou componente de galeria com preview das imagens  
  - Implementou sistema de upload com barra de progresso  
  - Estilizou a galeria com bordas arredondadas e efeito hover  

- **Jim (Tester):**  
  - Testou upload de diferentes formatos e tamanhos de imagem  
  - Validou visualização em tela cheia e navegação entre fotos  
  - Verificou se as imagens estavam corretamente associadas ao evento e ao autor  

- **Carla (Marketing):**  
  - Criou campanha visual destacando a nova galeria como espaço de memórias compartilhadas  
  - Produziu conteúdo para redes sociais incentivando o envio de fotos pelos convidados  
  - Planejou ação de engajamento com hashtag oficial para eventos BoraJoin  

- **Dom (DBA):**  
  - Configurou estrutura de armazenamento em nuvem com controle de acesso por evento  
  - Implementou sistema de metadados para cada imagem (autor, data, evento)  
  - Otimizou queries para carregamento rápido e seguro das imagens na galeria  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Implementação da galeria, lógica de upload, visualização e estrutura de dados |
| Testes          | 1 dia   | Validação de formatos, visualização e associação correta das imagens      |
| Revisão         | 2 dias  | Ajustes visuais, revisão de performance, testes de usabilidade e queries  |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Utilizado serviço de armazenamento em nuvem para garantir escalabilidade e segurança das imagens.  
- Galeria permite que o organizador destaque fotos favoritas no topo.  
- Campanha de marketing será lançada junto ao deploy com hashtag oficial para promover engajamento.  
- Banco de dados preparado para armazenar metadados e garantir integridade das imagens.

---
## **Sprint 11 – Notificações em Tempo Real** ♾️  
**Data inicial e final:** 22/11/2025 – 02/12/2025  

### 🎯 Objetivo da Sprint  
Implementar sistema de notificações em tempo real para manter os usuários informados sobre atualizações, confirmações e interações nos eventos. Integrar estratégias de comunicação e garantir estrutura de dados eficiente e segura.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Desenvolveu sistema de push notifications para dispositivos móveis  
  - Implementou lógica para notificar sobre confirmações de presença e novos comentários  
  - Adicionou painel de notificações dentro do app com histórico  

- **Ruthe (Angular):**  
  - Criou componente de notificações com ícone dinâmico e contador  
  - Implementou sistema de alertas em tempo real via WebSocket  
  - Estilizou painel de notificações com agrupamento por tipo de evento  

- **Jim (Tester):**  
  - Testou recebimento de notificações em diferentes dispositivos e navegadores  
  - Validou tempo de entrega, duplicidade e clareza das mensagens  
  - Verificou se o histórico de notificações estava sendo corretamente armazenado  

- **Carla (Marketing):**  
  - Planejou campanha de comunicação destacando o novo sistema de notificações  
  - Produziu conteúdo explicativo para redes sociais e onboarding de usuários  
  - Criou estratégia de uso das notificações para aumentar engajamento nos eventos  

- **Dom (DBA):**  
  - Modelou estrutura de banco para armazenar histórico de notificações por usuário  
  - Implementou controle de leitura e categorização das mensagens no banco  
  - Otimizou gatilhos automáticos para garantir entrega eficiente e segura das notificações  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação do sistema de notificações, lógica de envio e estrutura de dados |
| Testes          | 1 dia   | Validação de entrega, clareza e comportamento em tempo real               |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica, testes de performance e queries       |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Utilizado Firebase Cloud Messaging para envio de notificações no app.  
- Backend configurado com gatilhos automáticos para eventos relevantes.  
- Campanha de marketing será lançada junto ao deploy para orientar os usuários sobre o novo recurso.  
- Banco de dados preparado para armazenar e organizar notificações com segurança e escalabilidade.

---
## **Sprint 12 – Personalização de Eventos (Temas e Cores)** ♾️  
**Data inicial e final:** 03/12/2025 – 13/12/2025  

### 🎯 Objetivo da Sprint  
Permitir que os organizadores personalizem seus eventos com temas visuais, cores e estilos únicos para refletir o clima da comemoração. Integrar estratégias de comunicação visual e garantir estrutura de dados para armazenar preferências.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou sistema de seleção de temas com pré-visualização em tempo real  
  - Implementou paleta de cores personalizável para cada evento  
  - Adicionou animações suaves na transição entre estilos  

- **Ruthe (Angular):**  
  - Desenvolveu painel de personalização com opções de layout e cores  
  - Implementou salvamento automático das preferências do usuário  
  - Estilizou os temas com ícones e fontes específicas para cada tipo de evento  

- **Jim (Tester):**  
  - Testou aplicação dos temas em diferentes dispositivos e navegadores  
  - Validou persistência das configurações após login/logout  
  - Verificou se os estilos não afetavam a legibilidade ou usabilidade  

- **Carla (Marketing):**  
  - Criou campanha destacando a personalização como diferencial do BoraJoin  
  - Produziu conteúdo visual com exemplos de temas para inspirar usuários  
  - Planejou ação de engajamento para que usuários compartilhem seus estilos favoritos  

- **Dom (DBA):**  
  - Modelou estrutura de banco para armazenar preferências visuais por evento e usuário  
  - Implementou sistema de recuperação automática das configurações salvas  
  - Otimizou queries para garantir performance na aplicação dos estilos  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Implementação do sistema de personalização visual e estrutura de dados    |
| Testes          | 1 dia   | Validação de temas, cores e comportamento responsivo                      |
| Revisão         | 2 dias  | Ajustes visuais, revisão de UX, testes de acessibilidade e queries        |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

### 📝 Observações  
- Criado sistema de presets para facilitar a escolha de estilos por tipo de evento (casamento, festa, chá de bebê etc.).  
- Backend atualizado para armazenar preferências visuais por usuário e evento.  
- Campanha de marketing será lançada junto ao deploy com exemplos de personalização.  
- Banco de dados preparado para garantir persistência e escalabilidade das configurações visuais.

---

## **Sprint 13 – Timeline do Evento (Agenda e Programação)** ♾️  
**Data inicial e final:** 14/12/2025 – 24/12/2025  

### 🎯 Objetivo da Sprint  
Desenvolver uma timeline interativa para que o organizador possa definir a programação do evento, com horários e atividades detalhadas. Integrar estratégias de comunicação e garantir estrutura de dados eficiente para agendamento.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou componente de timeline com visual horizontal e scroll suave  
  - Implementou campos para adicionar atividades com horário e descrição  
  - Adicionou alertas visuais para atividades próximas do horário atual  

- **Ruthe (Angular):**  
  - Desenvolveu painel de programação com edição dinâmica das atividades  
  - Implementou sistema de ordenação automática por horário  
  - Estilizou a timeline com ícones e cores por tipo de atividade  

- **Jim (Tester):**  
  - Testou criação, edição e exclusão de atividades na timeline  
  - Validou ordenação correta e alertas de conflito de horários  
  - Verificou se a programação era exibida corretamente para convidados  

- **Carla (Marketing):**  
  - Criou conteúdo explicativo sobre como usar a timeline para organizar eventos  
  - Produziu posts com exemplos de agendas para diferentes tipos de comemoração  
  - Planejou ação de engajamento para que usuários compartilhem suas programações  

- **Dom (DBA):**  
  - Modelou estrutura de banco para armazenar atividades com horário e tipo  
  - Implementou controle de conflitos e alertas automáticos no backend  
  - Otimizou queries para exibição em tempo real da programação  


### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação da timeline, lógica de programação e estrutura de dados           |
| Testes          | 1 dia   | Validação de horários, ordenação e exibição correta                       |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica, testes de usabilidade e queries       |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

### 📝 Observações  
- Sistema permite que convidados visualizem a programação em tempo real, com destaque para atividades em andamento.  
- Backend atualizado com estrutura de agenda vinculada ao evento.  
- Campanha de marketing será lançada junto ao deploy com exemplos de uso da timeline.  
- Banco de dados preparado para garantir integridade e performance na exibição da programação.
  
---
## **Sprint 14 – Mapa do Evento e Direcionamento** ♾️  
**Data inicial e final:** 25/12/2025 – 04/01/2026  

### 🎯 Objetivo da Sprint  
Integrar mapas interativos para exibir a localização do evento e oferecer rotas de acesso aos convidados. Integrar estratégias de comunicação visual e garantir estrutura de dados geográficos segura e eficiente.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Implementou integração com Google Maps para exibir o local do evento  
  - Adicionou botão de “Como chegar” com redirecionamento para apps de navegação  
  - Criou marcador personalizado com ícone do evento  

- **Ruthe (Angular):**  
  - Desenvolveu componente de mapa com visualização responsiva  
  - Implementou campo de endereço com autocompletar via API de geolocalização  
  - Estilizou o mapa com tema visual do evento e marcador customizado  

- **Jim (Tester):**  
  - Testou exibição correta do mapa em diferentes dispositivos e navegadores  
  - Validou funcionamento dos links de rota e precisão da geolocalização  
  - Verificou se o endereço inserido era corretamente interpretado e exibido  

- **Carla (Marketing):**  
  - Criou conteúdo explicativo sobre como usar o mapa para chegar ao evento  
  - Produziu posts com dicas de transporte e localização para diferentes tipos de evento  
  - Planejou ação de engajamento com incentivo ao uso do recurso “Como chegar”  

- **Dom (DBA):**  
  - Modelou estrutura de banco para armazenar coordenadas geográficas e endereços  
  - Implementou sistema de cache para reduzir requisições à API de geolocalização  
  - Otimizou queries para busca e exibição rápida da localização nos eventos  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Implementação do mapa, marcador, rotas de acesso e estrutura de dados     |
| Testes          | 1 dia   | Validação de localização, responsividade e integração com apps externos   |
| Revisão         | 2 dias  | Ajustes visuais, revisão de dados, testes de usabilidade e queries        |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Utilizado Google Maps API com chave segura e limites de requisição configurados.  
- Sistema permite salvar o local como favorito para eventos recorrentes.  
- Campanha de marketing será lançada junto ao deploy com orientações de acesso e localização.  
- Banco de dados preparado para armazenar endereços e coordenadas com segurança e performance.
---
## **Sprint 15 – Sistema de Avaliação do Evento** ♾️  
**Data inicial e final:** 05/01/2026 – 15/01/2026  

### 🎯 Objetivo da Sprint  
Criar um sistema de avaliação para que os convidados possam dar feedback sobre o evento, com notas e comentários. Integrar estratégias de engajamento pós-evento e garantir estrutura de dados segura para armazenar avaliações.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Desenvolveu tela de avaliação com estrelas e campo de comentário  
  - Implementou lógica para envio de feedback vinculado ao evento  
  - Adicionou animações de agradecimento após envio da avaliação  

- **Ruthe (Angular):**  
  - Criou componente de avaliação com sistema de notas de 1 a 5 estrelas  
  - Implementou visualização das avaliações para o organizador  
  - Estilizou os cards de feedback com destaque para os mais relevantes  

- **Jim (Tester):**  
  - Testou envio de avaliações com diferentes combinações de nota e comentário  
  - Validou exibição correta das avaliações no painel do organizador  
  - Verificou se o sistema impedia avaliações duplicadas por usuário  

- **Carla (Marketing):**  
  - Criou campanha de incentivo ao feedback com mensagens pós-evento  
  - Produziu conteúdo explicativo sobre a importância das avaliações  
  - Planejou ação de engajamento com destaque para eventos mais bem avaliados  

- **Dom (DBA):**  
  - Modelou estrutura de banco para armazenar notas, comentários e respostas do organizador  
  - Implementou cálculo automático da média de avaliações por evento  
  - Otimizou queries para exibição rápida e segura dos dados no painel do organizador  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação do sistema de avaliação, painel de visualização e estrutura de dados |
| Testes          | 1 dia   | Validação de envio, exibição e controle de duplicidade                    |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica, testes de usabilidade e queries       |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Backend inclui cálculo automático da média de avaliações por evento.  
- Sistema permite que o organizador responda aos comentários dos convidados.  
- Campanha de marketing será lançada junto ao deploy para incentivar avaliações.  
- Banco de dados preparado para garantir integridade, segurança e performance na gestão dos feedbacks.

---
## **Sprint 16 – Histórico de Eventos e Arquivamento** ♾️  
**Data inicial e final:** 16/01/2026 – 26/01/2026  

### 🎯 Objetivo da Sprint  
Implementar uma área de histórico para que os usuários possam visualizar eventos passados e arquivá-los, mantendo o sistema organizado. Integrar estratégias de comunicação pós-evento e garantir estrutura de dados eficiente para arquivamento.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou tela de histórico com listagem cronológica dos eventos anteriores  
  - Implementou botão de arquivamento com confirmação visual  
  - Adicionou filtro por ano e tipo de evento  

- **Ruthe (Angular):**  
  - Desenvolveu componente de histórico com agrupamento por data  
  - Implementou funcionalidade de arquivamento com ícone e tooltip explicativo  
  - Estilizou a interface com separadores visuais entre os períodos  

- **Jim (Tester):**  
  - Testou exibição correta dos eventos arquivados e ativos  
  - Validou funcionamento dos filtros e ordenação  
  - Verificou se os eventos arquivados não apareciam nas buscas principais  

- **Carla (Marketing):**  
  - Criou conteúdo para reforçar a importância do histórico como memória dos eventos  
  - Produziu posts com retrospectivas e sugestões de reutilização de eventos arquivados  
  - Planejou ação de engajamento com destaque para eventos marcantes do ano  

- **Dom (DBA):**  
  - Modelou estrutura de banco com flag de status para eventos ativos e arquivados  
  - Implementou sistema de arquivamento com controle de integridade e acesso restrito  
  - Otimizou queries para filtros por data, tipo e status de arquivamento  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação da área de histórico, lógica de arquivamento e estrutura de dados |
| Testes          | 1 dia   | Validação de filtros, ordenação e comportamento de arquivamento           |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica, testes de usabilidade e queries       |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

### 📝 Observações  
- Eventos arquivados continuam acessíveis para consulta, mas não podem ser editados.  
- Backend atualizado com flag de status para diferenciar eventos ativos e arquivados.  
- Campanha de marketing será lançada junto ao deploy com retrospectiva dos eventos mais marcantes.  
- Banco de dados preparado para garantir performance e segurança na gestão do histórico.

---
## **Sprint 17 – Dashboard do Organizador** ♾️  
**Data inicial e final:** 27/01/2026 – 06/02/2026  

### 🎯 Objetivo da Sprint  
Desenvolver um painel administrativo para o organizador acompanhar métricas, interações e status dos eventos em tempo real. Integrar estratégias de comunicação de resultados e garantir estrutura de dados eficiente para análise.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou tela de dashboard com gráficos de presença, avaliações e interações  
  - Implementou widgets dinâmicos com atualização em tempo real  
  - Adicionou indicadores visuais para eventos ativos e arquivados  

- **Ruthe (Angular):**  
  - Desenvolveu painel com cards informativos e gráficos interativos  
  - Implementou filtros por evento, data e tipo de métrica  
  - Estilizou o dashboard com layout responsivo e visual limpo  

- **Jim (Tester):**  
  - Testou exibição correta dos dados e atualização em tempo real  
  - Validou comportamento dos filtros e precisão das métricas  
  - Verificou se os dados estavam sendo carregados com performance adequada  

- **Carla (Marketing):**  
  - Criou conteúdo explicativo sobre como interpretar os dados do dashboard  
  - Produziu posts com dicas para melhorar engajamento com base nas métricas  
  - Planejou ação de reconhecimento para eventos com alto desempenho  

- **Dom (DBA):**  
  - Modelou estrutura de banco para armazenar métricas agregadas e detalhadas  
  - Implementou endpoints otimizados para consulta de dados em tempo real  
  - Criou sistema de cache para gráficos com grande volume de informações  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                     |
|-----------------|---------|-------------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação do dashboard, lógica de visualização de métricas e estrutura de dados |
| Testes          | 1 dia   | Validação de gráficos, filtros e atualização dos dados                        |
| Revisão         | 2 dias  | Ajustes visuais, revisão de performance, testes de usabilidade e queries      |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                       |

### 📝 Observações  
- Utilizado biblioteca de gráficos para visualização interativa (Chart.js / Flutter Charts).  
- Backend otimizado com endpoints específicos para métricas agregadas.  
- Campanha de marketing será lançada junto ao deploy com orientações sobre uso do dashboard.  
- Banco de dados preparado para garantir performance, escalabilidade e segurança na análise dos eventos.

---
## **Sprint 18 – Integração com Redes Sociais** ♾️  
**Data inicial e final:** 18/02/2026 – 28/02/2026  

### 🎯 Objetivo da Sprint  
Permitir que os usuários compartilhem seus eventos diretamente em redes sociais como Instagram, Facebook e Twitter, ampliando o alcance das comemorações. Garantir visual atrativo, segurança dos dados e engajamento estratégico.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Implementou botões de compartilhamento nativo para redes sociais  
  - Criou templates visuais para posts com imagem, nome e data do evento  
  - Adicionou opção de copiar link personalizado para o evento  

- **Ruthe (Angular):**  
  - Desenvolveu componente de integração com APIs sociais  
  - Implementou sistema de geração de imagem do evento para compartilhamento  
  - Estilizou os botões com ícones oficiais e animações de hover  

- **Jim (Tester):**  
  - Testou compartilhamento em diferentes redes e dispositivos  
  - Validou funcionamento dos links e visualização correta dos templates  
  - Verificou se os dados compartilhados estavam atualizados e seguros  

- **Carla (Marketing):**  
  - Criou campanha de divulgação destacando a nova funcionalidade de compartilhamento  
  - Produziu exemplos de posts para incentivar os usuários a promoverem seus eventos  
  - Planejou ação de engajamento com hashtag oficial e destaque para eventos públicos  

- **Dom (DBA):**  
  - Atualizou estrutura de banco para armazenar metadados de compartilhamento  
  - Implementou controle de privacidade para impedir divulgação de eventos privados  
  - Configurou suporte ao protocolo Open Graph para visualização otimizada nas redes  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação dos fluxos de compartilhamento e integração com redes sociais     |
| Testes          | 1 dia   | Validação de links, templates e compatibilidade entre plataformas         |
| Revisão         | 2 dias  | Ajustes visuais, revisão de segurança e testes de usabilidade             |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

### 📝 Observações  
- Utilizado Open Graph para garantir visualização otimizada dos eventos ao serem compartilhados.  
- Sistema inclui controle de privacidade para evitar divulgação de eventos privados.  
- Campanha de marketing será lançada junto ao deploy com hashtag oficial e exemplos de uso.  
- Banco de dados preparado para registrar interações e garantir segurança dos dados compartilhados.

---
## **Sprint 19 – Sistema de Backup e Recuperação de Dados** ♾️  
**Data inicial e final:** 29/02/2026 – 10/03/2026  

### 🎯 Objetivo da Sprint  
Implementar um sistema de backup automático e recuperação de dados para garantir segurança e integridade das informações dos eventos. Incluir comunicação clara com os usuários e estrutura robusta no banco de dados.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou interface para o usuário solicitar recuperação de dados  
  - Implementou notificações sobre status de backup e restauração  
  - Adicionou mensagens informativas sobre segurança e privacidade  

- **Ruthe (Angular):**  
  - Desenvolveu painel administrativo com controle de backups por evento  
  - Implementou visualização de logs de backup e opção de restauração manual  
  - Estilizou a interface com ícones de status e alertas visuais  

- **Jim (Tester):**  
  - Testou criação e restauração de backups em diferentes cenários  
  - Validou integridade dos dados após recuperação  
  - Verificou se o sistema prevenia duplicações ou perdas durante o processo  

- **Carla (Marketing):**  
  - Criou conteúdo explicativo sobre o funcionamento do sistema de backup  
  - Produziu materiais de comunicação destacando a segurança da plataforma  
  - Planejou campanha de conscientização sobre boas práticas de proteção de dados  

- **Dom (DBA):**  
  - Configurou rotinas automáticas de backup com criptografia e redundância  
  - Implementou sistema de logs detalhados para auditoria e rastreabilidade  
  - Testou recuperação em ambiente isolado para garantir confiabilidade dos dados  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação do sistema de backup e recuperação de dados                       |
| Testes          | 1 dia   | Validação de integridade, segurança e comportamento em falhas             |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica e testes de confiabilidade             |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

### 📝 Observações  
- Backups são realizados automaticamente a cada 24h e armazenados em ambiente seguro.  
- Sistema inclui logs detalhados para auditoria e rastreabilidade.  
- Comunicação com o usuário reforça a transparência e confiança na proteção dos dados.  
- Banco de dados preparado para recuperação rápida e sem perdas em caso de falhas.

---
## **Sprint 20 – Sistema de Pagamentos e Contribuições** ♾️  
**Data inicial e final:** 11/03/2026 – 21/03/2026  

### 🎯 Objetivo da Sprint  
Desenvolver uma funcionalidade para que convidados possam contribuir financeiramente com o evento, seja para presentes, organização ou causas especiais. Garantir segurança nas transações e comunicação clara com os usuários.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou tela de contribuição com opções de valor e método de pagamento  
  - Implementou integração com gateway de pagamento (ex: Stripe ou Mercado Pago)  
  - Adicionou recibo digital e histórico de contribuições no perfil do usuário  

- **Ruthe (Angular):**  
  - Desenvolveu componente de pagamento com validação de dados sensíveis  
  - Implementou painel para o organizador acompanhar as contribuições recebidas  
  - Estilizou a interface com ícones de segurança e feedback visual  

- **Jim (Tester):**  
  - Testou pagamentos com diferentes valores e métodos (cartão, boleto, etc.)  
  - Validou segurança dos dados e mensagens de erro em transações falhas  
  - Verificou se os valores eram corretamente registrados e exibidos no painel  

- **Carla (Marketing):**  
  - Criou campanha explicando como os convidados podem contribuir com o evento  
  - Produziu conteúdo destacando a segurança e praticidade do sistema de pagamentos  
  - Planejou ação promocional com incentivo à contribuição para metas especiais  

- **Dom (DBA):**  
  - Modelou estrutura de banco para armazenar transações e vincular contribuições a eventos  
  - Implementou criptografia de dados sensíveis e controle de acesso às informações financeiras  
  - Configurou auditoria de transações e suporte a múltiplos métodos de pagamento  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação do sistema de pagamentos e painel de acompanhamento               |
| Testes          | 1 dia   | Validação de transações, segurança e exibição correta dos dados           |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica e testes de confiabilidade             |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Sistema inclui criptografia de dados sensíveis e autenticação em dois fatores para transações.  
- Contribuições podem ser vinculadas a metas específicas definidas pelo organizador.  
- Campanha de marketing será lançada junto ao deploy com instruções e incentivo à participação.  
- Banco de dados preparado para garantir rastreabilidade, segurança e escalabilidade das transações.

---
## **Sprint 21 – Relatórios e Exportação de Dados** ♾️  
**Data inicial e final:** 22/03/2026 – 01/04/2026  

### 🎯 Objetivo da Sprint  
Implementar geração de relatórios detalhados sobre os eventos, com opção de exportar dados em formatos como PDF ou Excel para fins de análise ou registro. Garantir clareza visual, precisão dos dados e utilidade estratégica.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Criou tela de geração de relatórios com filtros por data e tipo de evento  
  - Implementou exportação em PDF com layout personalizado  
  - Adicionou opção de envio do relatório por e-mail diretamente do app  

- **Ruthe (Angular):**  
  - Desenvolveu painel de relatórios com visualização tabular e gráfica  
  - Implementou exportação em Excel com estrutura organizada por colunas  
  - Estilizou os relatórios com cabeçalhos, logotipo do evento e rodapé informativo  

- **Jim (Tester):**  
  - Testou geração de relatórios com diferentes filtros e formatos  
  - Validou conteúdo exportado e compatibilidade com leitores de PDF/Excel  
  - Verificou se os dados estavam completos, atualizados e corretamente formatados  

- **Carla (Marketing):**  
  - Criou modelos de relatórios para uso em campanhas e prestação de contas  
  - Produziu conteúdo explicativo sobre como interpretar os dados dos eventos  
  - Planejou ação de divulgação destacando o valor dos relatórios para organizadores  

- **Dom (DBA):**  
  - Estruturou queries para geração eficiente de relatórios com dados consolidados  
  - Implementou controle de acesso aos relatórios com permissões por perfil  
  - Configurou agendamento automático de envio de relatórios periódicos  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação dos relatórios e lógica de exportação                             |
| Testes          | 1 dia   | Validação de conteúdo, formato e compatibilidade                          |
| Revisão         | 2 dias  | Ajustes visuais, revisão de dados e testes de usabilidade                 |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

### 📝 Observações  
- Relatórios incluem métricas de presença, avaliações, contribuições e interações.  
- Sistema permite agendamento de envio automático de relatórios periódicos.  
- Banco de dados otimizado para gerar relatórios com rapidez e precisão.  
- Comunicação reforça o uso estratégico dos dados para melhorar eventos futuros.

---
## **Sprint 22 – Acessibilidade e Inclusão Digital** ♾️  
**Data inicial e final:** 02/04/2026 – 12/04/2026  

### 🎯 Objetivo da Sprint  
Garantir que o BoraJoin seja acessível para todos os usuários, incluindo pessoas com deficiência visual, auditiva ou motora, seguindo boas práticas de inclusão digital. Promover uma experiência justa, intuitiva e acolhedora.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Implementou suporte a leitores de tela e navegação por teclado  
  - Adicionou contraste elevado e fontes ajustáveis nas telas principais  
  - Criou opção de descrição alternativa para imagens e ícones  

- **Ruthe (Angular):**  
  - Desenvolveu componentes com foco em acessibilidade (WCAG 2.1)  
  - Implementou navegação por tabulação e atalhos de teclado  
  - Estilizou elementos com foco visual e feedback sonoro opcional  

- **Jim (Tester):**  
  - Testou compatibilidade com tecnologias assistivas (NVDA, VoiceOver)  
  - Validou contraste, legibilidade e navegação sem mouse  
  - Verificou se todos os elementos interativos estavam acessíveis e descritos corretamente  

- **Carla (Marketing):**  
  - Criou campanha institucional destacando o compromisso com inclusão digital  
  - Produziu conteúdo explicativo sobre os recursos de acessibilidade disponíveis  
  - Planejou ação de engajamento com depoimentos de usuários beneficiados pelas melhorias  

- **Dom (DBA):**  
  - Atualizou estrutura de banco para armazenar preferências de acessibilidade por usuário  
  - Implementou suporte a logs de uso para análise de acessibilidade e melhoria contínua  
  - Garantiu que os dados de acessibilidade fossem tratados com segurança e privacidade  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Implementação de recursos de acessibilidade e ajustes visuais             |
| Testes          | 1 dia   | Validação com ferramentas assistivas e simulações de uso real             |
| Revisão         | 2 dias  | Ajustes de acessibilidade, revisão de UX e testes de inclusão             |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

### 📝 Observações  
- Projeto passou por auditoria interna de acessibilidade com checklist completo.  
- Inclusão digital é parte do compromisso do BoraJoin com experiências memoráveis para todos.  
- Preferências de acessibilidade são salvas por perfil e aplicadas automaticamente.  
- Comunicação reforça a importância da acessibilidade como valor central da plataforma.

---
## **Sprint 23 – Modo Offline e Sincronização de Dados** ♾️  
**Data inicial e final:** 13/04/2026 – 23/04/2026  

### 🎯 Objetivo da Sprint  
Permitir que os usuários acessem informações dos eventos mesmo sem conexão à internet, com sincronização automática assim que a conexão for restabelecida. Garantir continuidade da experiência e integridade dos dados.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Implementou cache local para dados essenciais dos eventos  
  - Criou lógica de sincronização automática ao reconectar  
  - Adicionou indicadores visuais de status de conexão e sincronização  

- **Ruthe (Angular):**  
  - Desenvolveu sistema de armazenamento local com IndexedDB  
  - Implementou fila de ações offline (ex: RSVP, comentários) para envio posterior  
  - Estilizou alertas informando ao usuário que está em modo offline  

- **Jim (Tester):**  
  - Testou funcionamento offline em diferentes navegadores e dispositivos  
  - Validou sincronização de dados após reconexão  
  - Verificou se não havia perda ou duplicação de informações durante o processo  

- **Carla (Marketing):**  
  - Criou campanha destacando o novo recurso como solução para eventos em áreas com pouca conectividade  
  - Produziu conteúdo explicativo sobre como o modo offline funciona e seus benefícios  
  - Planejou ação de engajamento com foco em tranquilidade e autonomia dos usuários  

- **Dom (DBA):**  
  - Estruturou banco para suportar armazenamento temporário e sincronização segura  
  - Implementou verificação de conflitos e lógica de resolução automática  
  - Garantiu que os dados sincronizados fossem auditáveis e rastreáveis  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Criação do modo offline e lógica de sincronização                         |
| Testes          | 1 dia   | Validação de cache, reconexão e integridade dos dados                     |
| Revisão         | 2 dias  | Ajustes visuais, revisão de lógica e testes de confiabilidade             |
| Deploy          | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |


### 📝 Observações  
- Sistema prioriza dados críticos como programação, localização e RSVP para acesso offline.  
- Sincronização inclui verificação de conflitos e resolução automática.  
- Comunicação reforça a autonomia do usuário em qualquer situação de conectividade.  
- Banco de dados preparado para garantir consistência e segurança na transição entre estados online e offline.

---
## **Sprint 24 – Finalização, Otimização e Lançamento Oficial** ♾️  
**Data inicial e final:** 24/04/2026 – 04/05/2026  

### 🎯 Objetivo da Sprint  
Realizar os ajustes finais, otimizar performance, revisar toda a aplicação e preparar o BoraJoin para seu lançamento oficial. Garantir estabilidade, comunicação clara e estrutura robusta para escalar.

### 👨‍💻 O que cada integrante fez

- **Wesley (Flutter):**  
  - Revisou todas as telas e corrigiu inconsistências visuais  
  - Otimizou tempo de carregamento e uso de memória no app  
  - Preparou versão final para publicação nas lojas (Google Play e App Store)  

- **Ruthe (Angular):**  
  - Realizou revisão completa do frontend web, ajustando responsividade e acessibilidade  
  - Minificou arquivos e otimizou carregamento de recursos  
  - Configurou domínio oficial e hospedagem para o lançamento  

- **Jim (Tester):**  
  - Executou testes de regressão em todas as funcionalidades  
  - Validou performance, segurança e compatibilidade cross-browser  
  - Gerou relatório final de qualidade com checklist de aprovação  

- **Carla (Marketing):**  
  - Lançou campanha oficial de divulgação com vídeos, posts e press release  
  - Organizou evento de lançamento com demonstração ao vivo da plataforma  
  - Criou materiais de onboarding para novos usuários e parceiros  

- **Dom (DBA):**  
  - Realizou auditoria final no banco de dados e otimizou índices para performance  
  - Configurou backups de produção e monitoramento em tempo real  
  - Garantiu escalabilidade da estrutura para suportar aumento de usuários após o lançamento  

### 📅 Cronograma da Sprint

| Fase            | Duração | Descrição                                                                 |
|-----------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento | 5 dias  | Revisão geral, otimizações e preparação para publicação                   |
| Testes          | 1 dia   | Testes finais de regressão, performance e segurança                       |
| Revisão         | 2 dias  | Validação visual, ajustes finais e checklist de lançamento                |
| Deploy          | 1 dia   | Publicação oficial nas lojas e servidores                                 |


### 📝 Observações  
- BoraJoin foi lançado oficialmente com versão estável, documentação completa e suporte integrado.  
- Equipe celebrou com um evento interno usando o próprio sistema — testado e aprovado!  
- Infraestrutura preparada para escalar com segurança e eficiência.  
- Campanha de lançamento reforça os valores de inovação, inclusão e celebração.

---

## Quantidade total de Sprints:  
**24 Sprints** – distribuídas entre planejamento, desenvolvimento de funcionalidades, testes, ajustes e deploy final.

---

## 🧠 Reflexão da Equipe – Metodologia Ágil no BoraJoin

### ✅ Vantagens percebidas:

- **Maior organização e foco:** As sprints curtas e bem definidas ajudaram a manter o time alinhado e produtivo, com metas claras a cada ciclo.
- **Flexibilidade para mudanças:** A metodologia permitiu ajustes rápidos conforme novas ideias surgiam ou necessidades mudavam.
- **Feedback constante:** A validação contínua com testes e revisões garantiu qualidade e evolução constante do produto.
- **Colaboração intensa:** A divisão de tarefas e reuniões regulares fortaleceram a comunicação entre os membros, mesmo em ambientes remotos.
- **Entrega contínua de valor:** A cada sprint, funcionalidades reais eram entregues, o que manteve o projeto motivador e tangível.

---

### ⚠️ Dificuldades enfrentadas:

- **Estimativas iniciais imprecisas:** Algumas sprints exigiram mais tempo do que o previsto, especialmente nas fases de integração e testes.
- **Adaptação ao ritmo ágil:** No início, foi desafiador manter o ritmo de entregas sem comprometer a qualidade ou gerar sobrecarga.
- **Dependência entre tarefas:** Algumas funcionalidades estavam interligadas, o que exigiu replanejamento constante para evitar bloqueios.
- **Documentação paralela:** Manter a documentação atualizada ao longo das sprints exigiu disciplina e tempo extra da equipe.

---

### 🎯 Conclusão:

---

## ✅ Conclusão do Ciclo de Sprints

Desenvolver o BoraJoin foi um processo intenso e desafiador. Cada sprint exigiu dedicação, colaboração multidisciplinar e atenção aos mínimos detalhes — afinal, criar uma plataforma completa, segura e acessível para celebrações não é tarefa simples.

Ao longo das 24 sprints, enfrentamos decisões técnicas complexas, refinamentos constantes e validações rigorosas. A magnitude do projeto exigiu não apenas esforço técnico, mas também organização estratégica e comunicação contínua.

Para garantir alinhamento e transparência, realizamos reuniões com os stakeholders ao final de cada sprint. Nessas sessões, apresentamos os avanços, coletamos feedback e ajustamos prioridades, mantendo o BoraJoin fiel à sua missão: tornar cada evento uma experiência memorável.

O resultado é uma plataforma robusta, inclusiva e pronta para escalar — construída com muito trabalho, visão coletiva e paixão por celebrar. A equipe acredita que o modelo incremental e colaborativo trouxe mais maturidade ao processo de desenvolvimento, permitindo que o produto evoluísse com qualidade, propósito e visão de longo prazo.



