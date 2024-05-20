## Grupo 24 - Pós Tech - FIAP

# Aplicação de Blogging Dinâmico

## Visão Geral

Esta aplicação de blogging dinâmico foi desenvolvida na plataforma OutSystems para permitir que professores e professoras da rede pública de educação postem suas aulas e transmitam conhecimento de maneira prática, centralizada e tecnológica. A aplicação possui funcionalidades específicas para alunos e alunas (visualização e leitura de posts) e uma visão administrativa para docentes (gerenciamento de postagens).

## Estrutura da Aplicação

### Visão dos Alunos e Alunas
- **Página Principal**: Exibe uma lista de posts.
- **Página de Leitura**: Exibe o conteúdo de um post específico.

### Visão Administrativa para Professores e Professoras
- **Página de Listagem de Postagens**: Exibe todas as postagens criadas.
- **Página de Criação de Postagens**: Permite a criação de novas postagens.
- **Página de Edição de Postagens**: Permite a edição de postagens existentes.
- **Funcionalidade de Exclusão**: Permite a exclusão de postagens.

## Fluxo da Aplicação

### Fluxo para Alunos e Alunas

#### Página Principal - Visualização de Posts

1. **Acesso à Página Principal**
   - O aluno ou aluna acessa a página principal da aplicação.
   - A página exibe uma lista de posts, mostrando o título e um breve resumo de cada postagem.
   - A lista de posts é carregada a partir de uma consulta à base de dados que armazena as postagens.

2. **Ação: Clicar no Título ou Resumo do Post**
   - Ao clicar no título ou resumo de um post, o aluno ou aluna é redirecionado para a página de leitura.

#### Página de Leitura - Leitura de Post

1. **Acesso à Página de Leitura**
   - A página de leitura é carregada com o conteúdo completo do post selecionado.
   - Os detalhes do post (título, autor, data e conteúdo) são exibidos.

### Fluxo para Professores e Professoras

#### Página de Listagem de Postagens - Gerenciamento de Postagens

1. **Acesso à Página de Listagem**
   - O professor ou professora acessa a visão administrativa.
   - A página de listagem exibe todas as postagens criadas, incluindo opções para criar, editar e excluir postagens.

#### Página de Criação de Postagens

1. **Acesso à Página de Criação**
   - O professor ou professora acessa a página de criação de postagens através de um botão na página de listagem.
   - Um formulário é exibido, permitindo a inserção do título, conteúdo e outros detalhes do post.

2. **Ação: Submeter o Formulário**
   - Ao submeter o formulário, os dados são validados e, se corretos, a nova postagem é salva na base de dados.
   - O professor ou professora é redirecionado de volta para a página de listagem, onde a nova postagem aparece.

#### Página de Edição de Postagens

1. **Acesso à Página de Edição**
   - O professor ou professora seleciona uma postagem para editar na página de listagem.
   - A página de edição exibe o formulário pré-preenchido com os dados da postagem existente.

2. **Ação: Submeter as Alterações**
   - Após editar os campos desejados, o professor ou professora submete o formulário.
   - Os dados são validados e, se corretos, a postagem atualizada é salva na base de dados.
   - O professor ou professora é redirecionado de volta para a página de listagem.

#### Funcionalidade de Exclusão de Postagens

1. **Ação: Excluir Postagem**
   - Na página de listagem, o professor ou professora clica no botão de exclusão correspondente à postagem desejada.
   - Uma confirmação de exclusão é exibida.
   - Ao confirmar, a postagem é removida da base de dados.
   - A lista de postagens é atualizada para refletir a exclusão.

## Considerações Finais

- **Autenticação e Autorização**
  - A aplicação possui um sistema de autenticação que diferencia alunos e alunas de professores e professoras.
  - Apenas usuários autenticados como professores e professoras têm acesso à visão administrativa.

- **Validação de Dados**
  - Tanto na criação quanto na edição de postagens, os dados são validados para garantir a consistência e integridade das informações.

- **Experiência do Usuário**
  - A interface da aplicação foi projetada para ser intuitiva e fácil de usar, garantindo que mesmo usuários com pouca experiência tecnológica possam utilizá-la eficientemente.

---

## Instruções para Clonar o Projeto

1. Faça a operação 'Clone' deste repositório:
   ```bash
   git clone git@github.com:FullStack24/techchallenge1.git

---

### Figma
https://www.figma.com/files/project/232236477/Team-project?fuid=1162739126089040030

---

### Membros:

Vitor Laurentino - RM 354411 <br>
vitorlaurentino@gmail.com 

José Luccas <br>
...@gmail.com 

Gustavo Carriel<br>
gucarriel@hotmail.com

Ariel <br>
...@gmail.com 
