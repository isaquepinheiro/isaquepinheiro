![image](https://github.com/user-attachments/assets/25ed810f-77aa-42ca-85f5-8d8aef707ff9)
<!-- Título -->
# Meus Projetos Open Source

<!-- Descrição -->
Esta é uma lista dos meus projetos open source, hoje mantidos na organização [**ModernDelphiWorks**](https://github.com/ModernDelphiWorks). Aqui você encontrará informações sobre cada projeto e como contribuir com eles.

> ℹ️ **Importante:** os projetos antigos publicados na organização **HashLoad** (DMFBr, ECLBr, ORMBr, DBEBr, DBCBr, CQLBr, JSONBr, InjectorBr, ResultPairBr) foram **descontinuados**. Eles foram reescritos, modernizados e renomeados, e seguem sendo mantidos sob a organização [**ModernDelphiWorks**](https://github.com/ModernDelphiWorks). Veja a tabela de equivalência abaixo.

## Sumário

- [Lista de Projetos](#lista-de-projetos)
- [Projetos antigos → atuais](#-projetos-antigos--atuais)
- [Contribuição](#%EF%B8%8F-contribui%C3%A7%C3%A3o)
- [Licença](#%EF%B8%8F-licen%C3%A7a)
- [Contato](#-contato)

<!-- Lista de Projetos -->
## Lista de Projetos

A seguir, uma lista dos meus projetos open source atuais:

### ⚙️ [Nidus for Delphi](https://github.com/ModernDelphiWorks/Nidus)

**Nidus** é um framework modular e altamente escalável para aplicações e microsserviços em Delphi, profundamente inspirado nos padrões arquiteturais modernos do **NestJS**. Oferece uma arquitetura pronta para uso corporativo com Injeção de Dependência (DI) avançada, organização modular, *validation pipes* via atributos RTTI (`[IsEmail]`, `[IsUUID]`, `[IsStrongPassword]`...), *security guards*, *object pooling* de alta concorrência, adaptadores de cache e microsserviços RPC nativos sobre socket. É o sucessor do antigo **DMFBr**.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/Nidus/)

### ⚙️ [ModernSyntax for Delphi](https://github.com/ModernDelphiWorks/ModernSyntax)

**ModernSyntax** é um toolkit leve e de alto desempenho de programação funcional e sintaxe moderna para Delphi, trazendo recursos encontrados em linguagens contemporâneas como **Rust**, **Kotlin**, **C#** e **Haskell**. Inclui tipos opcionais seguros (`TOption<T>`) contra *null-reference*, fluxo funcional de erros (`TResultPair<S,F>`), *pattern matching* (`TMatch<T>`), agendamento assíncrono no estilo *async/await*, *tuples* e *currying*. É o sucessor dos antigos **ECLBr** e **ResultPairBr**.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/ModernSyntax/)

### ⚙️ [Janus for Delphi](https://github.com/ModernDelphiWorks/Janus)

**Janus** é um framework ORM (Object-Relational Mapping) de alto desempenho para Delphi — a evolução e o **sucessor do framework ORMBr**. Ele faz a ponte entre modelos de domínio orientados a objetos e estruturas de banco de dados relacional, tratando mapeamentos de metadados via atributos RTTI, eliminando o *boilerplate* de SQL/conexão e oferecendo containers DataSet/ObjectSet, hierarquias master-detail (`TManagerDataSet`), *lazy loading* transparente via *proxies* RTTI e um *wizard* de geração de código integrado à IDE do Delphi.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/Janus/)

### ⚙️ [DataEngine for Delphi/Lazarus](https://github.com/ModernDelphiWorks/DataEngine)

**DataEngine** é um framework modular e extensível de abstração de *engine* de banco de dados para Delphi e Lazarus. Fornece uma camada de interface uniforme que desacopla a aplicação dos *drivers* específicos do banco, permitindo escrever código agnóstico (FireDAC, dbExpress, UniDAC, Zeos...). Conta com *connection pooling* multi-tenant, monitoramento inteligente de *queries* e cache avançado do lado cliente. É o sucessor do antigo **DBEBr**.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/DataEngine/)

### ⚙️ [MetaDbDiff for Delphi/Lazarus](https://github.com/ModernDelphiWorks/MetaDbDiff)

**MetaDbDiff** é uma *engine* de comparação de metadados de banco de dados e geração de *scripts* DDL de migração para Delphi e Lazarus. Permite comparar dois *schemas* físicos, ou comparar diretamente um modelo de entidades Pascal (classes ORM) com um banco ativo, gerando *scripts* de sincronização precisos (tabelas, colunas, tipos, *primary/foreign keys* e índices). É o sucessor do antigo **DBCBr**.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/MetaDbDiff/)

### ⚙️ [FluentSQL for Delphi/Lazarus](https://github.com/ModernDelphiWorks/FluentSQL)

**FluentSQL** é uma biblioteca moderna e agnóstica de geração de *scripts* SQL/MQL para Delphi e Lazarus. Seu contrato é simples: **apenas emite `string`** — *scripts* SQL padrão (ou equivalentes específicos do *driver*, como MQL/JSON para MongoDB) através de uma API fluente e orientada a objetos com encadeamento de métodos. Sem conexão ativa, sem execução no servidor e sem validação interna — totalmente desacoplado, ideal como dependência de ORMs como o **Janus**. É o sucessor do antigo **CQLBr**.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/FluentSQL/)

### ⚙️ [FluentQuery for Delphi/Lazarus](https://github.com/ModernDelphiWorks/FluentQuery)

**FluentQuery** é uma biblioteca de programação funcional e manipulação de coleções para Delphi e Lazarus, fortemente inspirada no **LINQ do C#** e nas APIs de *stream* de Java, Kotlin e Rust. Introduz estruturas baseadas em *records* (`IFluentEnumerable<T>` e `IFluentQueryable<T>`) para consultar, filtrar, mapear, ordenar e agregar coleções e *datasets* em memória. Utiliza *Lazy Evaluation* (execução adiada) para evitar alocações intermediárias, garantindo desempenho excepcional e baixo consumo de memória.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/FluentQuery/)

### ⚙️ [JsonFlow for Delphi/Lazarus](https://github.com/ModernDelphiWorks/JsonFlow)

**JsonFlow** é um framework de alto desempenho de serialização, manipulação dinâmica e validação de JSON (JSON Schema Draft 7) para Delphi e Lazarus. Reúne serialização rápida de objetos, edição dinâmica de JSON *in-place* (via *path strings* como `user.address[0].zip`) e validação robusta de *schema* sob uma API fluente e elegante, com *navigation cache*, modo *batch* e *object pooling* multi-thread. É o sucessor do antigo **JSONBr**.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/JsonFlow/)

### ⚙️ [InjectContainer for Delphi](https://github.com/ModernDelphiWorks/InjectContainer)

**InjectContainer** é um *container* de Injeção de Dependência (DI) *thread-safe* e de alto desempenho para Delphi. Desacopla classes e interfaces dinamicamente com baixíssimo *overhead*, usando um cache RTTI otimizado, *pooling* de instâncias e detecção automática de dependências circulares. Suporta *Singletons*, *Factories*, *LazyLoads* e classes baseadas em interface, com *logging* completo do ciclo de vida dos objetos. É o sucessor do antigo **InjectorBr**.

📖 [Clique aqui para acessar a documentação do projeto](https://moderndelphiworks.github.io/InjectContainer/)

### 🤖 [Aefos — AI for Delphi](https://github.com/ModernDelphiWorks/Aefos)

**Aefos** (Agent Execution Flow Orchestration System) traz a sua CLI de IA favorita — Claude Code, Codex, GitHub Copilot CLI, Gemini — para **dentro** do RAD Studio (Delphi 13), com plugins de **Chat** e **Terminal** de IA integrados à IDE. Este repositório é a casa pública do produto: downloads, manual do usuário e abertura de *issues*.

📖 [Manual do Usuário](https://moderndelphiworks.github.io/Aefos/)

> 📄 Licença proprietária (EULA) — edição Community gratuita. Não é open source / MIT.

### 🧩 [ProjectsManagerPlus for Delphi](https://github.com/ModernDelphiWorks/ProjectsManagerPlus)

**ProjectsManagerPlus** é um conjunto de extensões para o *Project Manager* da IDE do Delphi, ampliando a produtividade no gerenciamento de projetos e *project groups*.

<!-- Projetos antigos → atuais -->
## 🔄 Projetos antigos → atuais

Os projetos abaixo, antes publicados na organização **HashLoad**, foram descontinuados e substituídos pelas versões modernizadas na organização **ModernDelphiWorks**:

| Projeto antigo (HashLoad) | Projeto atual (ModernDelphiWorks) | Categoria |
| --- | --- | --- |
| DMFBr | [Nidus](https://github.com/ModernDelphiWorks/Nidus) | Framework modular / microsserviços |
| ECLBr · ResultPairBr | [ModernSyntax](https://github.com/ModernDelphiWorks/ModernSyntax) | Programação funcional / sintaxe moderna |
| ORMBr | [Janus](https://github.com/ModernDelphiWorks/Janus) | ORM |
| DBEBr | [DataEngine](https://github.com/ModernDelphiWorks/DataEngine) | Abstração de engine de banco |
| DBCBr | [MetaDbDiff](https://github.com/ModernDelphiWorks/MetaDbDiff) | Comparação de metadados / DDL |
| CQLBr | [FluentSQL](https://github.com/ModernDelphiWorks/FluentSQL) | Builder de SQL fluente |
| JSONBr | [JsonFlow](https://github.com/ModernDelphiWorks/JsonFlow) | JSON / serialização / schema |
| InjectorBr | [InjectContainer](https://github.com/ModernDelphiWorks/InjectContainer) | Injeção de dependência |

<!-- Contribuição -->
## ⛏️ Contribuição

Eu adoraria receber contribuições para os meus projetos open source. Se você tiver alguma ideia ou correção de bug, sinta-se à vontade para abrir uma issue ou enviar uma pull request no projeto correspondente em [ModernDelphiWorks](https://github.com/ModernDelphiWorks).

Para enviar uma pull request, siga estas etapas:

1. Faça um fork do projeto
2. Crie uma nova branch (`git checkout -b minha-nova-funcionalidade`)
3. Faça suas alterações e commit (`git commit -am 'Adicionando nova funcionalidade'`)
4. Faça push da branch (`git push origin minha-nova-funcionalidade`)
5. Abra uma pull request

<!-- Licença -->
## ✍️ Licença

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A maior parte dos projetos é licenciada sob **MIT**. Exceções:

- **Aefos** — licença proprietária (EULA), com edição Community gratuita.
- **ProjectsManagerPlus** — licença **Apache-2.0**.

Consulte sempre o arquivo `LICENSE` no repositório de cada projeto.

<!-- Contato -->
## 💬 Contato

- [Telegram](https://t.me/ormbr)
- [Website](https://www.isaquepinheiro.com.br)
- [Youtube Channel](https://www.youtube.com.br/isaquepinheirooficialbr)
- [FaceBook](https://www.facebook.com/isaquepinheirooficialbr)
- [Instagram](https://www.instagram.com/isaquepinheirooficialbr)
- [Linkedin](https://www.linkedin.com/in/isaquepinheirooficialbr)
