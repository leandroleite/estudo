# QUESTAO NUMERO 36

- [Conhecimento](https://github.com/leandroleite/estudo/blob/main/tecnologia-da-informacao/programacao/linguagens-de-programacao/swift/01-basico.md#vari%C3%A1veis-e-contantes)
- [Conhecimento](https://github.com/leandroleite/estudo/blob/main/tecnologia-da-informacao/programacao/linguagens-de-programacao/swift/02-operacoes-basicas.md#operador-de-atribui%C3%A7%C3%A3o)
- [Conhecimento](https://github.com/leandroleite/estudo/blob/main/tecnologia-da-informacao/programacao/linguagens-de-programacao/swift/03-strings-and-characters.md#interpola%C3%A7%C3%A3o-de-string)

Em um programa em Swift, o programador deseja incluir o resultado de uma operação dentro de uma string. Nesse contexto, considere o seguinte código:

~~~swift
let quantidade = 4
let valor = 10
~~~

Dado o código acima, o programador deseja uma string saida cujo valor seja

~~~swift
"valor total = 40"
~~~

Para isso, o programador deve utilizar o seguinte fragmento de código Swift:

- (A) let saida = "valor total = \(quantidade*valor)"
- (B) let saida = "valor total = %[quantidade*valor]"
- (C) let saida := "valor total = \{quantidade*valor}"
- (D) let saida = "valor total = \[quantidade*valor]"
- (E) let saida := "valor total = \(quantidade*valor)"

# QUESTAO NUMERO 37

- [Conhecimento](tecnologia-da-informacao/manipulacao-de-dados/python/biblioteca-numpy/01-array.md)
- [Conhecimento](tecnologia-da-informacao/manipulacao-de-dados/python/biblioteca-scikit-learn/01-linear-regression.md)

Analise o código a seguir, feito em Python com o Scikit-learn.

~~~python
import numpy as np
import sklearn.linear_model as skl
base = np.array([1, 2, 3, 4, 5, 6])
x = base.reshape((-1, 1))
y = base*2+3

# a fazer
print('a', model.coef_[0])
print('b', model.intercept_)
~~~

A partir desse código, um programador quer obter os parâmetros a e b da equação y = ax + b, por meio de uma regressão
linear, usando, para isso, os dados nos vetores x e y definidos no programa.

Qual linha de código deve substituir o comentário # a fazer de modo a realizar essa regressão linear?

- (A) model = skl.LinearRegression([x, y])
- (B) model = skl.LinearRegression(x, y)
- (C) model = skl.lr().fit(x, y)
- (D) model = skl.LinearRegression().fit(x, y)
- (E) model = skl.lr(x, y)

# QUESTAO NUMERO 38

- [Conhecimento](https://github.com/leandroleite/estudo/blob/main/tecnologia-da-informacao/programacao/linguagens-de-programacao/java/01-principios-da-programacao-orientada-a-objetos.md#heran%C3%A7a)

Um programador foi instruído pelo seu gerente a implementar, em Java, uma classe MemoriaCalculoVenda que implementasse a interface MemoriaCalculo, já criada pela organização e que representa as exigências da organização para classes que implementam memórias de cálculo.

Nesse cenário, com que fragmento de código o programador deve começar, de forma correta, a implementação da classe?

- (A) class MemoriaCalculoVenda inherits MemoriaCalculo
- (B) class MemoriaCalculoVenda imports MemoriaCalculo
- (C) class MemoriaCalculoVenda implements MemoriaCalculo
- (D) class MemoriaCalculoVenda uses MemoriaCalculo
- (E) class MemoriaCalculoVenda extends MemoriaCalculo

# QUESTAO NUMERO 39

Analise com atenção o código a seguir, escrito em TypeScript 4.0.

~~~typescript
function segredo(a: number[]) {
     return a.map(x=>x*2);
}

console.log(segredo([1,2,3]));
~~~

O que será exibido no console quando o código acima for executado?

- (A) 6
- (B) [6]
- (C) [2, 4, 6]
- (D) 12
- (E) "Executed JavaScript Failed:"

# QUESTAO NUMERO 40

Uma organização decidiu monitorar a opinião do público sobre ela nas redes sociais. Para isso, processou as mensagens com referências ao seu nome, a fim de possibilitar o uso de uma técnica de processamento de linguagem natural conhecida como análise de sentimentos.

Após transformar cada mensagem em uma string, um dos passos importantes nessa técnica é a tokenização, que consiste em

- (A) eliminar todos os marcadores HTML ou XML da mensagem.
- (B) dividir o texto da mensagem em palavras isoladas.
- (C) colocar todos os verbos da mensagem no infinitivo.
- (D) substituir todos os caracteres acentuados da mensagem por suas versões sem acento.
- (E) colocar todos os caracteres da mensagem em minúsculas.

# QUESTAO NUMERO 41

No processo de aprendizagem de máquina, busca-se identificar padrões compreensíveis em bases de dados. Desse modo, supõe-se a existência de uma hierarquia de três níveis: a base, com os itens elementares, captados e armazenados por recursos de Tecnologia da Informação; o nível intermediário, no qual esses itens são processados, com significados e contextos bem definidos; e o nível mais alto, contendo os padrões ou os conjuntos cuja formulação pode envolver ou relacionar os níveis inferiores.

Os três níveis dessa hierarquia, listados, respectivamente, da base para o nível mais alto, são:

- (A) informação, conhecimento e dado
- (B) dado, informação e conhecimento
- (C) dado, conhecimento e informação
- (D) informação, dado e conhecimento
- (E) conhecimento, informação e dado

# QUESTAO NUMERO 42

Ao fazer a preparação para analisar dados em um banco de dados típico de Big Data, um profissional de TI percebeu que o número de atributos, ou colunas, era muito maior do que poderia processar com a ferramenta de análise disponível, sendo necessário, portanto, utilizar uma técnica de redução de dados para prepará-los para análise.

Uma técnica indicada, nesse caso, é a

- (A) Deduplicação
- (B) Análise de Componentes Principais
- (C) Amostragem Estratificada
- (D) Imputação
- (E) Amostragem Aleatória

# QUESTAO NUMERO 43

Sabendo que existe, na organização em que trabalha, uma base de dados formada por uma grande tabela que contém apenas o id do cliente e colunas do tipo booleano indicando se um cliente possuía ou já tinha possuído cada produto da organização, um funcionário de TI resolveu dividir os clientes em grupos apenas com base nessa informação, utilizando aprendizado de máquina.

Para essa tarefa, o funcionário de TI deve utilizar o aprendizado de máquina 

- (A) por reforço
- (B) por recompensa
- (C) não supervisionado
- (D) supervisionado
- (E) independente

# QUESTAO NUMERO 44

Organizações modernas estão sujeitas a uma grande quantidade de dados, principalmente se tratam com grandes quantidades de clientes. Muitas das demandas de tecnologia de informação a que essas organizações estão submetidas passaram a ser organizadas e tratadas dentro do conceito de Big Data.

Além do grande volume de dados, o Big Data, em sua definição original, considera também a(s) seguinte(s) propriedade(s):

- (A) variedade e velocidade
- (B) velocidade, apenas
- (C) variedade, apenas
- (D) velocidade e falta de qualidade
- (E) falta de qualidade, apenas

# QUESTAO NUMERO 45

Ao programar em Python com Pandas, é possível usar máscaras para selecionar linhas específicas, de acordo com um padrão.

Nesse cenário, analise o seguinte código:

~~~python
import pandas as pd
data = {'x':[1,2,3], 'y':[3, 7, 11], 'z': [False, True, False]}
df = pd.DataFrame(data)
m = df['z'] == False
ef = df[m]
# a fazer
print(ff)
~~~

Ao executar esse código, deseja-se obter a seguinte saída:

  x y
0 1 3
2 3 11

O fragmento de código que deve substituir o comentário # a fazer para obter a saída desejada é

- (A) ff = ef.cols('x','y')
- (B) ff = ef[['x','y']]
- (C) ff = ef[] == 'x' or 'y'
- (D) ff = ef.cols(['x','y'])
- (E) ff = ef['x','y']

# QUESTAO NUMERO 46

O React Native 0.59 introduziu o conceito de Hooks. Entre os Hooks, tem-se o usestate, que permite

- (A) criar uma enumeration que representa estados.
- (B) declarar uma classe que segue o padrão de design state.
- (C) chamar estados específicos do engine React para alterar seu comportamento.
- (D) manter um estado local em uma função de um componente funcional.
- (E) calcular o estado de um CEP ou ZIP de acordo com o Locale.

# QUESTAO NUMERO 47

Um programador recebeu a incumbência de desenvolver uma aplicação móvel segundo a API 30 do Android, correspondente ao Android 11. Seguindo as melhores práticas, cada tela dessa aplicação, incluindo sua funcionalidade, foi construída como um módulo único e autônomo, totalmente independente de outros módulos similares.

Esse módulo único e autônomo é conhecido como

- (A) intent
- (B) fragment
- (C) content provider
- (D) manifest
- (E) activity

# QUESTAO NUMERO 48

Ansible é uma ferramenta configurável por playbooks, escritos em YAML.

Um playbook é composto de

- (A) tasks, que são sequências de plays que, por sua vez, chamam modules.
- (B) tasks, que são sequências de modules que, por sua vez, chamam plays.
- (C) plays, que são sequências de tasks que, por sua vez, chamam modules.
- (D) modules, que são sequências de tasks que, por sua vez, chamam play.
- (E) plays, que são sequências de modules que, por sua vez, chamam tasks.

# QUESTAO NUMERO 49

Durante o desenvolvimento de uma aplicação mobile em Java para Android, um programador detectou a necessidade de alterar o texto de um widget da classe TextView, chamado resultado, para "Sucesso!".

Para realizar essa ação, esse programador deve usar o seguinte fragmento de código:

- (A) resultado.setText("Sucesso!");
- (B) resultado.setValue("Sucesso!");
- (C) resultado := "Sucesso!";
- (D) resultado = TextView.setValue("Sucesso!");
- (E) TextView resultado = "Sucesso!";

# QUESTAO NUMERO 50

Considere uma empresa que possui dados de clientes, todos bem definidos e estruturados (ex: CPF, nome, e-mail, endereço), armazenados em um banco de dados relacional. Uma oportunidade surge para a empresa enriquecer esse banco de dados com dados de outra natureza, porém não muito bem definidos e pouco estruturados.

Uma solução pode ser adotar um banco de dados NoSQL, de tal forma que:

- (A) o gerenciador de banco de dados relacional utilizado possa ser atualizado para uma versão mais recente, que não utilize a linguagem SQL.
- (B) esse novo banco de dados relacional possa ser melhorado, com os dados não muito bem definidos, sem um esquema rígido.
- (C) a linguagem SQL utilizada para acesso aos dados dos clientes possa ser substituída por outra linguagem de acesso a dados organizados em tabelas segundo o modelo relacional, porém com maior eficiência.
- (D) os atributos que hoje representam chaves primárias e estrangeiras sejam mais bem controlados.
- (E) a ausência de um esquema de dados bem definido para os dados necessários de um cliente possa ser corretamente modelada e implementada em um gerenciador de banco de dados adequado.

# QUESTAO NUMERO 51

Kotlin é uma linguagem de programação usada no desenvolvimento Android.

Entre suas características, está um grau de compatibilidade com Java, que permite

- (A) ter suas funções chamadas por Java, apenas, mas não consegue chamar funções feitas em Java.
- (B) ler e escrever dados que podem ser lidos e escritos por apps Java, apenas.
- (C) ler dados que foram salvos por apps Java, apenas.
- (D) construir apps com código parcialmente em Java e parcialmente em Kotlin, sem restrições.
- (E) chamar funções feitas em Java, apenas, mas não permite que suas funções Kotlin sejam chamadas por Java.

# QUESTAO NUMERO 52

A seguir, é apresentado um fragmento de código em Python.

import numpy as np
b = np.array([[1,2,3,5]]) c = b.transpose()
print(b.dot- (C),sum- (B),sum- (C))

O fragmento de código acima provoca a seguinte saída:

- (A) [[39]] [11] [11]
- (B) [39] [1 2 3 5] 11
- (C) 39 [1 2 3 5] 11
- (D) [[39]] [1 2 3 5] [11]
- (E) 39 [11] [11]

# QUESTAO NUMERO 53

Uma empresa de investimentos financeiros busca identificar novas oportunidades de negócio para pessoas jurídicas, em especial dentre aquelas que têm como característica a adoção de governança ambiental, social e corporativa (conhecida como ESG, uma sigla em inglês). Considere que existe um banco de dados nessa empresa com as seguintes tabelas (todas as chaves primárias são numéricas):

Empresa (CNPJ, razaoSocial, endereco) Caracteristica (cod, sigla, nome)
Tem (CNPJ, cod)

Que comando SELECT do SQL retorna apenas o CNPJ e a razão social das empresas que não têm "ESG" como característica?

## A

SELECT E.CNPJ, E.razaoSocial FROM Empresa E
WHERE E.CNPJ NOT IN ( SELECT T.CNPJ FROM Tem T
JOIN Caracteristica C ON (T.cod = C.cod) WHERE C.sigla = 'ESG'
)

## B

SELECT E.CNPJ, E.razaoSocial FROM Empresa E
JOIN Tem T ON (E.CNPJ = T.CNPJ)
JOIN Caracteristica C ON (C.cod = T.cod) WHERE C.nome <> 'ESG'

## C

SELECT E.CNPJ, E.razaoSocial FROM Empresa E
JOIN Tem T ON (E.CNPJ = T.CNPJ) WHERE Tem.cod = 'ESG'

## D

SELECT Empresa.* FROM Empresa, Tem
WHERE Empresa.CNPJ = Tem.cod AND Tem.cod <> 'ESG'

## E

SELECT *
FROM Empresa
WHERE Caracteristica.Sigla <> ' ESG '

# QUESTAO NUMERO 54

Um banco de dados (BD) persiste dados de forma organizada e controlada. Em adição, um BD deve prover recursos para permitir que consultas que necessitem de velocidade (baixo tempo de resposta) no acesso aos dados possam ter um bom desempenho.

Um dos recursos que um profissional de tecnologia da informação tem à disposição para configurar um BD, de modo a melhorar o desempenho de consultas selecionadas, é a criação de

- (A) sequências
- (B) índices
- (C) visões não materializadas
- (D) gatilhos
- (E) regras de integridade

# QUESTAO NUMERO 55

O banco de dados de uma empresa que comercializa seguros pessoais possui as seguintes tabelas:

Pessoa (email, nome, unidadeFederativaNascimento, faixaEtaria) UF (sigla, nome)

Faixa (nome, menorIdade, maiorIdade)

A coluna "unidadeFederativaNascimento" da tabela Pessoa é uma chave estrangeira que referencia a coluna "sigla" da tabela UF; a coluna "faixaEtaria" da tabela Pessoa é uma chave estrangeira que aponta para a coluna "nome" da tabela Faixa.

A tabela Faixa possui os seguintes dados:

nome	menorIdade	maiorIdade
Jovens	não informada -	19
Adultos	20	59
Idosos	60	não informada -

Considere o seguinte comando:

SELECT COUNT(*)
FROM Pessoa P, Faixa F
WHERE P.faixaEtaria = F.nome
AND P.unidadeFederativaNascimento = 'RJ' AND F.maiorIdade <= 19

Esse comando SQL

- (A) realiza uma operação equivalente à união de dois outros comandos SQL.
- (B) agrupa pessoas por faixa etária e mostra quantos são os grupos com pessoas nascidas no Rio de Janeiro.
- (C) apresenta o nome e o email de jovens nascidos no Rio de Janeiro.
- (D) agrupa pessoas por UF e mostra quantos são os grupos com jovens.
- (E) apresenta quantas são as pessoas que estão na tabela Pessoa, que são jovens e que nasceram no estado do Rio de Janeiro.

# QUESTAO NUMERO 56

Um Sistema Gerenciador de Banco de Dados (SGBD) é um software bastante utilizado em empresas que precisam armazenar, tratar e utilizar dados em geral. O SGBD é especializado em realizar atividades relacionadas aos dados.

Uma das várias funcionalidades que um SGBD pode executar é

- (A) garantir a sequência de execução de programas, em especial quando há dependências de dados entre eles.
- (B) estimular os gestores de uma empresa a compartilhar dados em benefício de todos.
- (C) controlar que usuários podem ter acesso a que dados.
- (D) identificar que dados importantes ao processo decisório de uma empresa estão ausentes e deveriam ser coletados.
- (E) alertar os administradores da infraestrutura de TI de uma empresa quando há vírus circulando na rede.

# QUESTAO NUMERO 57

O banco de dados de uma empresa de investimentos financeiros possui as seguintes tabelas:

Empresa (CNPJ, razaoSocial, endereco) UF (sigla, nome)

O que o comando SQL "SELECT CNPJ, sigla FROM Empresa, UF" recupera desse banco de dados?

- (A) Pares de CNPJ e sigla de todas as empresas cadastradas com as UFs de suas respectivas sedes.
- (B) O CNPJ das empresas cadastradas cuja sigla de UF esteja na tabela UF.
- (C) Alguns pares de CNPJ e sigla, onde o nome da UF é igual à razão social da empresa.
- (D) Todos os pares de CNPJ e sigla possíveis, de todas as empresas e de todas as UFs cadastradas.
- (E) A sigla da UF das sedes das empresas cadastradas.

# QUESTAO NUMERO 58

A CNAE (Classificação Nacional de Atividades Econômicas), de responsabilidade do IBGE, possui códigos que são utilizados para caracterizar as atividades econômicas das empresas no Brasil. Por exemplo: empresas da área de construção de edifícios utilizam o CNAE de código 4120-4/00 para caracterizar a sua atividade econômica principal. Considere que existe um banco de dados em uma empresa, que concede empréstimos a outras empresas, com as seguintes tabelas:

Empresa (CNPJ, razaoSocial, endereco, atividade) CNAE (codigo, descricao)

A coluna "atividade" da tabela Empresa é uma chave estrangeira que referencia a coluna "codigo" da tabela CNAE.
Que comando SELECT do SQL retorna apenas o CNPJ e a razão social das empresas cuja atividade econômica principal
é a construção de edifícios (código 4120-4/00)?
## A

SELECT CNPJ, razaoSocial FROM Empresa E, CNAE C WHERE E.atividade = C.codigo
AND C.codigo = 'construção de edifícios'

## B

SELECT CNPJ, razaoSocial FROM CNAE
WHERE codigo = '4120-4/00'

## C

SELECT * FROM Empresa
WHERE atividade = 'construção de edifícios'

## D

SELECT CNPJ, razaoSocial FROM Empresa
WHERE atividade = '4120-4/00'

## E

SELECT *
FROM Empresa E, CNAE C
WHERE E.atividade = C.codigo

# QUESTAO NUMERO 59

O código abaixo está em linguagem TypeScrip, cuja tipagem é estática.

let fraseLegal = 'Bom dia!';
fraseLegal = 9.5;

Analisando o código apresentado, tem-se que a TypeScrip
- (A) realiza a inferência de tipo, por isso, não aceita a atribuição do tipo number para um tipo string, o que vai gerar um erro de compilação do código apresentado.
- (B) realiza a inferência de tipo, por isso, aceita a atribuição do tipo number para um tipo string sem gerar erro de compilação do código apresentado.
- (C) realiza a inferência de tipo, por isso, o código apresentado vai rodar sem erro.
- (D) não diferencia valores ponto flutuante (decimal) de valores inteiros, por isso, o código apresentado vai rodar sem erro.
- (E) não realiza a inferência de tipo, por isso, o código apresentado vai rodar sem erro.

# QUESTAO NUMERO 60

Considere um cenário no qual uma empresa de investimentos financeiros tenha realizado uma campanha para que seus colaboradores indicassem outras pessoas que pudessem vir a estar interessadas em seus produtos e serviços. Esses colaboradores também foram estimulados a informar a sua ligação com as pessoas indicadas (ex: amigo, irmão, primo) e as eventuais ligações entre as pessoas indicadas. Estes relacionamentos são importantes para a definição da próxima campanha dessa empresa.

O banco de dados NoSQL mais indicado para representar esses dados é o que utiliza o modelo

- (A) orientado a grafos
- (B) orientado a documentos
- (C) orientado a colunas
- (D) relacional
- (E) chave/valor

# QUESTAO NUMERO 61

Um profissional de TI está trabalhando com um grande banco de dados (Big Data), realizando uma análise prévia da base de dados, com o objetivo de identificar anomalias ou resultados raros, de forma a tratá-los ou descartá-los para utilização.
Esse profissional está realizando a seguinte tarefa:

- (A) Análise de outliers (pontos fora da curva) ou detecção de desvios
- (B) Análise de segmentação dos dados
- (C) Análise de associações dos dados
- (D) Classificação dos dados e das anomalias
- (E) Agrupamento dos dados

# QUESTAO NUMERO 62

Para entender como o algoritmo de busca binária se comporta, um estudante de computação resolveu inserir um comando System.out.printf() em um método chamado busca. Esse método, escrito em Java, realiza uma busca binária em um array de números inteiros, ordenados de forma ascendente. O objetivo do printf é exibir, no console, o valor de cada elemento do array visitado pelo algoritmo de busca binária.

Para testar o código que criou, o estudante escreveu o método main a seguir.

public class Main {

public static void main(String[] args) {
int lista[]={5,18,27,33,44,49,54,67,69,72,79,86,87,92};

// o array lista possui 14 elementos

busca(78, lista);
}

public static int busca(int val,int lista[]) {

// código relativo ao algoritmo de busca binária
}
}

O que será exibido no console quando o método main for executado?

- (A) 67 86 72 79
- (B) 54 86 69 72 79
- (C) 49 72 86 79
- (D) 54 79 67 69 72
- (E) 54 79 69 72

# QUESTAO NUMERO 63

Em uma base de dados (dataset) com avaliações sobre a qualidade de um determinado produto, o campo stars tem um valor de 1 a 5. Na fase de pré-processamento, decidiu-se criar o campo sentimento com valores bom ou ruim, e utilizando-se da biblioteca NumPy, escreveu-se o comando abaixo:

dataset['sentimento'] = np.where(dataset['stars'] >= 4, 'bom', 'ruim') Quanto aos valores do campo sentimento, o referido comando atribuirá o valor

- (A) ruim, para stars 4 e 5
- (B) bom, para stars 3 e 4
- (C) bom, para stars 4 e 5
- (D) ruim, para stars entre 1 e 4
- (E) bom, para stars entre 2 e 5

# QUESTAO NUMERO 64

Sejam as seguintes classes Java, que ocupam arquivos separados:

public class CAx {
protected int a; protected int b;

public CAx() {
a*=2; b*=3;
}

{
a=1; b=2;
}

public int op1(int x) { return op2(x)+op3(x)+b;
}

public int op2(int x) { return x+a;
}

public static int op3(int x) { return x*2;
}
}

public class CBy extends CAx { protected int a;

public CBy() {
a+=3; b+=3;
}

public int op2(int x) { return x-a;
}

public static int op3(int x) { return x*3;
}
}

public class Main {
public static void main(String[] args) { CAx o=new CBy();

System.out.println(o.op1(2));
}
}

O que será exibido no console quando o método main for executado?
- (A) 18
- (B) 14
- (C) 12
- (D) 20
- (E) 10

# QUESTAO NUMERO 65

Considere as seguintes classes Java, que ocupam arquivos separados:

public class Pa {
String x,y,z;
String r="vazio";

public Pa(String s1,String s2, String s3) throws Exception { x=s1;
y=s2; z=s3;

try {
if(x==null || y==null || z==null) throw new Exception();
}
catch(Exception e) { z="a";
throw e;
}
finally {
if(x==null)
x="***"; if(y==null)
y="***";
if(z==null)
z="***";
}
}

public String get() { return r;
}
}

public class Qb extends Pa {

public Qb(String s1,String s2, String s3) throws Exception { super(s1,s2,s3);
r=x+y+z;
}
}

public class Main {

public static void main(String[] args) { Pa o=null;

try {
o=new Qb("a"," ","c");
}
catch (Exception e) { System.out.print("***Erro***");
}
finally {
if(o!=null)
System.out.print(o.get());
}
}
}

O que será exibido no console quando o método main for executado?

- (A) ***Erro***
- (B) a***c
- (C) a***a
- (D) vazio
- (E) ac

# QUESTAO NUMERO 66

A Figura a seguir exibe o conteúdo de três pilhas: P1, P2 e P3.

Admita que um método Java, chamado exibePilha, receba essas três pilhas como parâmetros e execute os seguintes passos:

1. Cria duas pilhas auxiliares, A1 e A2, inicialmente vazias;

2. Remove um elemento de P1 e o insere em A1. Em seguida, remove um elemento de P2 e o insere em A1. Repete esses dois procedimentos até que P1 e P2 fiquem, ambas, vazias;

3. Remove um elemento de P3 e o insere em A1. Repete esse procedimento até que P3 fique vazia;

4. Remove um elemento de A1 e o insere em A2. Repete esse procedimento até que A1 fique vazia;

5. Remove um elemento de A2 e o exibe no console. Repete esse procedimento 4 vezes.

O que será exibido no console, quando o método exibePilha for executado, tendo P1, P2 e P3 sido passadas como
parâmetros?

- (A) 20 35 34 40
- (B) 15 10 28 25
- (C) 10 25 30 40
- (D) 40 34 30 60
- (E) 10 15 25 28

# QUESTAO NUMERO 67

Um estudante de computação decidiu escrever um método Java para exibir, no console, em pré-ordem, os valores dos nós de uma árvore binária recebida como parâmetro. Ao executar esse método, os seguintes valores foram exibidos no console:

80 84 55 76 72

Considerando os valores exibidos, qual árvore foi recebida como parâmetro?

- (A) -
- (B) -
- (C) -
- (D) -
- (E) -

# QUESTAO NUMERO 68

A Figura abaixo exibe um diagrama E-R que contém duas entidades (ET1 e XT2) e uma relação (S).


Admita a existência de um banco de dados relacional composto pelos conjuntos ET1 e XT2, oriundos do mapeamento das entidades ET1 e XT2. Parte do estado atual desse banco de dados é definido pelos seguintes conjuntos:

ET1={e1,e2,e4} XT2={t1,t2,t3}

Qual conjunto completa o banco de dados em questão, de modo a atender a todas as regras relativas à relação S?

- (A) S={ (e1,t1), (e1,t2), (e4,t3), (e4,t2) }
- (B) S={ (e1,t1), (e2,t2), (e4,t1) }
- (C) S={ (e1,t1), (e2,t2), (e2,t3) }
- (D) S={ (e1,t3), (e2,t2), (e4,t1) }
- (E) S={ }

# QUESTAO NUMERO 69

Considere o seguinte diagrama E-R:

Foi criado um conjunto de tabelas relacionais, a partir do modelo E-R acima. Uma vez que as regras de transformações de entidades e relações para tabelas relacionais independem dos tipos de dados dos atributos, todos os atributos do modelo E-R acima foram tratados como itens de dados do tipo cadeia de caracteres (TEXT).

As tabelas resultantes são as seguintes: CREATE TABLE TX (
X1	TEXT	NOT NULL,
X2	TEXT	NOT NULL,
X3	TEXT	NOT NULL, PRIMARY KEY (X1));

CREATE TABLE EY (
Y1	TEXT	NOT NULL,
Y2	TEXT	NOT NULL, PRIMARY KEY (Y1));


Qual transformação da relação Rel irá preservar a semântica do diagrama E-R apresentado?

## A

CREATE TABLE REL (
X1	TEXT	NOT NULL,
Y1	TEXT	NOT NULL,
R1	TEXT	NOT NULL,
R2	TEXT	NOT NULL, PRIMARY KEY (X1, Y1, R1),
FOREIGN KEY (X1)
REFERENCES TX (X1), FOREIGN KEY (Y1)
REFERENCES EY (Y1));

## B

CREATE TABLE REL (
X1	TEXT	NOT NULL,
Y1	TEXT	NOT NULL,
R1	TEXT	NOT NULL,
R2	TEXT	NOT NULL, PRIMARY KEY (Y1, R1),
FOREIGN KEY (X1)
REFERENCES TX (X1), FOREIGN KEY (Y1)
REFERENCES EY (Y1));

## C

CREATE TABLE REL (
X1	TEXT	NOT NULL,
Y1	TEXT	NOT NULL,
R1	TEXT	NOT NULL,
R2	TEXT	NOT NULL, PRIMARY KEY (X1, R1),
FOREIGN KEY (X1)
REFERENCES TX (X1), FOREIGN KEY (Y1)
REFERENCES EY (Y1));

## D

CREATE TABLE REL (
X1	TEXT	NOT NULL,
Y1	TEXT	NOT NULL,
R1	TEXT	NOT NULL,
R2	TEXT	NOT NULL, PRIMARY KEY (R1),
FOREIGN KEY (X1)
REFERENCES TX (X1), FOREIGN KEY (Y1)
REFERENCES EY (Y1));

## E

CREATE TABLE REL (
X1	TEXT	NOT NULL,
Y1	TEXT	NOT NULL,
R1	TEXT	NOT NULL,
R2	TEXT	NOT NULL, PRIMARY KEY (X1, Y1),
FOREIGN KEY (X1)
REFERENCES TX (X1), FOREIGN KEY (Y1)
REFERENCES EY (Y1));

# QUESTAO NUMERO 70

Um método Java, chamado converte, deve receber uma string (str) como parâmetro e retornar uma string igual a str, exceto pelas letras minúsculas, que devem ser convertidas em letras maiúsculas.

Exemplo:

String recebida: "Abc $12d" String retornada: "ABC $12D"

Qual método realiza essa tarefa?

## A

public static String converte(String str) { String r=" ";

for(char x : str)
if(Character.isLowerCase(x)) r=r.concat(Character.toString(Character.toUpperCase(x)));
else
r=r.concat(Character.toString(x));

return r;
}

## B

public static String converte(String str) { String r=null;
int i=0;

while(i < str.length()) { if(str[i].isLowerCase(x))
r=r.concat(Character.toString(Character.toUpperCase(str[i])));

else

i++;
}


r=r.concat(Character.toString(str[i]));

return r;
}

## C

public static String converte(String str) { String r=null;
int i=0;

while(i < str.length()) { char x=str.charAt(i);
if(Character.isLowerCase(x)) r=r.concat(Character.toString(Character.toUpperCase(x)));

else

i++;
}

r=r.concat(Character.toString(x));

return r;
}

## D

public static String converte(String str) { String r=" ";

for(int i=0; i < str.length(); i++) if(Character.isLowerCase(str.charAt(i)))
r=r+Character.toUpperCase(str.charAt(i));
else
r=r+str.charAt(i);

return r;
}

## E

public static String converte(String str) { String r=" ";
int i=0;

do {

char x=str.charAt(i); if(Character.isLowerCase(x))
r=r.concat(Character.toString(Character.toUpperCase(x)));

else

i++;

r=r.concat(Character.toString(x));

} while(i < str.length()); return r;
}
