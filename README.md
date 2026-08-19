# IFood - Sistema de divulgação do cardápio do restaurante universitário

O IFood é um sistema web desenvolvido para promover a divulgação clara, acessível e atualizada do cardápio do restaurante universitário do Instituto Federal de Educação, Ciência e Tecnologia de São Paulo (IFSP) - Campus Birigui. O objetivo do projeto é permitir que discentes, docentes e funcionários consultem previamente as refeições oferecidas, evitando deslocamentos desnecessários até o refeitório e otimizando o fluxo de pessoas no local. O sistema conta ainda com um painel administrativo para cadastro e autenticação dos funcionários responsáveis pela gestão das informações.

---

## Sumário

- Visão Geral
- Funcionalidades
- Tecnologias Utilizadas
- Estrutura do Projeto

---

## Visão geral

Atualmente, o cardápio do restaurante universitário não é divulgado com antecedência, fazendo com que a comunidade acadêmica precise ir até o refeitório (localizado em uma área afastada do campus) para consultar as refeições. 

O IFood resolve esse problema ao disponibilizar:
- Interface pública para consulta do cardápio semanal por qualquer usuário, sem necessidade de autenticação.
- Painel restrito para que funcionários do restaurante e administradores possam cadastrar, editar e excluir as informações das refeições.

---

## Funcionalidades

- Visualização do cardápio semanal: Consulta das refeições organizadas por dias da semana (segunda a sexta-feira).
- Informativo de horários e observações: Exibição detalhada dos horários do café da manhã, almoço e café da tarde.
- Cadastro e login de funcionários: Autenticação de usuários administrativos com armazenamento seguro e criptografado de senhas.
- Gestão do cardápio (CRUD): Permissão para que funcionários autenticados insiram, editem ou excluam itens do cardápio.
- Design responsivo: Interface otimizada para se adaptar às telas de diferentes dispositivos (desktops, tablets e smartphones).

---

## Tecnologias utilizadas

- HTML5: Estruturação semântica das telas.
- CSS3: Estilização responsiva com Flexbox e gradientes, utilizando as fontes Inter e Raleway.
- PHP: Linguagem backend para autenticação e manipulação dos dados no servidor.
- MySQL: Banco de dados relacional para armazenamento das tabelas `Funcionario` e `Cardapio`.
- SVG: Gráficos vetoriais para logos e ícones.

---

## Estrutura do projeto

```text
├── cadastro/
│   ├── index.html       # Formulário de cadastro de funcionários
│   └── styles.css       # Estilos da tela de cadastro
├── imagens/
│   └── logo-favicon.svg # Ícone e logo da aplicação
├── login/
│   ├── index.html       # Formulário de autenticação
│   └── styles.css       # Estilos da tela de login
└── pagina-inicial/
    ├── index.html       # Interface pública do cardápio semanal
    └── styles.css       # Estilos da página principal
