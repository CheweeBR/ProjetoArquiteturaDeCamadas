# 📊 Projeto de Estudo: Análise e Recomendações para o App Coronavirus-SUS

## 👨‍🎓 Equipe
**Alunos:**  
### :mortar_board: Alunos
- [Tiago Eloy Possidonio Pereira - 2417677](https://github.com/CheweeBR/)
- [Italo Pereira Ventura - 2457259](https://github.com/ItaloVenturaa)
- [Igor Batista Lima - 2475855](https://github.com/IgorBatistaLima)


## 📂 Repositório Analisado
**Aplicativo:** [Coronavirus-SUS](https://github.com/spbgovbr/aplicativo-coronavirus-sus)

## 🛠️ Visão Geral
Este projeto faz parte da disciplina de Arquitetura de Software, ministrada pelo professor Diego Addan Gonçalves. Nosso objetivo é explorar, documentar e mapear os processos de um sistema existente. Escolhemos o **Aplicativo Coronavirus-SUS** devido à sua relevância durante a pandemia, sua base tecnológica moderna e os desafios enfrentados em termos de escalabilidade e usabilidade.

## ⚙️ Estrutura do Sistema

### 💻 Ferramentas e Tecnologias Utilizadas
- **Linguagem de Programação:**
  - **TypeScript:** Linguagem principal para o desenvolvimento do app, oferecendo tipagem estática e suporte a POO.

- **Frameworks e Bibliotecas:**
  - **Ionic:** Framework utilizado para o desenvolvimento de interfaces móveis.
  - **Angular:** Usado na construção do frontend, proporcionando uma arquitetura modular e escalável.
  - **Cordova:** Plataforma que empacota o app em containers nativos para Android e iOS.

- **Serviços Backend:**
  - **APIs RESTful:** Utilizadas para comunicação com o backend, fornecendo dados como informações sobre sintomas e locais de atendimento.

### 🧩 Componentes Principais
- **Interface do Usuário (UI):**
  - Desenvolvida com **Ionic** e **Angular**, proporcionando uma experiência responsiva tanto em dispositivos Android quanto iOS.

- **Módulo Informativo sobre a Covid-19:**
  - Apresenta dados atualizados sobre sintomas, prevenção e procedimentos em caso de suspeita, utilizando APIs externas.

- **Mapa de Unidades de Saúde:**
  - Utiliza APIs de geolocalização para mostrar unidades de saúde próximas, integrando dados de localização do usuário.

### 🏛️ Padrões Arquiteturais
- **MVC (Model-View-Controller):**
  - O aplicativo adota o padrão MVC, com o Angular facilitando a separação entre a lógica de apresentação (View) e a lógica de negócios (Controller), enquanto os serviços RESTful funcionam como Model.

## 📈 Escalabilidade e Desempenho

### 🔧 Estratégias de Otimização
- **Otimização do Frontend:**
  - Implementação de técnicas de carregamento progressivo para melhorar a experiência do usuário, especialmente em ambientes com baixa conectividade.

- **Suporte a Alta Demanda:**
  - Escalabilidade do backend utilizando serviços em nuvem para gerenciar picos de acesso, como durante novas ondas de infecção ou campanhas de vacinação.

## 🚀 Recomendações de Melhoria

### 🎨 Atualização da Interface
- **Proposta:** Modernizar a UI utilizando os componentes mais recentes do Ionic e Angular, além de aplicar práticas de design responsivo para melhorar a usabilidade em diversos dispositivos.

### 📚 Aperfeiçoamento da Documentação Técnica
- **Proposta:** Ampliar a documentação existente, incluindo guias de configuração, exemplos de uso e casos de teste automatizados, facilitando a contribuição de novos desenvolvedores.

### 🛠️ Implementação de Microsserviços
- **Proposta:** Refatorar partes do backend para uma arquitetura baseada em microsserviços, permitindo uma melhor escalabilidade e manutenção dos diferentes módulos do aplicativo.

## 🖼️ Diagramas

### 🗺️ Diagrama de Arquitetura
- **Descrição:** Ilustra a interação entre os componentes do sistema, incluindo UI, APIs RESTful e serviços backend.
