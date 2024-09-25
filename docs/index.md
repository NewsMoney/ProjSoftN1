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

- O sistema deve permitir que os usuários façam login utilizando um nome de usuário e senha, diferenciando os perfis de professores e alunos, com permissões específicas para cada tipo de usuário.
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
![Desenho](https://github.com/user-attachments/assets/27780342-4bd7-4c04-94c0-069ed418c127)

# Diagrama de Casos de Uso

*Diagrama para visualizar o comportamento dos atores*
[Uploading Casos_de_Uso.xml…]()<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/128.0.0.0 Safari/537.36" version="24.7.16">
  <diagram name="Página-1" id="qzN4ffmXO8ULz5gD4bQf">
    <mxGraphModel dx="1147" dy="590" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="m8unOGw93lnWI2KK6Zvd-19" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="m8unOGw93lnWI2KK6Zvd-1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="329" y="524" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-1" value="Aluno/Resposavel" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;" vertex="1" parent="1">
          <mxGeometry x="260.5" y="554" width="30" height="60" as="geometry" />
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-18" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;curved=0;" edge="1" parent="1" source="m8unOGw93lnWI2KK6Zvd-3">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="379" y="524" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-27" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="431" y="635" as="sourcePoint" />
            <mxPoint x="314" y="663" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-3" value="Professor" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;shadow=0;" vertex="1" parent="1">
          <mxGeometry x="421.5" y="554" width="30" height="60" as="geometry" />
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-9" value="Verificar faltas" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="218" y="664" width="115" height="60" as="geometry" />
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-10" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.487;entryY=0.015;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="275.4" y="634" as="sourcePoint" />
            <mxPoint x="275.405" y="654.9" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-30" style="rounded=1;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;dashed=1;" edge="1" parent="1" source="m8unOGw93lnWI2KK6Zvd-11" target="m8unOGw93lnWI2KK6Zvd-29">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-11" value="Lançar Faltas" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="379" y="664" width="115" height="60" as="geometry" />
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-12" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.487;entryY=0.015;entryDx=0;entryDy=0;entryPerimeter=0;endArrow=none;endFill=0;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="436.4" y="634" as="sourcePoint" />
            <mxPoint x="436.405" y="654.9" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-21" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;" edge="1" parent="1" source="m8unOGw93lnWI2KK6Zvd-13">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="489" y="474" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-13" value="Pessoa" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;outlineConnect=0;shadow=0;" vertex="1" parent="1">
          <mxGeometry x="339" y="444" width="30" height="60" as="geometry" />
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-20" value="Efetuar login" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="494" y="444" width="115" height="60" as="geometry" />
        </mxCell>
        <mxCell id="m8unOGw93lnWI2KK6Zvd-29" value="Gerar relatorio de&lt;br&gt;faltas" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="299" y="770" width="115" height="60" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
