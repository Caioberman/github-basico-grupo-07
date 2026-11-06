# 📘 CARTILHA DO GITHUB
## Guia básico para novos usuários

**Objetivo:** Ensinar novos usuários a compreender e utilizar o GitHub, apresentando suas principais funcionalidades e ferramentas, desde a criação de uma conta até o compartilhamento e gerenciamento de projetos.

---<img width="700" height="700" alt="cbb993a9f7929507d21f41155e0d374c" src="https://github.com/user-attachments/assets/218efada-a426-4e64-bc24-710140b39377" />


# 1. O que é GitHub e qual é a diferença entre Git e GitHub?

### O que é Git?

O **Git** é um sistema de controle de versão utilizado para registrar e acompanhar alterações realizadas em arquivos de um projeto.

Ele permite que os usuários acompanhem o desenvolvimento de um projeto, recuperem versões anteriores e trabalhem em conjunto sem perder o histórico das modificações.

### O que é GitHub?

O **GitHub** é uma plataforma online que utiliza o Git para hospedar repositórios e facilitar o desenvolvimento colaborativo de projetos.

Por meio dele, é possível armazenar códigos, compartilhar projetos, colaborar com outros desenvolvedores e acompanhar as mudanças realizadas.

### Qual é a diferença?

| Git | GitHub |
|---|---|
| É um sistema de controle de versão. | É uma plataforma online. |
| Funciona localmente no computador. | Funciona pela internet. |
| Registra alterações nos arquivos. | Hospeda repositórios e facilita a colaboração. |
| Pode funcionar sem internet. | Depende de conexão para acessar os serviços online. |

**Exemplo:** O Git funciona como uma ferramenta que registra todas as versões de um trabalho, enquanto o GitHub funciona como um espaço online onde esse trabalho pode ser armazenado e compartilhado.

---

# 2. O que é um repositório e qual é a diferença entre público e privado?

Um **repositório**, também conhecido como *repository* ou simplesmente *repo*, é um espaço destinado ao armazenamento de arquivos de um projeto.

Ele pode conter códigos, imagens, documentos, vídeos, arquivos de configuração e outros materiais necessários para o desenvolvimento de um projeto.

No GitHub, os repositórios também armazenam o histórico de alterações realizadas nos arquivos.

### Tipos de repositório

**Repositório público (Public)**

- Qualquer pessoa pode visualizar o conteúdo.
- Pode ser encontrado por meio de pesquisas no GitHub.
- É ideal para projetos que precisam ser compartilhados.
- Outros usuários podem contribuir, dependendo das permissões e configurações.

**Repositório privado (Private)**

- Somente o proprietário e as pessoas autorizadas podem acessar.
- Não aparece publicamente para usuários sem permissão.
- É recomendado para projetos particulares ou que contenham informações restritas.
- Permite colaboração com pessoas selecionadas.

### Como criar um repositório?

1. Acesse o site https://github.com/.
2. Entre na sua conta.
3. Clique no botão **New**, localizado na área de criação de repositórios.
4. Digite um nome para o repositório.
5. Adicione uma descrição, se desejar.
6. Escolha entre público ou privado.
7. Marque a opção **Add a README file**, caso queira criar um arquivo de apresentação.
8. Clique em **Create repository**.

Pronto! Seu primeiro repositório estará criado.

--- <img width="1138" height="926" alt="Criando um repositorio no GitHub" src="https://github.com/user-attachments/assets/a89c24e7-14d4-4f52-91fb-19583119d15b" />


# 3. Para que servem README, Markdown, commit e histórico de alterações?

Esses quatro elementos são fundamentais para organizar e acompanhar um projeto no GitHub.

### README

O arquivo `README.md` é utilizado para apresentar e explicar um projeto.

Normalmente, ele contém:

- Nome do projeto.
- Descrição e objetivo.
- Instruções de instalação.
- Como utilizar o projeto.
- Tecnologias utilizadas.
- Informações sobre os responsáveis.

É geralmente o primeiro arquivo que uma pessoa encontra ao acessar um repositório.

<img width="1279" height="545" alt="colocando arquivos na pasta (1)" src="https://github.com/user-attachments/assets/f381247a-32cf-4094-9d0e-1ad1f61b31ef" />


### Markdown

Markdown é uma linguagem de marcação simples utilizada para formatar textos.

No GitHub, ela é bastante utilizada em arquivos `.md`, como o README.

Exemplos de formatação:

| Código Markdown | Resultado |
|---|---|
| `# Título` | Título principal |
| `## Subtítulo` | Subtítulo |
| `**Negrito**` | **Negrito** |
| `*Itálico*` | *Itálico* |
| `- Item` | Lista |
| `[Google](https://google.com)` | Link |

Exemplo de código:

```markdown
# Meu Projeto

Este é meu primeiro projeto no GitHub.

## Objetivo

Aprender a utilizar a plataforma.

## Tecnologias

- HTML
- CSS
- JavaScript
```

### Commit

Um **commit** é um registro de alterações realizadas em um repositório.

Sempre que um usuário realiza modificações e deseja registrá-las, pode criar um commit acompanhado de uma mensagem explicando o que foi alterado.

Exemplos de mensagens:

- `Adiciona página inicial`
- `Corrige erro no formulário`
- `Atualiza documentação`
- `Remove arquivos desnecessários`

O commit funciona como um ponto de registro na evolução do projeto.

### Histórico de alterações

O histórico de alterações, conhecido como *commit history*, permite visualizar os registros das modificações realizadas no projeto.

Por meio dele, é possível:

- Identificar quem realizou uma alteração.
- Consultar quando ela foi feita.
- Verificar quais arquivos foram modificados.
- Comparar versões diferentes.
- Recuperar versões anteriores, quando necessário.

Para acessar o histórico, entre em um repositório e clique na opção **Commits**, normalmente disponível na área de arquivos.

---

# 4. O que são branch, pull request e merge?

Esses recursos permitem que diferentes pessoas trabalhem no mesmo projeto de maneira organizada.

### Branch

Uma *branch* é uma ramificação do projeto utilizada para desenvolver funcionalidades ou realizar modificações sem alterar diretamente a versão principal.

A branch principal costuma ser chamada de `main`.

**Exemplo:**

Imagine que você possui um site e deseja adicionar uma página de contato.

Em vez de modificar diretamente a versão principal, você pode criar uma branch chamada `pagina-contato` e realizar todas as alterações nela.

Assim, a versão principal permanece intacta enquanto o trabalho está sendo desenvolvido.

### Pull Request (PR)

Um *Pull Request* é uma solicitação para integrar as alterações realizadas em uma branch a outra branch.

Ele permite que outros colaboradores analisem as modificações antes de serem incorporadas ao projeto.

Durante essa análise, os colaboradores podem:

- Visualizar as alterações.
- Fazer comentários.
- Solicitar correções.
- Aprovar as modificações.


### Merge

O *merge* é o processo de integrar as alterações de uma branch em outra.

Por exemplo, depois que uma funcionalidade é desenvolvida e aprovada por meio de um Pull Request, é possível realizar o merge para incorporar as alterações à branch principal.

### Como funciona o processo?

1. Criar uma nova branch.
2. Realizar as modificações necessárias.
3. Criar commits para registrar as alterações.
4. Abrir um Pull Request.
5. Aguardar a revisão dos colaboradores.
6. Realizar o merge após a aprovação.

Esse processo ajuda a evitar conflitos e mantém o desenvolvimento organizado.

---<img width="1134" height="794" alt="fazendo branch pull request e merge" src="https://github.com/user-attachments/assets/781240b8-ad6c-4af8-b2e7-788890866549" />


# 5. Como compartilhar um repositório e quais cuidados tomar ao publicar arquivos?

O GitHub permite compartilhar repositórios com outras pessoas de maneira simples.

### Como compartilhar um repositório?

1. Acesse o repositório que deseja compartilhar.
2. Copie o endereço presente na barra de navegação do navegador ou utilize a opção de copiar o link.
3. Envie o endereço para a pessoa desejada.

Se o repositório for público, qualquer pessoa poderá visualizar seu conteúdo.

Se for privado, será necessário conceder acesso ao usuário.

### Como adicionar colaboradores?

1. Entre no repositório.
2. Acesse **Settings**.
3. Procure a seção **Collaborators** ou **Collaborators and teams**.
4. Clique em **Add people**.
5. Pesquise o nome de usuário ou endereço de e-mail da pessoa.
6. Envie o convite.

A pessoa precisará aceitar o convite para obter acesso.

### Cuidados ao publicar arquivos

Antes de enviar arquivos para um repositório, é importante verificar se eles contêm informações que não deveriam ser compartilhadas.

**Nunca publique:**

- Senhas pessoais.
- Chaves de API.
- Tokens de autenticação.
- Dados bancários.
- Documentos pessoais.
- Informações confidenciais de empresas ou terceiros.

**Outros cuidados importantes:**

- Verifique se os arquivos enviados são realmente necessários.
- Utilize um arquivo `.gitignore` para evitar o envio de arquivos desnecessários.
- Respeite os direitos autorais de imagens, códigos e documentos.
- Revise o conteúdo antes de tornar um repositório público.
- Utilize senhas fortes e autenticação em dois fatores na sua conta.

**Atenção:** Tornar um repositório privado não substitui boas práticas de segurança. Informações confidenciais não devem ser armazenadas sem proteção adequada.

---

# 6. Como ensinar um usuário novo a utilizar a plataforma?

Para um usuário que nunca utilizou o GitHub, o ideal é começar pelas funções mais simples e avançar gradualmente para os recursos mais complexos.

A seguir, está um roteiro prático para realizar as primeiras atividades na plataforma.

## Etapa 1 – Criando uma conta

1. Acesse https://github.com/.
2. Clique em **Sign up**.
3. Informe seu endereço de e-mail.
4. Crie uma senha.
5. Escolha um nome de usuário.
6. Complete as etapas de verificação solicitadas.
7. Finalize o cadastro.

Depois de criar a conta, faça login na plataforma.

<img width="1350" height="857" alt="Criando uma conta no GitHub" src="https://github.com/user-attachments/assets/e3fe86bf-e290-438a-b7f5-f380da55ac53" />

## Etapa 2 – Conhecendo a interface

Ao entrar no GitHub, você encontrará algumas áreas importantes:

| Elemento | Função |
|---|---|
| Dashboard | Página inicial com atividades e repositórios. |
| Repositories | Lista de repositórios da conta. |
| Search | Ferramenta de pesquisa. |
| Issues | Área para registrar problemas e tarefas. |
| Pull Requests | Área para revisar alterações. |
| Profile | Página com informações públicas do usuário. |

Conhecer essas áreas facilita a navegação e a utilização da plataforma.

## Etapa 3 – Criando seu primeiro repositório

1. Clique em **New**.
2. Escolha um nome para o projeto.
3. Escreva uma breve descrição.
4. Escolha a visibilidade pública ou privada.
5. Marque a opção para adicionar um README.
6. Clique em **Create repository**.

Agora você possui um espaço para armazenar seus arquivos.

## Etapa 4 – Adicionando arquivos

Dentro do repositório:

1. Clique em **Add file**.
2. Escolha **Create new file** para criar um arquivo diretamente no GitHub ou **Upload files** para enviar arquivos do computador.
3. Escolha o nome do arquivo.
4. Adicione o conteúdo, se estiver criando um arquivo novo.
5. Clique em **Commit changes**.
6. Escreva uma mensagem explicando a alteração.
7. Confirme o commit.

Pronto! Seu arquivo estará armazenado no repositório.

## Etapa 5 – Editando arquivos

Para modificar um arquivo diretamente pelo navegador:

1. Abra o repositório.
2. Clique no arquivo que deseja modificar.
3. Clique no ícone de lápis, chamado **Edit this file**.
4. Faça as alterações necessárias.
5. Clique em **Commit changes**.
6. Escreva uma mensagem descrevendo o que foi modificado.
7. Confirme a alteração.

O GitHub registrará a nova versão no histórico do projeto.

## Etapa 6 – Criando uma branch

1. Entre no repositório.
2. Clique no seletor de branches, onde normalmente aparece `main`.
3. Digite o nome da nova branch.
4. Selecione a opção para criar uma nova branch a partir da atual.

Agora você poderá trabalhar em uma versão separada do projeto.


## Etapa 7 – Criando um Pull Request

Depois de realizar alterações em uma branch:

1. Acesse a aba **Pull requests**.
2. Clique em **New pull request**.
3. Selecione a branch que contém suas alterações.
4. Escolha a branch de destino, normalmente `main`.
5. Confira as modificações.
6. Clique em **Create pull request**.
7. Escreva um título e uma descrição explicando o que foi alterado.

## Etapa 8 – Realizando o Merge

Depois que as alterações forem revisadas e aprovadas:

1. Abra o Pull Request.
2. Verifique se não existem conflitos ou impedimentos.
3. Clique em **Merge pull request**.
4. Confirme a operação.

As alterações serão incorporadas à branch de destino.

---

# 7. Dicas para novos usuários

Para aproveitar melhor o GitHub, é importante seguir algumas boas práticas:

1. Utilize nomes claros para seus repositórios.
2. Mantenha o README atualizado.
3. Faça commits com mensagens objetivas.
4. Organize os arquivos em pastas.
5. Utilize branches para desenvolver novas funcionalidades.
6. Revise os arquivos antes de publicá-los.
7. Evite compartilhar informações confidenciais.
8. Consulte a documentação oficial quando tiver dúvidas.

---

# 8. Conclusão

O GitHub é uma ferramenta importante para o armazenamento, organização e desenvolvimento colaborativo de projetos.

Aprender a utilizar seus recursos básicos permite que qualquer usuário comece a criar repositórios, compartilhar arquivos, acompanhar alterações e colaborar com outras pessoas.

Mesmo para quem nunca teve contato com programação ou controle de versão, a plataforma oferece ferramentas acessíveis que facilitam o aprendizado.

**O mais importante é praticar:** criar um repositório, adicionar arquivos, realizar commits e experimentar as funcionalidades disponíveis.

---

# 9. Materiais complementares

Para aprofundar seus conhecimentos, consulte os materiais oficiais:

- [GitHub – Site oficial](https://github.com/)
- [GitHub Docs – Documentação oficial](https://docs.github.com/pt)
- [Git – Documentação oficial](https://git-scm.com/doc)
- [GitHub Skills – Cursos práticos](https://skills.github.com/)
- [GitHub Markdown – Guia de sintaxe](https://docs.github.com/pt/get-started/writing-on-github)

---

**Documento:** Cartilha introdutória do GitHub  
**Público-alvo:** Novos usuários da plataforma  
**Formato:** Markdown (.md)
