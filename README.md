# Classe-JavaBean-Banco-de-Dados



A	 seguir,	você	vê	um	exemplo	de	uma	classe	 JavaBean	que	 seria	equivalente	ao	nosso	modelo	de
entidade	do	banco	de	dados:


		package	br.com.caelum.jdbc.modelo;
		public class Contato	{
						private	Long	id;
						private	String	nome;
						private	String	email;
						private	String	endereco;
						private	Calendar	dataNascimento;
				//	métodos	get	e	set	para	id,	nome,	email,	endereço	e	dataNascimento
				public	String	getNome() {
						return this.nome;
				}
				public	void	setNome(String	novo) {
						this.nome	=	novo;
				}
				public	String	getEmail() {
						return this.email;
            public	void	setEmail(String	novo) {
						this.email	=	novo;
				}
				public	String	getEndereco() {
						return this.endereco;
				}
				public	void	setEndereco(String	novo) {
						this.endereco	=	novo;
				}
				public	Long	getId() {
						return this.id;
				}
				public	void	setId(Long	novo) {
						this.id	=	novo;
				}
				public	Calendar	getDataNascimento() {
						return this.dataNascimento;
				}
				public	void	setDataNascimento(Calendar	dataNascimento) {
						this.dataNascimento	=	dataNascimento;
				}
		}
    
A	especificação	JavaBeans	é	muito	grande	e	mais	informações	sobre	essa	vasta	área	que	é	a	base	dos
componentes	escritos	em	Java	pode	ser	encontrada	em:

http://docs.oracle.com/javase/tutorial/javabeans/


OBS: MÉTODOS GETTERS E SETTERS
Um	erro	muito	comum	cometido	pelos	desenvolvedores	Java	é	a	criação	dos	métodos	getters	e
setters	indiscriminadamente,	sem	ter	a	real	necessidade	da	existência	de	tais	métodos.
Existe	 um	 artigo	 no	 blog	 da	 Caelum	 que	 trata	 desse	 assunto:
http://blog.caelum.com.br/2006/09/14/nao-aprender-oo-getters-e-setters/
Os	 cursos	 FJ-11	 e	 FJ-22	também	 mostram	isso	 claramente,	 quando	 criam	 algumas	 entidades
que	não	possuem	apenas	getters	e	setters.
