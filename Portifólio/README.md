# Portfólio Kevin Romero Ribeiro 🙋🏽‍♂️

## Apresentação

Olá, sou o Kevin, sou aluno da FATEC de São José dos Campos atualmente no curso Desenvolvimento de Software Multiplataforma. 
Tenho 19 anos e atualmente trabalho como Desenvolvedor de Software Estagiário.
<br>

### Experiências
Atualmente tenho experiências em Python, Java, TypeScript, JavaScript, React, Node, Flask, MySQL, Oracle e NoSQL.
<br>
<br>

## Projetos 💻

### [API - 1º Semestre](https://github.com/whatscodeg3/API-DSM-ServiceDesk)

## Empresa Parceira 
FATEC Prof. Jessen Vidal (projeto proposto pelos professores da FATEC)
<br>

## Resumo do Projeto 

Em geral, uma Central de Serviços é uma ferramenta que oferece assistência para resolver problemas no ambiente de tecnologia da informação. Esse projeto foi desenvolvido com base na metodologia ágil SCRUM, que tem como objetivo principal promover a proatividade, autonomia e aprimorar a produtividade da equipe como um todo. A Central de Serviços é uma plataforma integrada que visa atender as demandas e necessidades dos usuários, fornecendo suporte e soluções eficientes para problemas técnicos e requisições de serviço. Neste projeto, foi utilizado a metodologia SCRUM, baseada em princípios ágeis, enfatiza a colaboração, a comunicação e a flexibilidade. No contexto da Central de Serviços, a equipe adota uma abordagem iterativa e incremental para o desenvolvimento e aprimoramento contínuos da plataforma. Isso permite que sejam priorizadas as tarefas mais importantes, levando em consideração as necessidades dos usuários e as demandas do ambiente de TI.

## Tecnologias 
* HTML
* CSS
* JavaScript
* Python
* Flask
* SQL Alchemy
* MySQL

## Contribuições Pessoais
Neste projeto, desempenhei um papel fundamental no desenvolvimento das interfaces utilizando HTML, CSS e JavaScript, visando garantir uma experiência de usuário atraente e intuitiva. Trabalhei na criação e estilização dos elementos HTML, aplicando CSS para tornar o design visualmente agradável e responsivo em diferentes dispositivos.

Além disso, contribuí significativamente com o desenvolvimento do framework Flask, responsável por gerenciar as requisições do back-end e estabelecer as conexões eficientes com o front-end. Participei ativamente na construção das rotas do Flask, que definem como as requisições do usuário são tratadas e como as respostas são enviadas de volta.

Durante o projeto, pude aprender e praticar JavaScript para melhorar a interatividade e a funcionalidade das páginas, implementando recursos dinâmicos como animações, manipulação do DOM e principalmente a construção 
de graficos da página de relatórios.

No geral, minha contribuição foi essencial para o desenvolvimento de uma aplicação web completa, onde pude aplicar meus conhecimentos em HTML, CSS, JavaScript e Flask para criar uma experiência de usuário atraente, intuitiva e funcional.

<details>
    
  <Summary>Contribuições Front-End</Summary>
    
  > Nesse código por exemplo eu pude contribuir no desenvolvimento de um gráfico utilizando a biblioteca ChartsJS. Escrevi o código 
    necessário para configurar e personalizar o gráfico, incluindo o tipo de gráfico, os datasets e as opções adicionais. Também 
    implementei funcionalidades avançadas, como atualização em tempo real dos dados e interatividade com o usuário.
  
  ```javascript
    const ctx1 = document.getElementById(id).getContext('2d');
    const myChart1 = new Chart(ctx1, {
        type: 'pie',
        data: {
        labels: ['Abertos', 'Fechados'],
        datasets: [
            {
            label: 'Chamados',
            data: dado,
            backgroundColor: ['#FF4343', '#6CEC90'],
            borderColor: ['#292A2F'],
            borderWidth: 7,
            tension: 0.1
            }
        ]
        },
        options: {
        scales: {
            y: {
            min: 0,
            max: 100
            }
        }
        }
    });

    };
  ```
    
  <br>
</details>

<details>
    
  <Summary>Contribuições Back-End</Summary>
  
> Durante o desenvolvimento do projeto, tive a oportunidade de criar rotas utilizando o framework Flask. O código abaixo é um exemplo 
    de uma rota simples que eu criei com uma funcionalidade específica. Essa rota é responsável por lidar com a verificação do usuário. 
    Primeiramente, é verificado se o usuário está autenticado. Se sim, o código solicita a lista do histórico de solicitações desse 
    usuário, enviando o ID do usuário como parâmetro. Em seguida, a página de histórico é renderizada, exibindo a lista do histórico de 
    solicitações. No caso de o usuário não estar verificado, ele é redirecionado para a página inicial do aplicativo.    
    
  ```python
     @contacts.route('/historico')
     def historico():
         if g.user != None:
             if g.user[0] == 1 or g.user[0] == 2 or g.user[0] == 3:
                 print(g.id_usuario)
                 lista = Solicita.query.filter_by(fk_id_usuario_comum=g.id_usuario)
                 return render_template('usuario-historico.html', listas=lista, user=session['user'])     
         return redirect(url_for('contacts.index'))
  ```
  
  <br>
</details>


## Aprendizados Efetivos

#### Hard Skills  
Pude neste projeto tive a oportunidade de desenvolver novas habilidades em tecnologias de front-end e back-end.

<details>
    <Summary>Ver Hard Skills desenvolvidas</Summary>
    
* HTML - No desenvolvimento do layout das interfaces;
    
* CSS - No desenvolvimento da estilização das interfaces;
    
* JavaScript - No desenvolvimento de manipulação do DOM e na construção de graficos da página de relatórios;
    
* Python - No desenvolvimento do microframework Flask.
    
* Flask - No desenvolvimento das rotas e na conexão do back-end com o front-end;
    
* MySQL - Ao lidar com as querrys para fazer chamadas no banco de dados.
    
</details>

#### Soft Skills 
Pude também estar desenvolvendo e aprimorando algumas softskills sendo elas:

<details>
    <Summary>Ver Soft Skills desenvolvidas</Summary>
    
* Comunicação: Nas apresentações de sprints;

* Trabalho em equipe: Ao lidar com a metodologia ágil SCRUM, seguindo ritos como: reuniões diárias(Dailys), reuniões de planejamento(Sprint Planning), reuniões de revisão(Sprint Review) e por fim, reuniões de retrospectiva(Sprint Retrospective);

* Autonomia: Sabendo o que devia ser feito e sempre entregando nos prazos corretos.
    
</details>
<br>

### [API - 2º Semestre](https://github.com/whatscodeg3/API-2DSM-DailyBot)

## Empresa Parceira 
MidAll
<br>

## Resumo do Projeto 

Desenvolver Crawler que consiga buscar, ler o arquivo e identificar o conteúdo relacionado aos Professores Associados, realizar os 
cruzamentos necessários com as bases de dados de associados, que suportarão está solução, gravar todos os processos publicados 
relacionados aos associados, e emitir relatório diário para que a equipe consiga disparar os e-mails para os professores citados 
no Diário Oficial. Caso consigam também realizar a automação do disparo destes e-mails seria uma sofisticação para a solução.

## Tecnologias 
* ReactJS
* StyledComponents
* JavaScript
* TypeScript
* NodeJS
* ExpressJS
* MySQL

## Contribuições Pessoais

Este projeto foi um pouco mais desafiador pois desempenhei o papel de Scrum Master. Como Scrum Master, fui responsável por facilitar a metodologia 
ágil Scrum e garantir a eficácia da equipe de desenvolvimento. Minhas principais responsabilidades incluíram facilitar as cerimônias do 
Scrum, remover obstáculos para a produtividade da equipe, apoiar o Product Owner, promover a colaboração e a transparência e aplicar 
melhorias contínuas. Consegui desempenhar um papel fundamental na criação de um ambiente de trabalho colaborativo, no cumprimento das metas 
do projeto e no gerenciamento eficaz do fluxo de trabalho da equipe de desenvolvimento.

Além disso, desempenhei outro papel fundamental, o desenvolvimento das interfaces, utilizando a biblioteca ReactJS. Minhas 
responsabilidades incluíam a criação e aprimoramento de componentes reutilizáveis, a implementação de lógica de negócios relacionada 
à interface do usuário e a integração com a API back-end.

Utilizei o React Router para a navegação entre diferentes páginas e rotas da aplicação, garantindo uma experiência de usuário fluida 
e intuitiva. Além disso, aproveitei recursos como hooks, que permitiram o gerenciamento eficiente de estado e a execução de efeitos 
colaterais.

Também me utilizei a biblioteca styled-components, pude criar estilos personalizados para cada componente, garantindo uma separação 
clara entre a lógica de apresentação e a lógica de negócios. Em vez de criar arquivos CSS separados, pude definir estilos diretamente 
no código JavaScript dos componentes.

No geral, minha contribuição com o uso da biblioteca ReactJS foi fundamental para o sucesso do projeto, permitindo a criação de 
interfaces modernas, interativas e de alto desempenho.


<details>
    
  <Summary>Contribuições Front-End</Summary>
  
  > No código abaixo, pude contribuir para a criação, estruturação e estilização do componente Header. Esse componente desempenha um papel fundamental 
    ao renderizar o cabeçalho das páginas, fornecendo uma identidade visual consistente e intuitiva para o site. Com minha contribuição, foi possível 
    garantir que o Header seja visualmente atraente, responsivo e facilmente reconhecível pelos usuários, contribuindo para uma experiência de navegação 
    agradável e eficiente.
    
  ```javascript
    function Header() {
        return (
            <>
                <DivFundo>
                    <img src={logo} alt="logo" />
                    <Titulo className="titulo">Dailybot é um robô<br /> programado para estar<br /> constantemente de<br /> olho no <Diario
                        href="http://www.imprensaoficial.com.br/" className="diario"><u style={{ fontFamily: 'Roboto' }}>Diário Oficial</u></Diario>
                    </Titulo>
                </DivFundo>
            </>
        )
    };
    export default Header;
  ```
  <br>
</details>
  
## Aprendizados Efetivos

#### Hard Skills  
Pude neste projeto tive a oportunidade de desenvolver novas habilidades em tecnologias de front-end.

<details>
    <Summary>Ver Hard Skills desenvolvidas</Summary>
    
* ReactJS - Na criação de componentes que compoem as interfaces;

* Styled-Componentes - Na estilização dos componentes;

* ReactRouterDom - Na criação das rotas.
    
</details>

#### Soft Skills 
Pude também estar desenvolvendo e aprimorando algumas softskills sendo elas:

<details>
    <Summary>Ver Soft Skills desenvolvidas</Summary>

* Comunicação: Nas apresentações de sprints;

* Trabalho em equipe: Ao lidar com a metodologia ágil SCRUM, seguindo ritos como: reuniões diárias(Dailys), reuniões de planejamento(Sprint Planning), reuniões de revisão(Sprint Review) e por fim, reuniões de retrospectiva(Sprint Retrospective);

* Autonomia: Sabendo o que devia ser feito e sempre entregando nos prazos corretos.

* Organização: Como master, na organização ritos da metodologia Scrum e no controle de Burndown e Softskills desenvolvidas por cada membro.

* Empatia: Como Scrum Master, foi preciso ser capaz de se colocar no lugar dos membros da equipe, compreender suas necessidades, preocupações e desafios.

* Adaptação: Novamente como Scrum Master fui capaz de me adaptar a diferentes situações e desafios em um ambiente ágil em constante evolução.
    
</details>
<br>

### [API - 3º Semestre](https://github.com/whatscodeg3/API-3DSM)

## Empresa Parceira 
Pro4Tech
<br>

## Resumo do Projeto 
 
Desenvolver um sistema de microsserviços que tem como objetivo oferecer aos funcionários da empresa a capacidade de cadastrar vendas e gerenciar as parcelas a serem pagas pelos clientes. Essa solução permite um controle eficiente e centralizado das transações comerciais, oferecendo recursos para a criação, edição e acompanhamento das vendas, bem como a geração de relatórios completos que facilitam a análise e interpretação das informações. O sistema possibilita o monitoramento das parcelas em aberto, facilitando o acompanhamento e controle das cobranças a serem realizadas. Com os relatórios gerados, a empresa obtém uma visão clara e detalhada das vendas realizadas, incluindo métricas de desempenho, como volume de vendas, inadimplência e outras informações cruciais para a tomada de decisões estratégicas. Em resumo, o sistema de microsserviços proposto simplifica e automatiza o processo de cadastramento de vendas, controle de parcelas e geração de relatórios, otimizando o trabalho dos funcionários e fornecendo uma visão abrangente e precisa das informações comerciais.

## Tecnologias 
* ReactTS
* JavaScript
* TypeScript
* Java
* SpringBoot
* MySQL
* Docker

## Contribuições Pessoais
Neste projeto, como desenvolvedor, novamente fui responsável pelo desenvolvimento do front-end utilizando a biblioteca React. Optei por adotar uma abordagem de arquitetura escalável, utilizando o conceito de Atomic Design. Essa abordagem organiza os componentes em uma hierarquia, começando pelos blocos de construção menores e combinando-os para formar componentes mais complexos.

Ao adotar o Atomic Design, pude dividir os componentes em átomos, moléculas, organismos, templates e páginas. Os átomos são os blocos de construção básicos, como botões, inputs e textos. As moléculas são combinações de átomos, formando componentes mais complexos, como um formulário de cadastro. Os organismos são composições de moléculas e átomos, como um cabeçalho ou um rodapé. Os templates são as estruturas de página reutilizáveis, e as páginas são as instâncias específicas desses templates.

Para a estilização dos componentes, novamente me utilizei a biblioteca styled-components, pude criar estilos personalizados para cada componente, garantindo uma separação 
clara entre a lógica de apresentação e a lógica de negócios. Em vez de criar arquivos CSS separados, pude definir estilos diretamente 
no código JavaScript dos componentes.

Novamente utilizei a biblioteca react-router-dom para a navegação entre diferentes páginas e rotas da aplicação, garantindo uma experiência de usuário fluida 
e intuitiva. Além disso, aproveitei recursos como hooks, que permitiram o gerenciamento eficiente de estado e a execução de efeitos 
colaterais.

Essas escolhas e técnicas adotadas no desenvolvimento do front-end permitiram criar um aplicativo React bem estruturado, escalável e de fácil manutenção. A abordagem do Atomic Design ajudou a organizar os componentes de forma coesa e reutilizável, enquanto o styled-components proporcionou uma estilização eficiente e legível. O react-router-dom, por sua vez, permitiu criar uma experiência de navegação fluída e intuitiva para os usuários.

<details>
    
  <Summary>Contribuições Front-End</Summary>
    
  > Neste codigo por exemplo pude estruturar componente SearchField, que é responsável por renderizar um campo de busca. Ele permite que os usuários digitem um texto para realizar uma pesquisa e dispara um evento de mudança (onChange) quando o conteúdo do campo de busca é alterado.
  
  ```html
    import React, { ChangeEvent } from "react";
    import { Field } from "./defaultStyles";

    interface SearchFieldProps {
      value?: string ;
      onChange: (event: ChangeEvent<HTMLInputElement>) => void;
      placeholder?: string;
    }
    
    const SearchField: React.FC<SearchFieldProps> = (props) => {
      return (
        <div className="mb-3">
          <span className="p-input-icon-left">
            <i className="pi pi-search" />
            <Field
              value={props.value}
              onChange={props.onChange}
              placeholder={props.placeholder}
            />
          </span>
        </div>
      );
    }
    export default SearchField;
  ```
  ...
  <br>
</details>

## Aprendizados Efetivos

#### Hard Skills  
Pude neste projeto tive a oportunidade de desenvolver novas habilidades em tecnologias de front-end.

<details>
    <Summary>Ver Hard Skills desenvolvidas</Summary>
    
* ReactJS - Na criação de componentes que compoem as interfaces;

* Styled-Componentes - Na estilização dos componentes;

* ReactRouterDom - Na criação das rotas;
   
* Atomic Design - Para uma melhor organização dos componentes.
    
</details>

#### Soft Skills 
Pude também estar desenvolvendo e aprimorando algumas softskills sendo elas:

<details>
    <Summary>Ver Soft Skills desenvolvidas</Summary>
    
* Comunicação: Nas apresentações de sprints;
    
* Trabalho em equipe: Ao lidar com a metodologia ágil SCRUM, seguindo ritos como: reuniões diárias(Dailys), reuniões de planejamento(Sprint Planning), reuniões de revisão(Sprint Review) e por fim, reuniões de retrospectiva(Sprint Retrospective);
    
* Autonomia: Sabendo o que devia ser feito e sempre entregando nos prazos corretos;
    
* Entrega de resultados: Sempre fazendo entregas continuas e efetivas.
    
</details>
<br>

<br>
<br>

## Contato 📞

- Telefone: [(12) 99165-7409]
- Email: [romribkevin@gmail.com](#)
- LinkedIn: [Kevin Romero Ribeiro](#)
