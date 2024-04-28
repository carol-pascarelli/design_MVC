# Design de Arquitetura do Software


<div align="center">
<img src="/assets/mvc.drawio.png" width="100%" >
</div>


<a href="https://drive.google.com/file/d/1uVv8GAk-ReYaqwbkPWSbP9Dm5yEZhXdO/view?usp=drive_link">link do MVC completo no draw.io</a>

# Especificações 
- Nome do Projeto: Tech Bridge
- Descrição: Este design foi desenvolvido para a visualização de um website para a Faculdade Zuyd para conectar melhor os alunos participando da simulação de negócios Cesim, com o intuito de faze-los entender melhor uns aos outros, seu costumes, frustrações e desenvolvimento no jogo.
- Arquitetura: MVC (Model-View-Controller)
- Ferramenta de Diagramação: draw.io

### Modelos (Models):
&nbsp;&nbsp;&nbsp;&nbsp;Os modelos (models) é a responsável pela lógica de armazenamento e recuperação de infromações. Neste modelo há 5,cada um com seus respectivos atributos. Cada uma destas entidades são agrupamentos de dados com atributos designados apenas a ela. Por exemplo nas entidades tutor e player temos atributos como nome, país de origem, email, senha e times que está participando no jogo. Assim, é possível visualizar como o código deverá ser feito para poder estruturas este website

### Controladores (Controllers):
&nbsp;&nbsp;&nbsp;&nbsp;Os controladores do projeto conectam a visão com o modelo, sendo o que está por trás fazendo este website funcionar. Neste mvc há 5 controladores: player, tutor, feedback, perfil e medidor de felicidade. Todos os controladores devem ser visualizados, por isso há este parâmetro de entrada e saída (das informações inseridas), para que todos os usuários possam consultar na plataforma. Há também parâmetros como gravar a informação de entrada, buscar, e calcular, no caso do medidor de felicidade. Dessa forma, há a entrada da informação inserida pelo usuário, que é gravada e assim poderá ser visualizada no seu perfil.

### Views (Views):
&nbsp;&nbsp;&nbsp;&nbsp; O projeto é contituído por 5 views. Nesta parte está tudo que vai poder ser visualizado pelo usuário, então há uma página de login na qual ele irá preencher com seu email e senha, um questionário para saber mais sobre o seu perfil e personalidade, feedbacks que ele poderá dar para os outros membros de seu grupo, medidor de felicidade no qual ele poderá dizer como está se sentindo e ficará disponível para visualização do resto do grupo também e perfil e avatar no qual ele poderá escolher quais informações estarão em display para os outros membros de sua equipe assim como um avatar editável por ele. 

### Infraestrutura:
&nbsp;&nbsp;&nbsp;&nbsp; O projeto irá contar com um banco de dados para poder armazenar e gerenciar todos os dados do website. Além disso, nos controles serão usados Interfaces de programação (APIs) para processar tudo que está sendo inserido.