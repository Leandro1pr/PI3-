
# Proposta de Tema de PI3
Título: Derretedor de metais uilizando corrente elétrica

Aluno(s): Leandro Romani
Orientador: Saimon

# Objetivo geral
 Desenvolver um circuito para derreter metais utilizando corrente elétrica.

# Objetivos específicos
 - Projetar circuito elevador de corrente utilizando transformador;
 - Dimensionar sensores de corrente e de tensão e implementar um circuito para leitura; 
 - Implementar um circuito de ajuste da corrente;
 - Criar um suporte para colocar a fonte;
 - Desenvolver uma bancada para a realização de testes dos cabos de baixa tensão.

# Metodologia
 O projeto consiste numa fonte de alta corrente de saída, que terá como carga algum artefato metalico. Através de uma corrente elevada, será possivel derreter o objeto metálico devido a sua alta temperatura causada pela passagem da corrente por sua estrutura. Com base nisso o circuito final pode ser separado em blocos pelo qual é definido por suas funções:

- O circuito elevador de corrente;
  - Controle e medição;
  - Suporte de instalação da fonte de corrente e uma bancada de teste.

  Circuito elevador de corrente:

 O circuito elevador de corrente conta com um transformador de microondas e dispositivos de seccionamento e proteção. A escolha do transformador de microondas se dá por dois motivos:
1) Transformadores de microondas tem uma maior potência para a especificação do projeto;
 2) São encontrados em sucatas, o que faz com que diminua o custo para a construção da fonte.
 A ideia é modificar o transformador para que seja possivel obter altas correntes para derreter o objeto.

 Ajuste e medição
 Para controle e medição, a ideia é de utilizar um potenciômetro para o ajuste da corrente no primário do transformador, e sensores de corrente e de tensão nos dois lados do transformador, juntamente com um microcontrolador para fazer a leitura e apresentar num display os valores da corrente e da tensão no primário e secundário.

 Suporte de instalação da fonte de corrente e uma bancada de teste
Pela condição que o circuito tem como objetivo entregar ( alta corrente), para uma maior segurança, o circuito juntamente com sensores e demais dispositivos, ficaram dentro de uma "caixa" para isolar qualquer contato do corpo com o lado de alta corrente do circuito, bem como uma bancada para o teste do cabo de baixa tensão. A intenção é que a fonte de corrente seja portátil para levar a qualquer lugar. Será usado como referência, O vídeo no Youtube do canal Engehall no qual construíram uma fonte de corrente para testes de dispositivos elétricos. 

# Cronograma
> crie um projeto no GitHub discriminando as ações e o período em que as mesmas serão realizadas
> coloque dentro do parênteses abaixo o link para o projeto criado

Clique [aqui](https://github.com/users/sergiopetrovcic/projects/8/views/1?layout=roadmap) para acessar o cronograma.

# Lista de materiais

| Item | Descrição | Unidade | Valor Unitário | Quantidade | Total |
| ---- | ------------- | --- | ------------- | ------------- | ------------- |
|  01  | Eletroduto rígido de 3/4" branco | barra | R$ 30,00 | 1 | R$ 30,00 |
|  02  | Fita isolante | rolo de 5 m | R$ 20,00 | 5 | R$ 100,00 |
|    |  |   |  |  | **R$ 130,00** |

# Unidades curriculares envolvidas

- Circuitos elétricos;
- Microcontroladores;
- Máquinas elétricas;
