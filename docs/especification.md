# Especificações do Projeto

O projeto Bookbox será executado seguindo os critérios mencionados abaixo. Utlização da técnica SCRUM para agilizar sua produção e com pequenos ciclos de trabalho. A partir das personas e histórias de usuários, obtivemos os dados necessários para montarmos os requisitos e restrições do projeto, dando continuidade para o próximo passo, a codificação.

SCRUM PLANNING 
1 - Ideia
2 - Personas
3 - Histórias de usuários
4 - Selecionar o escopo do projeto
5 - Revisar
6 - Levantamento de requisitos e restrições
7 - Iniciar codificação

## Personas

Daniel José, tem 31 anos, é casado e possui 3 filhos e formou-se em odontologia pela UFMG em 2013. Apaixonado por Dentística, durante sua graduação adquiriu diversos livros didáticos para seus estudos. Após concluir seus estudos, aquele material ficou sem uso e atualmente ele está buscando uma maneira de vender seus livros para ajudar novos estudantes, por isso o mesmo está em busca de um site que o ajude a comercializar essas obras.

Maria Auxiliadora tem 67 anos, é aposentada e seu hobby é ler livros literários. Pensa em uma forma de divulgar seu arquivo de livros físicos para pessoas leitoras próximas ou de outras regiões, pois Maria sonha em divulgar seu rico material e em poder incentivar outras pessoas a desenvolver o gosto pela leitura. Está à procura de uma plataforma que a ajude a realizar este sonho.  

Beatriz tem 42 anos, casada, possui 2 filhos e se formou em pediatria. Durante a pandemia de 2020 começou a ler livros arduamente para passar o tempo e acabou gostando desse novo hobby e acabou comprando muitos livros. Muitos livros já foram lidos, com isso ela ficou sem espaço na estante e não consegue comprar mais. Agora está em busca de pessoas que possam comprar esse livros para abrir mais espaço e eventualemente conseguir um retorno do que foi gasto anteriormente.

Lucas Ferrari tem 27 anos e é um aficcionado por livros. Não se adaptou aos formatos digitais como os Ebooks, ele costuma procurar reviews em sites especializados como o Skoob, porém, se viu limitado em não poder trocar com outros usuários os títulos que não queira mais em sua estante. Ele procura um site onde possa além de deixar salvo virtualmente sua biblioteca de livros físicos, uma ferramenta eficiente e confiável de trocas e vendas visto que ele mora em uma pequena cidade do interior e precisaria usar os correios como método de entrega. Através do Bookbox Lucas poderá utilizar uma ferramenta confiável de rastreio e o recurso de localização verificando quais os usuários mais próximos a ele para uma eventual troca presencial.

Miguel Alves tem 16 anos e gosta muito de ler. Ele não possui acesso a livros de qualidade na sua cidade por ser uma cidade do interior e buscar uma forma de ter acesso a livros baratos e de qualidade de forma digital e física. Dessa forma a Bookbox pode ajudar ele a encontrar alguém na cidade ou disponibilar ebooks com um preços mais acessíveis.

## Histórias de Usuários
"Como formado, quero vender meus livros adquiridos para os estudos durante minha formação, com o intuito de que novos estudantes tenham acesso à esses matérias de excelente qualidade por um preço justo." 

"Como leitora, quero divulgar minha biblioteca de livros usados para incentivar a leitura e a apreciação pelos livros."

"Acabei me apaixonando pela leitura e estou procurando mais livros para comprar, mas infelizmente estou sem espaço para guardá-los e preciso vender os meus antigos."

"Gostaria de uma plataforma onde pudesse trocar meus livros com segurança, e quem sabe conhecer outros leitores com gostos parecidos com o meu".

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário             | Vender livros de estudo.           | Para ajudar outros estudantes          |
|Usuário             | Divulgar sua biblioteca de livros  | Para incentivar outras pessoas a ler   |
|Usuário             | Vender livros de literatura        | Para desocupar espaço em sua estante   |
|Usuário             | Trocar livros de literatura        | Para renovar sua coleção de exemplares |
|Usuário             | Achar leitores próximos            | Para adquirir livros mais acessíveis   |
|Moderador           | Fiscalizar anúncios e conversas    | Procurar possíveis fraudes e golpes    |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| Permitir que o usuário venda livros          | ALTA  | |
|RF-002| Permitir que o usuário compre livros         | ALTA  | |
|RF-003| Registrar compras e vendas de livros         | MÉDIA | |
|RF-004| Cadastro de usuários                         | ALTA  | |
|RF-005| Cadastro de exemplares de cada usuário       | MÉDIA | |
|RF-006| Plataforma de chat entre usuários            | MÉDIA | |
|RF-007| Permitir recurso de localização do usuário   | MÉDIA | |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos telas menores | MÉDIA |
|RNF-002| Exibir o histórico de compras e vendas ao usuário                         | MÉDIA | 
|RNF-003| Deve processar requisições do usuário em no máximo 3s                     | BAIXA | 
|RNF-004| Autenticação de direitos autorais caso o livro seja autoral               | MÉDIA | 
|RNF-005| Projeto dentro das leis de LGPD                                           | ALTA  | 
|RNF-006| Notificações por e-mail para vendas de livros e confirmações de compra    | MÉDIA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| Tempo curto para o desenvolvimento do projeto         |
|04| Não teremos estoque de livros                         |

