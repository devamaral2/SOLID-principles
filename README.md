## SOLID- introdução aos principios S e I

<details>

  <summary><strong> O que vamos aprender? </strong></summary><br />
  
> SOLID é um acrônimo utilizado para memorizarmos cinco principios básicos na engenharia de software, eles são amplamente divulgados pelo programador e > escritor Robert C. Martin e tem como objetivo tornar a escrita de códigos com orientação à objetos mais simples, reutilizável, agil e padronizaods.  
  
</details>

<details>
  <summary><strong> Você será capaz de: </strong></summary><br />
  
 > - Aplicar o principio da responsabilidade única(single-responsibility principle). </br>
 > - Aplicar o principio da segregação de interfacer(interface segregation principle).
  
</details>

<details>
  <summary><strong> Porque isso é importante? </strong></summary><br />
  
> A aplicação dos  principios SOLID tornará seu código mais legivel, será mais fácil realizar testes com ele e também ajudará no reaproveitamento e 
> manutenção  do códgo.
  
 ```typescript
public class Student {

     public void registerStudent() {
         // some logic
     }

     public void calculate_Student_Results() {
         // some logic
     }

     public void sendEmail() {
         // some logic
     }

} 
  
 ```
  
</details>

<details>
  <summary><strong> Conteúdos </strong></summary><br />
  
<details>
  <summary> Single responsability principle </summary><br />
 
  O princípio da responsabilidade única talvez seja o princípio menos compreendido dos 5 princípios criados do SOLID, muito provavelmente pelo seu nome inadequado. Quando escutamos o nome princípio da responsabilidade única, tendemos a associar com as ideias sobre a criação de funções que aprendemos também com nosso “uncle bob”(Robert C. Martin) no livro Clean Code. É como se aplicássemos o princípio de que cada função deve realizar apenas uma coisa para classes, orientando para que estas devem ter também apenas uma função.
  Uma classe é uma abstração de algum objeto no mundo real, ela descreve os atributos e ações daquele objeto e se este objeto possui uma série de atributos e ações seu código não se tornará mais legível ou de fácil manutenção apenas porque você dividiu esta classe em subclasses menores. Se por um exemplo você tem a classe Tigre com atributos e as funções andar, correr, comer, beber água e dormir, você precisaria criar arquivos distintos para cada uma destas funções, tornando mais difícil para quem irá realizar a manutenção do código de encontrar todo o código escrito relacionado com a classe Tigre. 

⚠️ATENÇÃO! O SRP, ou princípio da responsabilidade única não é sobre God classes! Muito material na internet cita este princípio como um modo de evitar as chamadas God classes, classes que realizam muitas coisas e que por isso tornam-se mais complexas, mas não é deste modo como Robert C. Martin descreve este princípio no livro Clean Architecture.⚠️ 

  
  > *Um módulo deve ter uma e apenas uma, razão para mudar.*

  
</details>
  
</details>

<details>
  <summary><strong> Vamos praticar! </strong></summary><br />
  
  
</details>

<details>
  <summary><strong> Recursos Adicionais </strong></summary><br />
 
  https://www.youtube.com/watch?v=P9RJs4oatQM - 139 - Entenda o Single Responsibility Principle do SOLID | theWiseDev SOLID
  
</details>

