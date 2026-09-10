#  Lutas Casadas

Plataforma SaaS em desenvolvimento para **gestão, organização e matchmaking de lutas e eventos de Jiu-Jitsu**.

O projeto busca simplificar o processo de cadastro de atletas, criação de confrontos e gerenciamento de eventos, utilizando critérios esportivos para auxiliar na formação de lutas mais equilibradas.

>  Projeto em desenvolvimento — versão atual focada em Jiu-Jitsu.



##  Objetivo

Organizar lutas casadas manualmente pode exigir a comparação de diversos fatores entre atletas, como idade, peso, faixa, categoria e modalidade.

O Lutas Casadas busca centralizar esse processo em uma única plataforma, permitindo cadastrar atletas, organizar eventos e utilizar regras de compatibilidade para auxiliar na escolha de adversários.

A visão de longo prazo é transformar o projeto em um **SaaS para gestão de eventos e matchmaking em esportes de combate**, começando pelo Jiu-Jitsu e posteriormente permitindo suporte a outras modalidades.



##  Matchmaking

O sistema utiliza informações dos atletas para auxiliar na sugestão de possíveis confrontos.

Entre os critérios considerados estão:

- Idade
- Peso
- Faixa
- Categoria
- Modalidade
- Disponibilidade para luta

O objetivo não é substituir a decisão do organizador, mas fornecer informações que tornem o processo de matchmaking mais rápido, organizado e consistente.



##  Modalidades

Inicialmente, o sistema é direcionado ao Jiu-Jitsu:

- Gi — com kimono
- No-Gi — sem kimono

A arquitetura do produto deverá evoluir para permitir novas regras e modalidades de esportes de combate.



## ✨ Funcionalidades

### Gestão de atletas

- Cadastro de atletas
- Edição de informações
- Exclusão de atletas
- Controle de idade
- Controle de peso
- Faixa e categoria
- Modalidade
- Identificação de atletas disponíveis para luta

### Gestão de lutas

- Criação de confrontos
- Associação entre atletas
- Visualização das lutas casadas
- Alteração de confrontos
- Exclusão e cancelamento de lutas
- Registro do vencedor

### Matchmaking

- Sugestão de adversários
- Comparação por idade
- Comparação por peso
- Compatibilidade por faixa
- Compatibilidade por categoria
- Filtro por Gi e No-Gi

### Dashboard

Visão geral da operação, incluindo informações como:

- Atletas cadastrados
- Atletas sem luta
- Lutas casadas
- Lutas realizadas
- Situação dos confrontos



##  Gestão de eventos

A evolução do projeto prevê que atletas e confrontos possam ser organizados dentro de eventos.

Cada evento poderá concentrar seus próprios:

- Atletas
- Confrontos
- Categorias
- Modalidades
- Resultados

Isso permitirá utilizar a plataforma em diferentes competições e organizações.



##  Visão SaaS

O projeto está sendo estruturado para evoluir de uma aplicação de gerenciamento para uma plataforma SaaS.

A evolução prevista inclui:

- Autenticação de usuários
- Organizações independentes
- Gestão de diferentes eventos
- Isolamento de dados entre clientes
- Perfis e permissões
- Configuração de regras por modalidade
- Histórico de eventos e confrontos
- Expansão para outros esportes de combate



##  Tecnologias

A aplicação utiliza atualmente:

- React
- JavaScript
- Vite
- Supabase
- Git
- GitHub
- Vercel

O Supabase é utilizado como parte da infraestrutura de dados da aplicação.

---

##  Roadmap

### MVP — Jiu-Jitsu

- [x] Estrutura inicial da aplicação
- [x] Integração inicial com banco de dados
- [ ] Consolidar gestão de atletas
- [ ] Consolidar gestão de lutas
- [ ] Aprimorar mecanismo de matchmaking
- [ ] Implementar gestão de eventos
- [ ] Melhorar dashboard operacional
- [ ] Implementar histórico de confrontos

### SaaS

- [ ] Implementar autenticação
- [ ] Criar estrutura de organizações
- [ ] Isolar dados por organização
- [ ] Implementar usuários e permissões
- [ ] Preparar onboarding de novos clientes
- [ ] Estruturar planos e recursos do produto

### Expansão

- [ ] Tornar regras de matchmaking configuráveis
- [ ] Adicionar novas modalidades de combate
- [ ] Criar regras específicas por modalidade
- [ ] Evoluir relatórios e indicadores



## 🔐 Segurança e dados

Por se tratar de uma aplicação que poderá armazenar informações de atletas e organizações, segurança e isolamento dos dados fazem parte da evolução planejada do produto.

Credenciais e informações sensíveis não devem ser armazenadas diretamente no repositório.

O modelo de autorização e isolamento de dados será evoluído juntamente com a arquitetura SaaS.

---

##  Status

**Em desenvolvimento ativo.**

A versão atual é focada na validação das funcionalidades essenciais para organização de atletas e lutas de Jiu-Jitsu.

O produto continuará evoluindo até a consolidação do MVP e posteriormente da arquitetura SaaS.



## 👨‍💻 Desenvolvedor

**Nelson Souza**  
Desenvolvedor de Software

GitHub: [@nelsonlsouza](https://github.com/nelsonlsouza)
