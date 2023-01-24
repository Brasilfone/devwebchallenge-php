# Descrição do projeto:
  Tecnologias: 
      * PHP com Zend Framework 2 ou Laravel
      * PostgreSQL com Doctrine ou outro ORM
   
- Crie uma pagina de "login". 
- Crie uma pagina de "cadastre-se", que valida apenas se o e-mail está no formato correto e cadastra usuários em banco de dados. 
- O usuário precisa conter nome, e-mail e senha.
- As páginas precisam estar funcionais, com verificação no banco de dados se o usuário existe, se a senha e acesso estão corretos.
- Ao acessar o login deve direcionar para uma página inicial com uma mensagem de bem vindo {{ nome }}.
- Crie uma pagina para cadastro de Setores, simulando uma empresa de telecomunicações (Financeiro, Comercial, Suporte, Atendimento, Desenvolvimento)
- Crie uma pagina para cadastro de Empregados da empresa, nesse mesmo cadastro, deve listar os setores cadastrados e vincular o setor ao empregado (os campos do cadastro do empregado ficam ao seu critério)

# Diferencial:

- Ampliar o projeto com sua criatividade e abordar o máximo desses relacionamentos que conseguir:
  - OneToMany;
  - ManyToOne;
  - ManyToMany;
  - OneToOne;

- Criar um api em Node.js que:
  - Liste os usuários cadastrados;
  - CRUD de Setores;
  - CRUD de Empregados;
 
- **Somente se tiver conhecimentos em IA**: Mostrar algum case que você criou ou participou;

# Opcional:
- Utilizar Zend Framework 3 no lugar do Zend Framework 2 - (pensando em migrar/criar sistemas com o ZF3);
- Criar todo o projeto com Nest.js, Next.js e PostgreSQL | MongoDB;


As referências para a tela de login podem ser visualizadas neste repositório na pasta: 
devwebchallenge/project-images/

Não há necessidade do projeto estar igual as imagens, é apenas uma referência do que é esperado. 


## O que nós vamos avaliar

- O seu código será avaliado por: semântica, estrutura, legibilidade, tamanho, ferramentas utilizadas, entre outros fatores, principalmente as habilidades descritas em seu currículo.
- O histórico do `git` será avaliado.
- Nossa stack atual é: PHP 7.3, Zend Framework 2, Doctrine ORM, Javascript, Node.js, PostGreSQL, Linux. 
- Não se esqueça de documentar o processo necessário para rodar a sua solução. Ou senão, como nós iremos iniciar o projeto em nossas máquinas?

Todas as etapas acima devem ser enviadas em um único e-mail para: desenvolvimento@brasilfone.com.br

Qualquer dúdiva que surgir com relação ao desafio, estaremos a disposição para sanar. 
