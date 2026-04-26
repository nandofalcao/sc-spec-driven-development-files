# Todos os Prompts — Desenvolvimento Orientado a Especificações com Agentes de Código

> Consolidado de todas as lições do repositório do curso.

---

## Lição 04 — Criando a Constituição

### Prompt 1

Estamos desenvolvendo o AgentClinic, um lugar para agentes de IA se recuperarem de seus humanos. Consulte o README.md para obter informações dos stakeholders.

### Prompt 2

Vamos criar uma "constituição" em um diretório specs:
- `mission.md`
- `tech-stack.md`
- `roadmap.md` para a ordem de implementação de alto nível, em fases de trabalho muito pequenas.

Importante: Você *deve* usar sua ferramenta AskUserQuestion, agrupada nesses 3 arquivos, antes de escrever no disco.

### Prompt 3

Use TypeScript no lado do servidor e recomende um framework.

### Prompt 4

Adicione um público-alvo à missão:
- Estudantes do curso aprendendo desenvolvimento orientado a especificações com agentes de código de IA
- Desenvolvedores fazendo demos de IA em estandes de conferências

### Prompt 5

Na stack de tecnologia, adicione que usamos SQLite.

---

## Lição 05 — Especificação de Funcionalidade

### Prompt 1

Encontre a próxima fase em specs/roadmap.md, crie uma branch e me pergunte sobre a especificação da funcionalidade.
Crie:
 - Um novo diretório AAAA-MM-DD-nome-da-funcionalidade em specs para este trabalho
 - Dentro dele:
  - `plan.md` como uma série de grupos de tarefas numerados.
  - `requirements.md` para escopo, decisões e contexto
  - `validation.md` para saber como verificar se a implementação foi bem-sucedida e pode ser integrada

Consulte specs/mission.md e specs/tech-stack.md como orientação.

Importante: Você *deve* usar sua ferramenta AskUserQuestion, agrupada nesses 3 arquivos, antes de escrever no disco.

### Prompt 2

Adicione um grupo de tarefas ao plano para ter uma página inicial mínima do AgentClinic e atualize o restante da especificação para estar em sincronia.

---

## Lição 06 — Implementação de Funcionalidade

### Prompt 1

Implemente os grupos de tarefas restantes.

---

## Lição 07 — Validação de Funcionalidade

### Prompt 1

Atualize specs/2026-03-30-hello-hono/plan.md e a implementação de um componente de layout principal com header/main/footer como três subcomponentes. Crie um arquivo CSS, importe-o e vincule-o.

### Prompt 2

Atualize a especificação para registrar que os componentes de header, footer e main devem estar em seus próprios arquivos.

### Prompt 3

Marque esta fase do specs/roadmap.md como concluída, faça o commit deste trabalho, mude para a branch main e faça o merge desta branch e depois a exclua.

---

## Lição 08 — Replanejamento do Projeto

### Prompt 1

Atualize este tech-stack.md para registrar que queremos usar testes Vitest para validação e escreva um script no package.json.

### Prompt 2

Atualize as especificações e o código existentes para refletir essas mudanças de testes.

### Prompt 3

Escreva uma nova suíte de testes usando o framework de testes especificado.

### Prompt 4

A interface web do produto deve seguir design responsivo. Atualize as especificações do produto e todas as especificações de funcionalidades para refletir isso, bem como qualquer código relacionado.

### Prompt 5

Quero manter um CHANGELOG.md na raiz do projeto, com cabeçalhos por data. Se não houver changelog, examine os commits do git e adicione marcadores para cada data. Então, conforme trabalhamos, invocaremos essa habilidade manualmente[...]  

### Prompt 6

Use sua habilidade de changelog para atualizar o changelog.

### Prompt 7

Faça o commit disso, mude para a main, faça o merge desta branch e depois a exclua.

### Prompt 8

Vá ao roadmap.md e combine as fases 2-3-4-5 em uma nova fase 2.

---

## Lição 09 — A Segunda Fase de Funcionalidades

### Prompt 1

Nossas cores de marca são laranja e preto.

### Prompt 2

Use definições de props extraídas com um tipo TypeScript em vez de inline e execute os testes novamente.

### Prompt 3

Faça uma revisão profunda: Crie múltiplos subagentes para analisar todas as mudanças nesta branch sob três perspectivas diferentes e veja se algo não faz sentido ou pode ser melhorado, etc.

### Prompt 4

Use sua habilidade de changelog para atualizar o changelog com o trabalho feito nesta branch.

---

## Lição 10 — O MVP

### Prompt 1

Percorra todas as funcionalidades em specs/roadmap.md, crie uma branch mvp e me pergunte sobre as especificações de funcionalidades necessárias para completar um MVP.
Crie:
 - Um novo diretório em specs para este trabalho de funcionalidade
 - Dentro dele:
  - `plan.md` para a lista de tarefas
  - `requirements.md` para escopo, decisões e contexto
  - `validation.md` para saber como verificar se a implementação foi bem-sucedida e pode ser integrada

Consulte specs/mission.md e specs/tech-stack.md além das especificações de funcionalidades existentes como orientação.

Importante: Você *deve* usar sua ferramenta AskUserQuestion, agrupada nesses 3 arquivos, antes de escrever no disco.

### Prompt 2

Implemente este plano.

### Prompt 3

Com base no MVP, você encontrou algo que precisa de esclarecimento nas especificações?

---

## Lição 11 — Suporte a Legado

### Prompt 1

Temos um projeto AgentClinic, um lugar para agentes de IA se recuperarem de seus humanos.

Consulte o README.md para obter informações dos stakeholders. Crie uma constituição em um diretório specs:
- `mission.md`
- `tech-stack.md`
- `roadmap.md` deve ser baseado no TODO.md para a ordem de implementação de alto nível, em fases de trabalho muito pequenas.

Me entreviste sobre missão, público-alvo e lacunas na stack de tecnologia.

Importante: Você *deve* usar sua ferramenta AskUserQuestion, agrupada nesses 3 arquivos, antes de escrever no disco.

### Prompt 2

Implemente o plano.

---

## Lição 12 — Construa Seu Próprio Fluxo de Trabalho

### Prompt 1

Quero parar de repetir o prompt de especificação de funcionalidade. Use seu criador de habilidades para me ajudar a escrever uma habilidade local de "feature spec". Aqui está o prompt anterior:

Encontre a próxima fase em specs/roadmap.md, crie uma branch e me pergunte sobre a especificação da funcionalidade.
Crie:
 - Um novo diretório AAAA-MM-DD-nome-da-funcionalidade em specs para este trabalho
 - Dentro dele:
  - `plan.md` como uma série de grupos de tarefas numerados.
  - `requirements.md` para escopo, decisões e contexto
  - `validation.md` para saber como verificar se a implementação foi bem-sucedida e pode ser integrada

Consulte specs/mission.md e specs/tech-stack.md como orientação.

Importante: Você *deve* usar sua ferramenta AskUserQuestion, agrupada nesses 3 arquivos, antes de escrever no disco.

### Prompt 2

Use sua habilidade feature-spec para trabalhar na próxima funcionalidade do roadmap.

---

## Lição 13 — Intercambiabilidade de Agentes

### Prompt 1

Quais partes do nosso código precisam de mais testes?