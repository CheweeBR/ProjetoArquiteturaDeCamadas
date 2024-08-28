# :clipboard: Projeto de Estudo: Análise e Sugestões para o App Coronavirus-SUS

### :mortar_board: Alunos:  Tiago Eloy Possidonio Pereira - 2417677 / Italo Pereira Ventura - 2457259 / Igor Batista Lima - 2475855

### :open_file_folder: Repositório analisado: [Aplicativo Coronavirus-SUS](https://github.com/spbgovbr/aplicativo-coronavirus-sus)

## 🛠️ Visão Geral
Este trabalho é parte da disciplina de Arquitetura de Software ministrada pelo professor Diego Addan Gonçalves. O objetivo é explorar, documentar e mapear os processos de um sistema existente. Optamos por analisar o **Aplicativo Coronavirus-SUS** devido à sua relevância durante a pandemia, sua base tecnológica atualizada e os desafios enfrentados em termos de escalabilidade e usabilidade.

## ⚙️ Estrutura do Sistema
### 🖥️ Ferramentas e Linguagens Utilizadas
- **Linguagem de Programação:**
  - **TypeScript:** Usada para desenvolver a maior parte do app, com suporte para tipagem estática e OOP.

- **Frameworks e Bibliotecas:**
  - **Ionic:** Framework para desenvolvimento de interfaces móveis.
  - **Angular:** Utilizado na construção do frontend, proporcionando uma arquitetura modular.
  - **Cordova:** Plataforma que empacota o app em containers nativos para Android e iOS.

- **Serviços Backend:**
  - **APIs RESTful:** Utilizadas para comunicação com serviços backend, fornecendo dados como informações sobre sintomas e locais de atendimento.
  
 ### 🧩 Componentes Principais
- **Interface do Usuário (UI):**
  - Desenvolvida utilizando **Ionic** e **Angular**, proporcionando uma experiência responsiva em dispositivos Android e iOS.

- **Módulo Informativo sobre a Covid-19:**
  - Fornece dados sobre sintomas, prevenção e procedimentos em caso de suspeita, atualizados via API externa.

- **Mapa de Unidades de Saúde:**
  - Utiliza APIs de geolocalização para mostrar unidades de saúde próximas, integrando dados de localização do usuário.

