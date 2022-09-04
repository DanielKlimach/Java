<h1>Princípios da Orientação a Objetos</h1>
<ul>
	<li><h2>Classes</h2></li>
		<p>
			Através da definição de uma classe, descreve-se que propriedades — ou atributos — o objeto terá.
			A Classe é todo o conglomerado de objetos que exercem determinada função od projeto
			(que é justamente uma classe ou um conjunto de classes.<br>
			O nome da classe é um identificador para a classe, que permite referenciá-la posteriormente —
			por exemplo, no momento da criação de um objeto.
		</p>
		<p>
			O conjunto de atributos descreve as propriedades da classe. Cada atributo é identificado por
			um nome e tem um tipo associado.
		</p>
		<p>
			Os métodos definem as funcionalidades da classe, ou seja, o que será possível fazer com objetos
			dessa classe. Cada método é especificado por uma assinatura, composta por um identificador para
			o método (o nome do método), o tipo para o valor de retorno e sua lista de argumentos, sendo cada
			argumento identificado por seu tipo e nome.
		</p>
		<p>
			Através do mecanismo de sobrecarga (overloading), dois métodos de uma classe podem ter o
			mesmo nome, desde que suas assinaturas sejam diferentes.
		</p>
		<p>
			O modificador de visibilidade pode estar presente tanto para atributos como para métodos. Em
			princípio, três categorias de visibilidade podem ser definidas:<br>
			<b>+público:</b> Denotado em UML pelo símbolo + nesse caso, o atributo ou método de um objeto dessa
			classe pode ser acessado por qualquer outro objeto (visibilidade externa total);<br>
			<b>-privativo:</b> Denotado em UML pelo símbolo - nesse caso, o atributo ou método de um objeto dessa
			classe não pode ser acessado por nenhum outro objeto (nenhuma visibilidade externa);<br>
			<b>#protegido:</b> Denotado em UML pelo símbolo # nesse caso, o atributo ou método de um objeto dessa
			classe poderá ser acessado apenas por objetos de classes que sejam derivadas dessa através do
			mecanismo de herança.
		</p>
	<li><h2>Objetos</h2></li>
		<p>
			Objetos são instâncias de classes. É através deles que (praticamente) todo o processamento ocorre
			em sistemas implementados com linguagens de programação orientadas a objetos
		</p>
		<p>
			No paradigma de orientação a objetos, tudo pode ser potencialmente representado como um
			objeto. Sob o ponto de vista da programação orientada a objetos, um objeto não é muito diferente de
			uma variável normal.	
		</p>
		<p>
			quando se cria um objeto, esse objeto adquire um espaço em memória para
			armazenar seu estado (os valores de seu conjunto de atributos, definidos pela classe) e um conjunto
			de operações que podem ser aplicadas ao objeto (o conjunto de métodos definidos pela classe).
		</p>
		<p>
			<b>Encapsulação</b> é o princípio de projeto pelo qual cada componente de um programa deve agregar
			toda a informação relevante para sua manipulação como uma unidade (uma cápsula).
		</p>
	<li><h2>Herança</h2></li>
		<p>
			Herança é um mecanismo que permite que características comuns a diversas classes sejam fatoradas em uma classe base,
			ou superclasse.Há várias formas de relacionamentos em herança:<br>
			<b>Extensão:</b> a subclasse estende a superclasse, acrescentando novos membros (atributos e/ou métodos).
			A superclasse permanece inalterada, motivo pelo qual este tipo de relacionamento é
			normalmente referenciado como herança estrita.<br>
			<b>Especificação:</b> a superclasse especifica o que uma subclasse deve oferecer, mas não implementa nenhuma funcionalidade. Diz-se que apenas a 			interface (conjunto de especificação dos métodos públicos) da superclasse é herdada pela subclasse.<br>
			<b>Combinação de extensão e especificação:</b> a subclasse herda a interface e uma implementação padrão de (pelo menos alguns de) métodos da 				superclasse. A subclasse pode então redefinir métodos para especializar o comportamento em relação ao que é oferecido pela superclasse,
			ou ter que oferecer alguma implementação para métodos que a superclasse tenha declarado mas não implementado. Normalmente, este tipo de 			relacionamento é denominado herança polimórfica.
		</p>
	<li><h2>Polimorfismo</h2></li>
		<p>
			duas ou mais classes derivadas de uma mesma superclasse podem invocar métodos que têm a mesma identificação (assinatura)
			mas comportamentos distintos.
		</p>
</ul>
