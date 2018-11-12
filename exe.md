1.Relatório de Histório de Saúde
---

0Fn

	Relato(id, nome, tipo, idade, dono, (data_visita,id_procedimento,procedimento))

1Fn

	Relato(_id_, nome, tipo, idade ,dono, (_data_visita_,_id_procedimento_,procedimento))

2Fn == 3Fn

	Animal(_id_, nome, tipo, idade ,dono)
  
	Consulta(_id_,_data_visita_,_id_procedimento_)
  
	Procedimento(_id_procedimento_,procedimento)  

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


