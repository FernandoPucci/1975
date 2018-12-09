## DOMINIOS

### DOMINIOS RICOS
 Dominios muito bem elaborados em linguagens de alto nível como Java e C#. Classes especialistas com diversas funcionalidades.

### DOMINIOS ANÊMICOS
Dominios pobres onde as classes apenas mapeiam as entidades do banco de dados e na maioria das vezes a lógica de negócio está na base de dados.

## SUBDOMINIOS
 Dificilmente se atava um grande sistema sem quebrá-lo em partes. 
 Para tal, se quebra o domínio principal em **subdomínios**.
 Podem ser definidos como a segmentação de um domínio em diversas outras partes.

---

## CONTEXTOS DELIMITADOS
 São __pequenos pedaços__ do sistema a ser criado. 
 __Batch Size__ : Tamanho da mudança.
 Quando menor o __batch size__ mais fácil a mudança. Exemplo de microsserviços. 

O exemplo do curso utiliza o **Contexto de Pagamento**, ou seja, pode facilmente ser modelado para um microsserviço de __**Pagamento**__.

 O Conceito de **Contexto Limitado** não exige que o modelo desenhado seja obrigatóriamente aplicado a Microsserviços.
