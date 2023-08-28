# Bertoti
Pasta "engenharia SW"


Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming is certainly a significant part of software engineering: after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming.

resumo
Engenharia de software se divide em três pilares : tempo, escala e o conflito de escolha.
Cria o software fácil de interagir com tempo útil para não haver gastos desnecessário e melhor performance.
Escala e a distribuição de acesso para muitas pessoas, sendo acessado pelas mesma tendo visibilidade de maior número de pessoas.
Última coisa e trade off e jogo de perde ganha, você acaba ganhando em um ponto e acabar perdendo em outro, para da melhor equilíbrio nesse jogo, ganha no que você pode e perder na menos importante.

Requisitos funcionais são as ações do sistema são espresso como verbos.
Não funcionais, qualidade adjetivo.

2- De 3 exemplo de trade off
vantages e desvantagem do progrmação em java 
JavaScript é empregado em todos os lugares da web.
JavaScript funciona bem com outras linguagens e pode ser utilizado em uma grande variedade de aplicativos.
Existem muitos projetos de código aberto que fornecem uma ajuda útil na adição de JavaScript do desenvolvedor.
Existem muitos cursos disponíveis na área de JavaScript, por isso você expandirá de forma rápida e simples seu conhecimento desta linguagem de programação.
Não é difícil começar a trabalhar em JavaScript. Por isso, muitos de nós preferimos começar sua aventura no setor de TI aprendendo essa língua.

Pode ser difícil desenvolver aplicativos grandes, embora você também use a sobreposição de TypeScript.
Isso se aplica a projetos front-end maiores. A configuração costuma ser uma tarefa tediosa para a quantidade de ferramentas que precisam ser montadas para criar um ambiente para tal projeto. Geralmente, isso está diretamente associado à operação da biblioteca.
O principal problema ou desvantagem em JavaScript é que o código está sempre visível para qualquer pessoa que possa visualizar o código JavaScript.


3- Escolha outro exemplo e faça uma mesma atividade 
exemplo intragram e facebook os dois tem a mais aplicação de fotos uso do intragram usa filtro, usabilidade tambem bem melhor e desempenho, privacidade, enquanto facebook fica atras de algumas funcinalidades.




18/08/2023

// Encontre um erro e um acerto de cada heurística e coloque no seu readme.md do github

##1: Visibilidade do status do sistema
acerto: Entrada do windows
erro: whatsapp(status)
#2: Correspondência entre o sistema e o mundo real
acerto:Metáforas do windows (janela, arq,etc)
erro:SQL exception p/user
#3: Controle e liberdade do usuário
acerto:pacote office(word,excel, etc)
erro:
#4: Consistência e padrões
acerto: whatsapp (conversa, status, chamada)
erro:siga (ver print)
#5: Prevenção de erros
acerto:
erro:
#6: Reconhecimento em vez de recordação
acerto:reconhecer por data ou mes
erro:
#7: Flexibilidade e eficiência de uso
acerto: atalhos
erro:
#8: Design estético e minimalista
acerto:
erro:
#9: Ajude os usuários a reconhecer, diagnosticar e se recuperar de erros
acerto:
erro:
#10: Ajuda e documentação
acerto:
erro:

21/08/2023

4 Fazer o diagrama de (uml) de casos de uso com os requisitos funcionais (ver slida 10)







25/08/2023
slide 23

Diagram de clone UML + JAVA 
nome da clone - sala de aula - lista chamada: LIST<ALUNO> ATRIBUTO O QUE CLONE CONHECE SUBSTATIVO COM A PRIMEIRA LETRA MINUSCULA.
O QUE COLNE FAZ VERBO -BUSCAR ALUNO NOME(STRING NOME):LISTA<ALUNO> + BUSCAR ALUNO RA(INT RA): ALUNO


ALUNO
-NOME:STRING



PUBLIC LIST<ALUNO>BUSCAR ALUNO NOME (STRING NOME){
      LIST ALUNO<ALUNO>encontrados=meu linhed list<ALUNO>()
      FOR(Aluno aluno:lista chamda)}
          if(ALUNO.GITNOME().EQUALS(NOME))ENCONTRADOS.ADD(ALUNO)
          }
          RETURN ENCONTRADOS;






          28/08/2023


Inicie seu diagrama de colnes UML fazendo-o junto com o código java(como fizemos junots em sala e ou no slide 23).

BIBLIOTECA
livros:LIST<LIVRO>
USUARIOS:list<usuario>





public class diagrama_uml {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
      public class Biblioteca{
    	private list<livro>livros=meu linheclist<list>0;
    	private list<usuario>usuarios linkedlist<
    	
    					
      public void add livro(livro livro) {
    		livros.add(livro);
      public void addusuario(usuariousuario) {
    	usuario.add(ususario);
    	
     public list<livrop>buscarlivronome(string nome)	{
    	LIST<livro>enocntrados=meu linkedlist<livro>();
    	for(Livro livro;livros)
    		if(livro.get nome()equals(nome))
    			encontrados.add(livros);
    			
    			return encontrados;
    			
    }
    }
    	}
	  
  }
  
	}

}
Faremos várias versoes desta atividade evoluindo passo a passo coloque cada versão no seu github.

obs
lembrete
1 livro engenhariano google
2 trade-offs
3 requisitos não funcional usabilidade 
4 CASO DE USO uml
5 CLONES UML
6 codigo java
varias vessoes!
incremente melhores aula a aula.




