# Java

<h2>Conta</h2>
package Aula1;

public class Conta {
	private String numConta;
	private String cliente;
	private Double saldo = 0.0; //Se comneçar com letra maiúscula é classe, e se o double minúsculo seria um tipo primitivo(ex:int, double, float)
	// usar a classe ao invés do tipo primitivo torna possível você usar métodos prontos que agiliza sua programação
	
	public Conta(String numConta, String cliente) {
		saldo = 0.0;
		this.numConta = numConta; // this serve para dizer que aquele nome é a variável e não o parâmetro do método
		this.cliente = cliente;
	}
	
	public void depositar(Double valor) {
		saldo += valor;
		System.out.println(consultarSaldo());
	}
	
	public Double consultarSaldo() {
		return saldo;
	}
	
	public void sacar(Double num) {
		if(saldo >= num) {
			saldo -= num;
			System.out.println(saldo); //escreve sysout e aperte ctrl+space
		}else {
			System.out.println("Calma amigo, você não tem tanto saldo para sacar esse valor");
		}
	}
}

<h2>TestarConta</h2>
package Aula1;

public class TestarConta {

	public static void main(String[] args) {
		Conta c1 = new Conta("123.500-0", "Daniel");
		c1.depositar(100.00);
		c1.sacar(50.00);
		c1.sacar(60.00);
	}

}
