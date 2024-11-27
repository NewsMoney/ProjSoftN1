<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*Sistema de Controle de Presenças Escola Infinito*
</center></font>

**Conteúdo**

- [Autor](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autor

* Milton Almeida Leôncio

# Descrição do Projeto

O projeto consiste no desenvolvimento de um Sistema de Controle de Presenças para a Escola Infinito, que atualmente realiza o registro de presenças de forma manual, em papel. O sistema visa automatizar o processo de controle de faltas dos alunos, facilitando o trabalho dos professores e a gestão escolar.

Principais funcionalidades:

- Registro de Faltas: Os professores podem registrar as faltas de forma fácil e intuitiva.
- Relatórios: O sistema gera relatórios detalhados de faltas, filtráveis por data, turma, professor, disciplina ou aluno.
- Notificações: Envio automático de e-mails aos pais quando a frequência do aluno cai abaixo de 80%.
- Acessibilidade: Suporte para pessoas com deficiência, com funcionalidades como ajuste de tamanho de fonte.
- Acesso Web: Disponível em navegadores, incluindo dispositivos móveis.

O sistema busca substituir o processo atual por uma solução mais eficiente e acessível, garantindo que o acompanhamento das presenças seja mais organizado e prático.

# Análise de Requisitos Funcionais e Não-Funcionais
*Requisitos Funcionais:*

- O sistema deve permitir que os usuários façam login utilizando um nome de usuário e senha, diferenciando os perfis de professores e responsáveis, com permissões específicas para cada tipo de usuário.
- Os professores devem ser capazes de registrar as faltas de forma intuitiva e rápida, permitindo o acompanhamento diário das presenças dos alunos em cada turma.
- O sistema deve gerar relatórios detalhados de faltas, com a opção de filtrar por diversos critérios, incluindo Data específica ou intervalo de datas, Ano escolar ou turma, Professor responsável, Disciplina ou aluno.
- O sistema deve monitorar a frequência dos alunos e enviar automaticamente notificações por e-mail para os pais ou responsáveis, caso a frequência do aluno fique abaixo de 80%.
- O sistema deve garantir suporte a usuários com necessidades especiais, incluindo funcionalidades como ajuste de tamanho de fonte e navegação facilitada.
- O sistema deve ser acessível via navegadores da web, sendo compatível com computadores e dispositivos móveis, permitindo o uso em diferentes plataformas sem comprometer a experiência do usuário.

*Requisitos Não-Funcionais:*

- O sistema deve ser capaz de processar o login e a consulta de relatórios em até 2 segundos, garantindo rapidez no acesso aos dados.
- Todas as informações de login e dados de alunos devem ser protegidos por criptografia, garantindo a confidencialidade e integridade das informações.
- O sistema deve ser escalável para suportar o crescimento do número de usuários, podendo acomodar turmas maiores e um aumento no número de professores sem perda de desempenho.
- O sistema deve ser compatível com os principais navegadores (Chrome, Firefox, Edge, Safari) e funcionar adequadamente em dispositivos móveis com diferentes resoluções.
- A interface do sistema deve ser amigável e de fácil navegação, minimizando a curva de aprendizado para os usuários (professores e administradores).
- O sistema deve ter uma disponibilidade mínima de 99%, garantindo que esteja sempre acessível durante os horários de funcionamento da escola.
  
# Diagrama de Atividades

*Diagrama para visualizar o comportamento do sistema*

![Desenho (1)](https://github.com/user-attachments/assets/b5bf8319-cb77-4687-afc2-7339b1daa11f)

# Diagrama de Casos de Uso

*Diagrama para visualizar o comportamento dos atores*

![Casos_de_Uso (1)](https://github.com/user-attachments/assets/3f33ff5b-26f1-4c3f-8f69-6924f99bf925)

# Descrição dos Casos de Uso

*Requisitos Funcionais*

Efetuar Login:
- O sistema deve permitir que o usuário faça login com suas credenciais (nome de usuário e senha) para acessar suas funcionalidades.
- Ator: Pessoa.

Verificar Faltas:
- O sistema deve permitir que o responsável consulte as faltas registradas do aluno.
- Ator: Responsável.

Lançar Faltas:
- O sistema deve permitir que o professor registre as faltas de seus alunos.
- Ator: Professor.

Gerar Relatório de Faltas:
- O sistema deve gerar um relatório com todas as faltas registradas por um determinado período de tempo.
- Ator: Professor.

*Requisitos Não Funcionais*

Segurança:
- O sistema deve garantir a segurança dos dados dos usuários, utilizando criptografia para as senhas e protocolos de segurança no login.

Desempenho:
- O sistema deve ser capaz de gerar o relatório de faltas em até 5 segundos, mesmo com uma grande quantidade de dados.

Acessibilidade:
- A interface do sistema deve ser intuitiva e acessível tanto para professores quanto para alunos e responsáveis.

*Restrições*

Compatibilidade:
- O sistema deve ser compatível com navegadores modernos e deve funcionar em dispositivos móveis.

Autenticação:
- Apenas usuários autenticados (professores ou responsáveis) podem acessar suas respectivas funcionalidades.

# Diagrama de Sequência

*Diagrama de ordem e interação dos objetos*

![Diagrama de sequencia drawio](https://github.com/user-attachments/assets/7faa9c34-ff75-497f-b3fc-fd4e406055d6)

# Diagrama de Classes

*Diagrama de relacionamento entre classes para os seus atributos e operações*

![Diagrama de Classes](https://github.com/user-attachments/assets/264fcbb5-1e39-49f5-97d7-f26a07f35618)

# Diagrama de Estados

*Diagrama para modelar o comportamento interno de um determinado objeto, subsistema ou sistema global*

![Diagrama de Estados](https://github.com/user-attachments/assets/d8fb22c6-8f0e-4c2a-a764-82bc5d7439c1)

# Diagrama de Implantação

*Diagrama para exibir o relacionamento de hardware e software no projeto*

# Referências

*&lt;Lista de referências&gt;*
