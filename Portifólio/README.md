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
  
  ```html
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
  Nesse código por exemplo eu pude contribuir no desenvolvimento de um gráfico utilizando a biblioteca ChartsJS. Escrevi o código 
    necessário para configurar e personalizar o gráfico, incluindo o tipo de gráfico, os datasets e as opções adicionais. Também 
    implementei funcionalidades avançadas, como atualização em tempo real dos dados e interatividade com o usuário.
  <br>
</details>

<details>
    
  <Summary>Contribuições Back-End</Summary>
  
  ```html
     @contacts.route('/historico')
     def historico():
         if g.user != None:
             if g.user[0] == 1 or g.user[0] == 2 or g.user[0] == 3:
                 print(g.id_usuario)
                 lista = Solicita.query.filter_by(fk_id_usuario_comum=g.id_usuario)
                 return render_template('usuario-historico.html', listas=lista, user=session['user'])     
         return redirect(url_for('contacts.index'))
  ```
  Durante o desenvolvimento do projeto, tive a oportunidade de criar rotas utilizando o framework Flask. O código acima é um exemplo 
    de uma rota simples que eu criei com uma funcionalidade específica. Essa rota é responsável por lidar com a verificação do usuário. 
    Primeiramente, é verificado se o usuário está autenticado. Se sim, o código solicita a lista do histórico de solicitações desse 
    usuário, enviando o ID do usuário como parâmetro. Em seguida, a página de histórico é renderizada, exibindo a lista do histórico de 
    solicitações. No caso de o usuário não estar verificado, ele é redirecionado para a página inicial do aplicativo.
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


### Empresa Parceira ###
FATEC Prof. Jessen Vidal (projeto proposto pelos professores da FATEC)
<br>

### Desafio ###

#### Bot ####
Neste projeto...
<br>

### Minhas Contribuições ###
Neste projeto...
<br>

### Tecnologias ###
<br>

### Hard Skills desenvolvidas ###
Neste projeto...
<br>

### [API - 3º Semestre](https://github.com/whatscodeg3/API-3DSM)

### Empresa Parceira ###
FATEC Prof. Jessen Vidal (projeto proposto pelos professores da FATEC)
<br>

### Desafio ###

#### Site para controle de parcelas ####
Neste projeto...
<br>

### Minhas Contribuições ###
Neste projeto...
<br>

### Tecnologias ###
<br>

### Hard Skills desenvolvidas ###
Neste projeto...
<br>

<br>
<br>

## Formações 🎓

### Superior em Desenvolvimento de Software Multiplataforma - FATEC São José dos Campos (2024)

Estou aprendendo...

<br>
<br>

## Contato 📞

- Telefone: [(12) 99165-7409]
- Email: [romribkevin@gmail.com](#)
- LinkedIn: [Kevin Romero Ribeiro](#)
