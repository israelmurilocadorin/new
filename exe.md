1.Relatório de Histório de Saúde
---

0Fn

	Relato(id, nome, tipo, idade, dono, (data_visita,id_procedimento,procedimento))

1Fn

	Relato( __id__ ), nome, tipo, idade ,dono, (__dataVisita__,__idProcedimento__,procedimento))

2Fn == 3Fn

	Animal(__id__, nome, tipo, idade ,dono)
  
	Consulta(__id__,__dataVisita__,__idProcedimento__)
  
	Procedimento(__idProcedimento__,procedimento)  

Já está na terceira forma normal

2.Ficha de Orçamento
---

0Fn


1Fn

	ficha(Nome_Da_clinica,data,numero_de_Orçamento,nome_Do_medico,endereco,n	ome_Do_animal,procedimento,valorTotal);

2Fn

	consulta(nome_Da_clinica,Numero_de_orçamento,data,valor),

	medico(nome,endereço),

	animal(numero_de_orcamento,nome, procedimento)

3Fn


