# SistemaCadastro

Sistema Java simples desenvolvido para atividade prática de controle de versão e gerenciamento de mudanças com Git e GitHub.

## Análise rápida

### 1. Qual a finalidade de uma branch?

Uma branch permite desenvolver alterações ou novas funcionalidades de forma separada da versão principal do projeto, evitando que mudanças em desenvolvimento afetem diretamente a main.

### 2. Qual a diferença entre commit e merge?

Commit é o registro de uma alteração realizada no projeto. Merge é a integração das alterações de uma branch em outra.

### 3. Por que é importante utilizar mensagens claras nos commits?

Mensagens claras facilitam a compreensão do histórico do projeto, permitindo identificar rapidamente quais alterações foram realizadas em cada commit.

### 4. Por que o controle de versão é importante em equipes de desenvolvimento?

O controle de versão permite acompanhar as alterações realizadas no projeto, trabalhar de forma organizada entre diferentes desenvolvedores, recuperar versões anteriores e evitar conflitos durante o desenvolvimento.

### 5. O que representa a versão 1.1.0 no contexto desta atividade?

A versão 1.1.0 representa a versão do SistemaCadastro após a inclusão da nova opção de exclusão de usuário.

### 6. A tag foi criada direto na interface do GitHub, essa tag também pode ser realizada pela interface CLI, escreva abaixo os comandos git para criação desta tag.

Sim. A tag pode ser criada pela interface CLI utilizando:

```bash
git tag v1.1.0
git push origin v1.1.0