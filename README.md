# BoraJoin 🎆

## **Nome dos integrantes:** 👨‍💻  
+ _Scrum Master: Steven Jobs_  
+ _Product Owner: Steven Jobs_  
+ _Scrum Team: Desenvolvedor Flutter – Wesley_  
+ _Scrum Team: Tester – Jim_  
+ _Scrum Team: Desenvolvedora Angular – Ruthe_

---

## Tecnologias utilizadas: 👨‍💻  
* 👉 **Flutter**: para desenvolvimento multiplataforma de aplicativos móveis com visual atraente e responsivo  
* 👉 **Angular**: para construção da interface web dinâmica e interativa  
* 👉 **Java + Spring Boot**: formando o backend da aplicação, responsável pelo processamento de dados, segurança, integração com serviços externos e gerenciamento das funcionalidades essenciais do sistema

---

## Descrição do projeto:  
#### *BoraJoin é um sistema completo para criação e gerenciamento de eventos que abrange tanto aplicativo móvel como página web.*  
#### *Com o BoraJoin é possível ter uma experiência intuitiva e personalizada para organizar eventos como casamentos, chás de bebê, festas de inauguração e muito mais — tudo de forma prática, rápida e sem complicações.*  
#### *Além disso, cada detalhe da sua comemoração é planejado com facilidade, tornando cada evento único e inesquecível.*  
#### ***Junte-se. Comemore. BoraJoin.***

---

## **Sprints ♾️:**

## **Sprint 1 – Setup do Projeto** ♾️  
**Data inicial e final:** 04/08/2025 – 14/08/2025  

---

### 🎯 Objetivo da Sprint:  
Configurar o ambiente de desenvolvimento, repositório e ferramentas de controle de versão para iniciar o projeto BoraJoin.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Configuração dos ambientes, estrutura inicial e primeiras telas           |
| Testes             | 1 dia   | Validação de rotas, responsividade e funcionamento básico                 |
| Revisão            | 2 dias  | Ajustes finos no layout, estrutura de pastas e documentação inicial       |
| Deploy             | 1 dia   | Publicação da versão inicial em ambiente de homologação                   |

---

### 📝 Observações:  
- Todos os ambientes foram integrados com GitHub Actions para facilitar o CI/CD nas próximas Sprints.  
- A comunicação entre os membros foi feita via Discord e Trello, com reuniões diárias de 15 minutos.

---
## **Sprint 2 – Cadastro de Usuário e Autenticação** ♾️  
**Data inicial e final:** 15/08/2025 – 25/08/2025  

---

### 🎯 Objetivo da Sprint:  
Implementar o sistema de cadastro de usuários, autenticação segura e integração entre frontend e backend.

---

### 👨‍💻 O que cada desenvolvedor fez:

- **Wesley (Flutter):**  
  - Criou telas de login e cadastro com validação de campos  
  - Implementou integração com API de autenticação  
  - Adicionou feedback visual para erros e sucesso no login  

- **Ruthe (Angular):**  
  - Desenvolveu componentes de login e cadastro na interface web  
  - Aplicou validações reativas nos formulários  
  - Estilizou os componentes com responsividade e acessibilidade  

- **Jim (Tester):**  
  - Criou testes automatizados para fluxo de login e cadastro  
  - Testou falhas de autenticação e mensagens de erro  
  - Validou integração entre frontend e backend com dados reais

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação das telas, formulários e integração com backend                   |
| Testes             | 1 dia   | Validação de autenticação, segurança e usabilidade                        |
| Revisão            | 2 dias  | Ajustes visuais, melhorias na UX e revisão de código                      |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado JWT para autenticação segura entre cliente e servidor.  
- Criado middleware no backend para proteger rotas privadas.

---
## **Sprint 3 – Criação de Eventos** ♾️  
**Data inicial e final:** 26/08/2025 – 05/09/2025  

---

### 🎯 Objetivo da Sprint:  
Desenvolver a funcionalidade de criação de eventos, permitindo ao usuário cadastrar informações como nome, data, local e tipo de evento.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Implementação dos formulários e lógica de criação de eventos              |
| Testes             | 1 dia   | Validação de campos, comportamento e integração com backend               |
| Revisão            | 2 dias  | Ajustes visuais, melhorias na UX e revisão de código                      |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Criado modelo de dados no backend para armazenar eventos com campos personalizáveis.  
- Utilizado serviço de geolocalização para sugestão de locais próximos.

---
## **Sprint 4 – Listagem e Visualização de Eventos** ♾️  
**Data inicial e final:** 06/09/2025 – 16/09/2025  

---

### 🎯 Objetivo da Sprint:  
Implementar a listagem dos eventos criados e permitir a visualização detalhada de cada evento, com layout atrativo e navegação fluida.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação das telas de listagem e visualização de eventos                   |
| Testes             | 1 dia   | Validação da navegação, filtros e exibição correta dos dados              |
| Revisão            | 2 dias  | Ajustes visuais, melhorias na performance e revisão de código             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado scroll infinito na listagem para melhor performance em dispositivos móveis.  
- Backend otimizado com paginação e ordenação por data.

---
## **Sprint 5 – Edição e Exclusão de Eventos** ♾️  
**Data inicial e final:** 17/09/2025 – 27/09/2025  

---

### 🎯 Objetivo da Sprint:  
Permitir que os usuários editem ou excluam eventos já criados, garantindo flexibilidade e controle total sobre suas comemorações.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Implementação das funcionalidades de edição e exclusão de eventos         |
| Testes             | 1 dia   | Validação dos fluxos, mensagens e persistência dos dados                  |
| Revisão            | 2 dias  | Ajustes visuais, revisão de segurança e tratamento de erros               |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Implementado controle de permissões para garantir que apenas o criador do evento possa editá-lo ou excluí-lo.  
- Backend atualizado com rotas específicas para PUT e DELETE.

---
## **Sprint 6 – Convites e Compartilhamento de Eventos** ♾️  
**Data inicial e final:** 28/09/2025 – 08/10/2025  

---

### 🎯 Objetivo da Sprint:  
Desenvolver a funcionalidade de envio de convites e compartilhamento de eventos com amigos e familiares por diferentes canais.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação dos fluxos de convite e compartilhamento                          |
| Testes             | 1 dia   | Validação de envio, links e compatibilidade entre plataformas             |
| Revisão            | 2 dias  | Ajustes visuais, revisão de mensagens e testes de usabilidade             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado serviço de e-mail com template HTML para convites personalizados.  
- Links de eventos incluem token único para garantir segurança e rastreabilidade.

---

## **Sprint 7 – Confirmação de Presença (RSVP)** ♾️  
**Data inicial e final:** 09/10/2025 – 19/10/2025  

---

### 🎯 Objetivo da Sprint:  
Implementar o sistema de confirmação de presença (RSVP), permitindo que convidados confirmem participação nos eventos e visualizem detalhes importantes.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do sistema de RSVP e painel de visualização                       |
| Testes             | 1 dia   | Validação de respostas, atualizações e mensagens                          |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de usabilidade                |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Implementado sistema de notificações para o organizador ao receber novas confirmações.  
- Backend atualizado com controle de status por evento e por convidado.

---
## **Sprint 8 – Lista de Presentes e Sugestões** ♾️  
**Data inicial e final:** 20/10/2025 – 30/10/2025  

---

### 🎯 Objetivo da Sprint:  
Desenvolver a funcionalidade de lista de presentes, permitindo que o organizador sugira itens e os convidados escolham o que desejam oferecer.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação da lista de presentes e lógica de reserva                         |
| Testes             | 1 dia   | Validação de seleção, reserva e visualização dos itens                    |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de usabilidade                |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Sistema permite adicionar links de lojas online para facilitar a compra dos presentes.  
- Backend inclui controle de disponibilidade e histórico de alterações.

---
## **Sprint 9 – Comentários e Interações nos Eventos** ♾️  
**Data inicial e final:** 31/10/2025 – 10/11/2025  

---

### 🎯 Objetivo da Sprint:  
Adicionar uma seção de comentários nos eventos, permitindo que convidados interajam, deixem mensagens e façam perguntas diretamente na página do evento.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação da área de comentários e lógica de interação                      |
| Testes             | 1 dia   | Validação de envio, edição, exclusão e sincronização                      |
| Revisão            | 2 dias  | Ajustes visuais, revisão de segurança e testes de usabilidade             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Implementado sistema de moderação para o organizador ocultar comentários indesejados.  
- Backend atualizado com timestamps e controle de autor por comentário.

---
## **Sprint 10 – Galeria de Fotos do Evento** ♾️  
**Data inicial e final:** 11/11/2025 – 21/11/2025  

---

### 🎯 Objetivo da Sprint:  
Criar uma galeria de fotos para cada evento, permitindo que o organizador e os convidados compartilhem imagens antes, durante e após a comemoração.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Implementação da galeria e lógica de upload e visualização                |
| Testes             | 1 dia   | Validação de formatos, visualização e associação correta das imagens      |
| Revisão            | 2 dias  | Ajustes visuais, revisão de performance e testes de usabilidade           |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado serviço de armazenamento em nuvem para garantir escalabilidade e segurança das imagens.  
- Galeria permite que o organizador destaque fotos favoritas no topo.

---
## **Sprint 11 – Notificações em Tempo Real** ♾️  
**Data inicial e final:** 22/11/2025 – 02/12/2025  

---

### 🎯 Objetivo da Sprint:  
Implementar sistema de notificações em tempo real para manter os usuários informados sobre atualizações, confirmações e interações nos eventos.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do sistema de notificações e lógica de envio                      |
| Testes             | 1 dia   | Validação de entrega, clareza e comportamento em tempo real               |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de performance                |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado Firebase Cloud Messaging para envio de notificações no app.  
- Backend configurado com gatilhos automáticos para eventos relevantes.

---
## **Sprint 12 – Personalização de Eventos (Temas e Cores)** ♾️  
**Data inicial e final:** 03/12/2025 – 13/12/2025  

---

### 🎯 Objetivo da Sprint:  
Permitir que os organizadores personalizem seus eventos com temas visuais, cores e estilos únicos para refletir o clima da comemoração.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Implementação do sistema de personalização visual                         |
| Testes             | 1 dia   | Validação de temas, cores e comportamento responsivo                      |
| Revisão            | 2 dias  | Ajustes visuais, revisão de UX e testes de acessibilidade                 |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Criado sistema de presets para facilitar a escolha de estilos por tipo de evento (casamento, festa, chá de bebê etc.).  
- Backend atualizado para armazenar preferências visuais por usuário e evento.

---
## **Sprint 13 – Timeline do Evento (Agenda e Programação)** ♾️  
**Data inicial e final:** 14/12/2025 – 24/12/2025  

---

### 🎯 Objetivo da Sprint:  
Desenvolver uma timeline interativa para que o organizador possa definir a programação do evento, com horários e atividades detalhadas.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação da timeline e lógica de programação do evento                     |
| Testes             | 1 dia   | Validação de horários, ordenação e exibição correta                       |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de usabilidade                |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Sistema permite que convidados visualizem a programação em tempo real, com destaque para atividades em andamento.  
- Backend atualizado com estrutura de agenda vinculada ao evento.

---
## **Sprint 14 – Mapa do Evento e Direcionamento** ♾️  
**Data inicial e final:** 25/12/2025 – 04/01/2026  

---

### 🎯 Objetivo da Sprint:  
Integrar mapas interativos para exibir a localização do evento e oferecer rotas de acesso aos convidados.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Implementação do mapa, marcador e rotas de acesso                         |
| Testes             | 1 dia   | Validação de localização, responsividade e integração com apps externos   |
| Revisão            | 2 dias  | Ajustes visuais, revisão de dados e testes de usabilidade                 |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado Google Maps API com chave segura e limites de requisição configurados.  
- Sistema permite salvar o local como favorito para eventos recorrentes.

---
## **Sprint 15 – Sistema de Avaliação do Evento** ♾️  
**Data inicial e final:** 05/01/2026 – 15/01/2026  

---

### 🎯 Objetivo da Sprint:  
Criar um sistema de avaliação para que os convidados possam dar feedback sobre o evento, com notas e comentários.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do sistema de avaliação e painel de visualização                  |
| Testes             | 1 dia   | Validação de envio, exibição e controle de duplicidade                    |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de usabilidade                |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Backend inclui cálculo automático da média de avaliações por evento.  
- Sistema permite que o organizador responda aos comentários dos convidados.

---
## **Sprint 16 – Histórico de Eventos e Arquivamento** ♾️  
**Data inicial e final:** 16/01/2026 – 26/01/2026  

---

### 🎯 Objetivo da Sprint:  
Implementar uma área de histórico para que os usuários possam visualizar eventos passados e arquivá-los, mantendo o sistema organizado.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação da área de histórico e lógica de arquivamento                     |
| Testes             | 1 dia   | Validação de filtros, ordenação e comportamento de arquivamento           |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de usabilidade                |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Eventos arquivados continuam acessíveis para consulta, mas não podem ser editados.  
- Backend atualizado com flag de status para diferenciar eventos ativos e arquivados.

---
## **Sprint 17 – Dashboard do Organizador** ♾️  
**Data inicial e final:** 27/01/2026 – 06/02/2026  

---

### 🎯 Objetivo da Sprint:  
Desenvolver um painel administrativo para o organizador acompanhar métricas, interações e status dos eventos em tempo real.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do dashboard e lógica de visualização de métricas                 |
| Testes             | 1 dia   | Validação de gráficos, filtros e atualização dos dados                    |
| Revisão            | 2 dias  | Ajustes visuais, revisão de performance e testes de usabilidade           |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado biblioteca de gráficos para visualização interativa (Chart.js / Flutter Charts).  
- Backend otimizado com endpoints específicos para métricas agregadas.

---
## **Sprint 18 – Sistema de Mensagens Privadas** ♾️  
**Data inicial e final:** 07/02/2026 – 17/02/2026  

---

### 🎯 Objetivo da Sprint:  
Implementar um sistema de mensagens privadas entre organizadores e convidados, permitindo comunicação direta e segura dentro da plataforma.

---

### 👨‍💻 O que cada desenvolvedor fez:

- **Wesley (Flutter):**  
  - Desenvolveu tela de mensagens com visual estilo chat  
  - Implementou envio e recebimento em tempo real com WebSocket  
  - Adicionou notificações internas para novas mensagens recebidas  

- **Ruthe (Angular):**  
  - Criou componente de mensagens com histórico e rolagem automática  
  - Implementou sistema de leitura e status de entrega das mensagens  
  - Estilizou a interface com bolhas de conversa e separadores por data  

- **Jim (Tester):**  
  - Testou envio e recebimento de mensagens entre diferentes perfis  
  - Validou sincronização em tempo real e status de leitura  
  - Verificou se as mensagens estavam corretamente associadas aos usuários e eventos

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do sistema de mensagens e lógica de comunicação privada           |
| Testes             | 1 dia   | Validação de envio, leitura, entrega e sincronização                      |
| Revisão            | 2 dias  | Ajustes visuais, revisão de segurança e testes de performance             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Sistema inclui criptografia de mensagens para garantir privacidade.  
- Backend atualizado com estrutura de conversas e controle de status por mensagem.

---
## **Sprint 19 – Integração com Redes Sociais** ♾️  
**Data inicial e final:** 18/02/2026 – 28/02/2026  

---

### 🎯 Objetivo da Sprint:  
Permitir que os usuários compartilhem seus eventos diretamente em redes sociais como Instagram, Facebook e Twitter, ampliando o alcance das comemorações.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação dos fluxos de compartilhamento e integração com redes sociais     |
| Testes             | 1 dia   | Validação de links, templates e compatibilidade entre plataformas         |
| Revisão            | 2 dias  | Ajustes visuais, revisão de segurança e testes de usabilidade             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Utilizado Open Graph para garantir visualização otimizada dos eventos ao serem compartilhados.  
- Sistema inclui controle de privacidade para evitar divulgação de eventos privados.

---
## **Sprint 20 – Sistema de Backup e Recuperação de Dados** ♾️  
**Data inicial e final:** 29/02/2026 – 10/03/2026  

---

### 🎯 Objetivo da Sprint:  
Implementar um sistema de backup automático e recuperação de dados para garantir segurança e integridade das informações dos eventos.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do sistema de backup e recuperação de dados                       |
| Testes             | 1 dia   | Validação de integridade, segurança e comportamento em falhas             |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de confiabilidade             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Backups são realizados automaticamente a cada 24h e armazenados em ambiente seguro.  
- Sistema inclui logs detalhados para auditoria e rastreabilidade.

---
## **Sprint 21 – Sistema de Pagamentos e Contribuições** ♾️  
**Data inicial e final:** 11/03/2026 – 21/03/2026  

---

### 🎯 Objetivo da Sprint:  
Desenvolver uma funcionalidade para que convidados possam contribuir financeiramente com o evento, seja para presentes, organização ou causas especiais.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do sistema de pagamentos e painel de acompanhamento               |
| Testes             | 1 dia   | Validação de transações, segurança e exibição correta dos dados           |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de confiabilidade             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Sistema inclui criptografia de dados sensíveis e autenticação em dois fatores para transações.  
- Contribuições podem ser vinculadas a metas específicas definidas pelo organizador.

---
## **Sprint 22 – Relatórios e Exportação de Dados** ♾️  
**Data inicial e final:** 22/03/2026 – 01/04/2026  

---

### 🎯 Objetivo da Sprint:  
Implementar geração de relatórios detalhados sobre os eventos, com opção de exportar dados em formatos como PDF ou Excel para fins de análise ou registro.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação dos relatórios e lógica de exportação                             |
| Testes             | 1 dia   | Validação de conteúdo, formato e compatibilidade                          |
| Revisão            | 2 dias  | Ajustes visuais, revisão de dados e testes de usabilidade                 |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Relatórios incluem métricas de presença, avaliações, contribuições e interações.  
- Sistema permite agendamento de envio automático de relatórios periódicos.

---
## **Sprint 23 – Acessibilidade e Inclusão Digital** ♾️  
**Data inicial e final:** 02/04/2026 – 12/04/2026  

---

### 🎯 Objetivo da Sprint:  
Garantir que o BoraJoin seja acessível para todos os usuários, incluindo pessoas com deficiência visual, auditiva ou motora, seguindo boas práticas de inclusão digital.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Implementação de recursos de acessibilidade e ajustes visuais             |
| Testes             | 1 dia   | Validação com ferramentas assistivas e simulações de uso real             |
| Revisão            | 2 dias  | Ajustes de acessibilidade, revisão de UX e testes de inclusão             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Projeto passou por auditoria interna de acessibilidade com checklist completo.  
- Inclusão digital é parte do compromisso do BoraJoin com experiências memoráveis para todos.

---
## **Sprint 24 – Modo Offline e Sincronização de Dados** ♾️  
**Data inicial e final:** 13/04/2026 – 23/04/2026  

---

### 🎯 Objetivo da Sprint:  
Permitir que os usuários acessem informações dos eventos mesmo sem conexão à internet, com sincronização automática assim que a conexão for restabelecida.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Criação do modo offline e lógica de sincronização                         |
| Testes             | 1 dia   | Validação de cache, reconexão e integridade dos dados                     |
| Revisão            | 2 dias  | Ajustes visuais, revisão de lógica e testes de confiabilidade             |
| Deploy             | 1 dia   | Publicação da funcionalidade em ambiente de homologação                   |

---

### 📝 Observações:  
- Sistema prioriza dados críticos como programação, localização e RSVP para acesso offline.  
- Sincronização inclui verificação de conflitos e resolução automática.

---
## **Sprint 25 – Finalização, Otimização e Lançamento Oficial** ♾️  
**Data inicial e final:** 24/04/2026 – 04/05/2026  

---

### 🎯 Objetivo da Sprint:  
Realizar os ajustes finais, otimizar performance, revisar toda a aplicação e preparar o BoraJoin para seu lançamento oficial.

---

### 👨‍💻 O que cada desenvolvedor fez:

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

---

### 📅 Cronograma da Sprint:

| Fase               | Duração | Descrição                                                                 |
|--------------------|---------|---------------------------------------------------------------------------|
| Desenvolvimento    | 5 dias  | Revisão geral, otimizações e preparação para publicação                   |
| Testes             | 1 dia   | Testes finais de regressão, performance e segurança                       |
| Revisão            | 2 dias  | Validação visual, ajustes finais e checklist de lançamento                |
| Deploy             | 1 dia   | Publicação oficial nas lojas e servidores                                 |

---

### 📝 Observações:  
- BoraJoin foi lançado oficialmente com versão estável, documentação completa e suporte integrado.  
- Equipe celebrou com um evento interno usando o próprio sistema — testado e aprovado! 🎉

---

## Quantidade total de Sprints:  
**25 Sprints** – distribuídas entre planejamento, desenvolvimento de funcionalidades, testes, ajustes e deploy final.

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

Apesar dos desafios, a Metodologia Ágil foi essencial para o sucesso do BoraJoin. A equipe acredita que o modelo incremental e colaborativo trouxe mais maturidade ao processo de desenvolvimento, permitindo que o produto evoluísse com qualidade, propósito e visão de longo prazo.



