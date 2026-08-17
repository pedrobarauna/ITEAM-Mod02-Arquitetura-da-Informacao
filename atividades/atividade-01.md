
# Atividade 01 — Auditoria Rápida do Site do ITEAM

## 1. Identificação

**Site analisado:** ITEAM — Instituto Tecnológico Educacional da Amazônia  
**URL:** https://www.iteam.org.br/  
**Tipo de site:** Institucional

### Objetivo da análise

Realizar uma auditoria rápida da Arquitetura da Informação do site, observando:

- Organização das informações;
- Rotulagem;
- Navegação;
- Encontrabilidade;
- Clareza das informações;
- Facilidade para encontrar cursos;
- Facilidade para encontrar editais e processos seletivos;
- Facilidade para encontrar informações institucionais importantes.

A análise considera principalmente a perspectiva de um usuário que acessa o site para realizar uma tarefa.

---

## 2. Organização das informações

O site apresenta uma estrutura organizada principalmente por **tópicos**, com categorias como:

- Educação;
- Inovação e Tecnologia;
- Consultoria;
- Sobre Nós;
- Periódicos;
- Novidades;
- Contato.

Essa organização permite compreender as principais áreas de atuação da instituição.

### Evidência

![Página inicial do ITEAM](https://github.com/pedrobarauna/ITEAM-Mod02-Arquitetura-da-Informacao/blob/main/evidencias/atividde01/home.png)

### Análise

Apesar de a organização institucional ser compreensível, ela não está totalmente orientada às principais tarefas que o usuário deseja realizar.

Por exemplo, um usuário que acessa o site com o objetivo de **encontrar um curso** precisa interpretar que a categoria correta é **Educação**.

**Avaliação:** 🟡 Adequada, mas pode ser melhor orientada ao usuário.

---

## 3. Rotulagem

Os principais rótulos encontrados na navegação são:

- Educação;
- Inovação e Tecnologia;
- Consultoria;
- Sobre Nós;
- Periódicos;
- Novidades;
- Contato.

Os termos são, em sua maioria, claros e compreensíveis para o usuário.

### Evidência

![Menu principal do ITEAM](../imagens/atividade-01/menu-navegacao.png)

### Análise

Os rótulos utilizados possuem relação com os conteúdos apresentados.

Entretanto, alguns rótulos importantes para as tarefas do usuário não aparecem diretamente na navegação.

Por exemplo, **Cursos**, **Editais**, **Inscrições** e **Resultados** poderiam ser apresentados de forma mais direta.

O problema, portanto, não está apenas na clareza dos rótulos existentes, mas também na ausência de rótulos relacionados às principais tarefas do usuário.

**Avaliação:** 🟡 Razoável, com oportunidades de melhoria.

---

## 4. Navegação

O menu principal apresenta as principais áreas institucionais do ITEAM.

### Evidência

![Menu de navegação](../imagens/atividade-01/menu-navegacao.png)

### Pontos positivos

- Menu principal visível;
- Categorias relativamente compreensíveis;
- Acesso às principais áreas institucionais;
- Acesso à área de contato.

### Pontos de atenção

As categorias estão mais relacionadas à estrutura da instituição do que às tarefas que o usuário deseja realizar.

Um usuário pode acessar o site com objetivos como:

- Encontrar um curso;
- Verificar inscrições abertas;
- Encontrar um edital;
- Consultar um resultado;
- Conhecer os requisitos de um curso.

Essas tarefas não aparecem de maneira evidente na navegação principal.

**Avaliação:** 🟡 Funcional, porém pouco orientada às tarefas do usuário.

---

## 5. Tarefa: encontrar um curso

### Pergunta

**Se eu fosse um usuário interessado em estudar no ITEAM, conseguiria encontrar facilmente os cursos disponíveis?**

A página apresenta informações relacionadas à área de **Educação** e informa diferentes modalidades de ensino.

### Evidência

![Área de Educação](../imagens/atividade-01/educacao.png)

### Análise

A informação sobre os cursos existe, porém **Cursos** não aparece como uma opção principal do menu.

O usuário precisa primeiro identificar que deve acessar **Educação** para encontrar as informações relacionadas aos cursos.

Isso cria uma pequena barreira de encontrabilidade para usuários que acessam o site pela primeira vez.

**Avaliação:** 🟡 Encontrabilidade razoável.

### Sugestão

Disponibilizar uma estrutura mais direta:

```text
Educação
├── Cursos
├── Graduação
├── Pós-Graduação
├── Capacitação
└── Educação Empresarial
```

---

### 6. Tarefa: encontrar um edital

### Pergunta
Se eu quiser me inscrever em um curso, consigo encontrar rapidamente o edital correspondente?

### Análise
Na navegação principal não existe uma categoria claramente identificada como Editais ou Processos Seletivos.

Entretanto, o site possui publicações relacionadas a editais, resultados e processos seletivos.

### Evidência
(Adicionar evidência visual aqui, se houver)

### Análise Adicional
Esse é um dos principais pontos identificados na auditoria.

A informação pode existir no site, mas não está organizada de maneira suficientemente evidente de acordo com a tarefa do usuário.

Um usuário interessado em ingressar em um curso poderia procurar naturalmente por:

Educação → Editais

ou:

Educação → Processos Seletivos

Essa relação não está clara na estrutura principal.

Avaliação: 🔴 Encontrabilidade baixa.

### Sugestão
Criar uma área específica para processos seletivos:
```text
Processos Seletivos
├── Editais Abertos
├── Editais Encerrados
├── Inscrições
├── Resultados
└── Retificações
```

7. Tarefa: encontrar inscrições abertas
Pergunta
O usuário consegue descobrir rapidamente quais cursos estão com inscrições abertas?

Análise
Não existe um acesso claramente destacado para Inscrições Abertas na navegação principal.

Um usuário pode precisar explorar diferentes áreas do site para descobrir se existe algum processo seletivo em andamento.

Isso aumenta o esforço necessário para realizar uma tarefa importante.

Avaliação: 🔴 Encontrabilidade baixa.

Sugestão
Criar uma área de destaque na página inicial:
```text
Inscrições Abertas
Confira os cursos com processos seletivos abertos.
[Ver cursos disponíveis →]
````

8. Tarefa: encontrar resultados
Pergunta
Depois de realizar uma inscrição, o usuário consegue encontrar facilmente o resultado?

Análise
O site apresenta publicações relacionadas a resultados de processos seletivos.

Porém, editais, resultados, retificações e outros comunicados podem aparecer dentro do mesmo conjunto de publicações.

Isso exige que o usuário interprete os títulos para descobrir qual documento corresponde ao que procura.

Avaliação: 🔴 Pode gerar dificuldade de encontrabilidade.

Sugestão
Organizar os conteúdos por tipo:

```text
Processos Seletivos
├── Editais
├── Resultados
├── Retificações
└── Comunicados
````
9. Novidades
O site possui uma seção chamada Novidades do ITEAM.

Evidência
(Adicionar evidência visual aqui, se houver)

Análise
A existência de uma área destinada às novidades é positiva.

Porém, a seção não deixa claro para o usuário se deve procurar nela informações como:
```text

Editais;
Processos seletivos;
Resultados;
Inscrições;
Comunicados.
````
Além disso, uma área sem informações recentes pode transmitir a impressão de que o site não está sendo atualizado.

Avaliação: 🟡 Necessita atenção.

Sugestão
Separar as informações em categorias mais específicas:

```text
Notícias
Editais
Processos Seletivos
Resultados
````

10. Política de Privacidade
Pergunta
É possível encontrar a Política de Privacidade em menos de 3 cliques?

Durante a auditoria, não foi identificado um acesso claramente destacado para a Política de Privacidade na página inicial.

Evidência
(Adicionar evidência visual aqui, se houver)

Análise
A Política de Privacidade é uma informação institucional importante, principalmente em um site que disponibiliza formulários para coleta de dados.

A ausência de um acesso evidente dificulta a encontrabilidade dessa informação.

Avaliação: 🔴 Necessita melhoria.

Sugestão
Adicionar no rodapé:
```text
Política de Privacidade | Termos de Uso | Acessibilidade | Contato
````

11. Contato
A área de contato apresenta formulário com:

Nome;

Telefone;

E-mail;

Mensagem.

Também apresenta o endereço físico da instituição.

Evidência
(Adicionar evidência visual aqui, se houver)

Análise
Nesse aspecto, o site apresenta uma organização adequada.

O usuário consegue identificar facilmente onde deve entrar em contato com a instituição.

Avaliação: 🟢 Boa.

12. Resumo da auditoria
Critério	Avaliação	Observação
Organização por tópicos	🟢 Boa	As áreas institucionais estão bem divididas
Orientação por tarefas	🔴 Baixa	Poucos acessos são orientados às tarefas do usuário
Rotulagem	🟡 Razoável	Os rótulos são claros, mas faltam categorias importantes
Navegação	🟡 Razoável	Funcional, porém pouco orientada a tarefas
Encontrar cursos	🟡 Razoável	É necessário identificar que cursos estão em Educação
Encontrar editais	🔴 Difícil	Não existe acesso principal claramente identificado
Encontrar inscrições	🔴 Difícil	Não há destaque evidente para essa tarefa
Encontrar resultados	🔴 Difícil	Informações podem exigir interpretação do usuário
Política de Privacidade	🔴 Difícil	Não foi localizado acesso claramente destacado
Contato	🟢 Boa	Formulário e endereço facilmente identificáveis
13. Principais problemas encontrados
🔴 1. Estrutura pouco orientada às tarefas: O site apresenta principalmente as áreas da instituição, mas não destaca as principais tarefas que um usuário pode querer realizar.

🔴 2. Cursos não possuem destaque principal: O usuário precisa interpretar que Educação é o caminho para encontrar os cursos.

🔴 3. Editais não possuem uma categoria principal: Uma informação importante para quem deseja ingressar em um curso não está claramente representada na navegação principal.

🔴 4. Processos seletivos e resultados: Editais, resultados e retificações podem exigir interpretação do usuário para identificar o conteúdo desejado.

🔴 5. Política de Privacidade: Não existe um acesso claramente destacado na página inicial.

🟡 6. Novidades: A seção existe, mas não deixa claro que tipo de informação o usuário deve procurar nela.

14. Proposta de melhoria
Uma estrutura mais orientada ao usuário poderia ser:

Plaintext
INÍCIO
├── EDUCAÇÃO
│   ├── Cursos
│   ├── Graduação
│   ├── Pós-Graduação
│   ├── Capacitação
│   └── Educação Empresarial
│
├── PROCESSOS SELETIVOS
│   ├── Inscrições Abertas
│   ├── Editais
│   ├── Resultados
│   └── Retificações
│
├── INOVAÇÃO E TECNOLOGIA
│
├── CONSULTORIA
│
├── SOBRE O ITEAM
│
├── PERIÓDICOS
│
├── NOTÍCIAS
│
└── CONTATO
Essa estrutura mantém as áreas institucionais existentes, mas acrescenta acessos orientados às principais tarefas dos usuários.

15. Conclusão
A auditoria demonstra que o site do ITEAM possui informações relevantes e uma estrutura institucional compreensível.  
TXT

Entretanto, quando analisado pela perspectiva do usuário, principalmente de um possível aluno, existem dificuldades para encontrar algumas informações importantes.  
TXT

O principal problema identificado não é necessariamente a ausência de informação, mas a dificuldade de encontrar a informação certa no momento em que o usuário precisa dela.  
TXT

Para um usuário interessado em estudar, o caminho esperado seria:

Plaintext
Quero estudar
      ↓
Encontrar um curso
      ↓
Ver informações do curso
      ↓
Encontrar o edital
      ↓
Verificar as inscrições
      ↓
Realizar a inscrição
      ↓
Consultar o resultado
Essa sequência de tarefas não está representada de forma evidente na estrutura atual do site.  
TXT

Resultado geral
🟡 Arquitetura da Informação funcional, porém com oportunidades significativas de melhoria em encontrabilidade e orientação por tarefas.

**🟡 Arquitetura da Informação funcional, porém com oportunidades significativas de melhoria em encontrabilidade e orientação por tarefas.**
atividade-01.md
Exibindo atividade-01.md.
