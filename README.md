> toda proposta de tema de projeto de PI3 deve seguir o padrão abaixo.

# Proposta de Tema de PI3
Título: Derretedor de metais uilizando corrente elétrica

Aluno(s): Leandro Romani
Orientador: Saimon

# Objetivo geral
> Desenvolver um circuito para derreter metais utilizando corrente elétrica.

# Objetivos específicos
> - Projetar circuito elevador de corrente utilizando transformador;
> - Dimensionar sensores de corrente e de tensão e implementar um circuito para leitura; 
> - Implementar um circuito de ajuste da corrente;
> - Criar um suporte para colocar a fonte;
> - Desenvolver uma bancada para a realização de testes dos cabos de baixa tensão.

# Metodologia
> O projeto consiste numa fonte de alta corrente de saída, que terá como carga cabos de baixa tensão. Para a realização do protótipo este será dividido em blocos para melhor entendimento do projeto, esses blocos são:
 O circuito elevador de corrente;
Controle e medição;
 Suporte de instalação da fonte de corrente e uma bancada de teste.
Circuito elevador de corrente:
O circuito elevador de corrente conta com um transformador de microondas e dispositivos de seccionamento e proteção. A escolha do transformador de microondas se dá por dois motivos:
1) Transformadores de microondas tem uma maior potência para a especificação do projeto;
2) São encontrados em sucatas, o que faz com que diminua o custo para a construção da fonte.
Inicialmente as especificações para a fonte de corrente é 220V na entrada e na saída com uma corrente que estará entre 400 a 500A. Como se pôde ver em (CUNHA, 2019), foi utilizado  para obter uma alta corrente 2 voltas com um cabo de 35mm2. A proteção será feita com um disjuntor que será dimensionado segundo a corrente que estará no primário.
    Ajuste e medição
Para controle e medição, a ideia é de utilizar um potenciômetro para o ajuste da corrente no primário do transformador, e sensores de corrente e de tensão nos dois lados do transformador, juntamente com um microcontrolador para fazer a leitura e apresentar num display os valores da corrente e da tensão no primário e secundário.
   Suporte de instalação da fonte de corrente e uma bancada de teste
Pela condição que o circuito tem como objetivo entregar ( alta corrente), para uma maior segurança, o circuito juntamente com sensores e demais dispositivos, ficaram dentro de uma "caixa" para isolar qualquer contato do corpo com o lado de alta corrente do circuito, bem como uma bancada para o teste do cabo de baixa tensão. A intenção é que a fonte de corrente seja portátil para levar a qualquer lugar. Será usado como referência, O vídeo no Youtube do canal Engehall no qual construíram uma fonte de corrente para testes de dispositivos elétricos. 

# Cronograma
> crie um projeto no GitHub discriminando as ações e o período em que as mesmas serão realizadas
> coloque dentro do parênteses abaixo o link para o projeto criado

Clique [aqui](https://github.com/users/sergiopetrovcic/projects/8/views/1?layout=roadmap) para acessar o cronograma.

# Lista de materiais
> crie uma lista dos materiais que serão necessários para a execução do projeto
> 
> utilize preço médio do mercado mesmo que não seja necessário comprar

| Item | Descrição | Unidade | Valor Unitário | Quantidade | Total |
| ---- | ------------- | --- | ------------- | ------------- | ------------- |
|  01  | Eletroduto rígido de 3/4" branco | barra | R$ 30,00 | 1 | R$ 30,00 |
|  02  | Fita isolante | rolo de 5 m | R$ 20,00 | 5 | R$ 100,00 |
|    |  |   |  |  | **R$ 130,00** |

# Unidades curriculares envolvidas
> liste as unidades curriculares envolvidas com o tema escolhido
- Disciplina 1;
- Disciplina 2;
- Disciplina n.
