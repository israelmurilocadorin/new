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

![GitHub Logo](/ajudaIsrael/image.png)

2.Ficha de Orçamento
---

0Fn
	
	Orcamento(NumeroOrcamento ,Cliente,DataOrcamento ,Endereco ,(NomeDoAnimal,Procedimento,Valor)

1Fn

	Orcamento(__NumeroOrcamento__ ,Cliente ,Endereco ,DataOrcamento , __NomeDoAnimal__ ,__Procedimento__, Valor)
	
2Fn

	Orcamento(__NumeroOrcamento__ ,Cliente ,Endereco ,DataOrcamento)
	Procedimento(__NumeroOrcamento__ ,__NomeDoAnimal__ ,__Procedimento__,Valor)

3Fn

	Orcamento(__NumeroOrcamento__ ,Cliente ,DataOrcamento)
	Procedimento(__NumeroOrcamento__ ,__NomeDoAnimal__ ,__Procedimento__,Valor)
	Cliente(__Cliente__ , Endereco)
	

