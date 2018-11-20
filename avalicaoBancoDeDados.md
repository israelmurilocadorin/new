Execício de Banco de dados sobre normalização
===

[Lista](//github.com/Dayanfreitas/new/blob/master/documentos/Prova_BD_I_MER_e_Normalizacao.pdf) 
---

1. A) - B
   
   B) - C

2. D

3. D

4. B 

5. D 
 
6. A) - 3FN --> Pois não há atributos multi valorados, os atributos depende totalmente da chave. 
   
   B) - Não --> Não pois para calcular depende de dois atributos 

7. A) -

	1FN

Projeto(__CodProjeto__,descricao ,tipo ,__codEmpregado__ ,nome ,catEmpregado ,salario ,dataInicio ,tempoAlocado);
	
	2FN
	
Projeto( __CodProjeto__, descricao ,tipo);

Empregado(__codEmpregado__, nome,catFuncional,salario);

Alocado(__CodProjeto__,__codEmpregado__,dataInicio,tempAlocado);
	
	3FN

Empregado(__codEmpregado__,nome,catFuncional);

Funcao(__catFuncional__,salario);

   B) -
   []()
