## Grupo 24 - Pós Tech - FIAP

# Aplicação de Blogging Dinâmico: Minha Sala Virtual

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

## Instruções para Acessar e Rodar o Projeto

1. **Acesse a Plataforma OutSystems**
   - Vá para a [OutSystems](https://www.outsystems.com/).

2. **Download do Ambiente de Desenvolvimento**
   - Após fazer o login na sua conta, faça o download e acesse o ambiente de desenvolvimento da OutSystems, conhecido como Service Studio.

3. **Faça Login**
   - Após fazer o download do ambiente de desenvolvimnto, utilize o login e senha fornecidos pela equipe para acessar a conta onde o projeto está hospedado:
   - E-mail: fiapgrupo24full@gmail.com
   - Senha: joaomariajose

4. **Abra o Projeto**
   - No Service Studio, abra o projeto de blogging dinâmico.
   - Se o projeto não estiver visível na lista de projetos recentes, utilize a função de busca para encontrá-lo.

5. **Publicar o Projeto**
   - Com o projeto aberto, clique no botão de `1-Click Publish` para publicar a aplicação no ambiente de desenvolvimento.

6. **Executar a Aplicação**
   - Após a publicação, uma página web será aberta automaticamente pelo Service Studio e irá executar a aplicação em seu navegador.
   - Verifique se todas as funcionalidades estão operacionais conforme descritas na documentação.


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

Ariel - 355696 <br>
arielandrielli100@gmail.com 
