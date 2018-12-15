## SEPARACAO EM CONTEXTOS DELIMITADOS

 >- Mesmo após a separação do Sistema em Subsistema/Dominio/Subdomínio, ainda assim o entendimento é complexo.

Contextos Delimidatos - pequenos pedaços do programa a se separar, onde o objetivo é garantir um pequeno **batch size** (tamanho da mudança), onde se dimunui a área de código afetada por ajustes, seja por exemplo, a reescrita em outra linguagem. 

Ex. 

ERP
**Modulo** - FI - Financeiro
**Subdominio** - Pagamentos
**Contexto limitado** - Realização de Pagamentos

Atenção: Um Contexto Delimitado, não quer dizer necessariamente que será criado um micro serviço para todo ele. Há exemplo de micro serviços ainda menores - somente para um GET, por exemplo.
