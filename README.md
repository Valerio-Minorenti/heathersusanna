NON TOCCARE I FILE .HTML, SE HAI DUBBI SCRIVIMI
## Come aggiungere un'opera?
## Scaricare e aggiungere la foto
Per aggiungere un'opera devi innanzitutto scaricare la foto in formato jpg e salvarla come: NOMEOPERA.jpg 

Non usare spazi se l'opera ha più nomi la scrivi come: Cena_di_Natale.jpg

Una volta che l'hai salvata sul tuo computer, clicca sulla cartella images. Dopo averci cliccato in alto a destra ci sara scritto add file.

Clicca su add file e poi su UPLOAD FILE. Metti la foto lì dentro e poi salva le modifiche

## AGGIUNGERLA AL FILE opere.json

Una volta che hai salvato la foto non ti ressta che aggiungerla alla lista delle opere nel file json.

Le opere andranno sempre aggiunte come segue:

{<br>
		"id_quadro" : Vedi l'ultimo ID e fai +1 (ESEMPIO: se l'ultima foto è apartment complex e ha come ID 21,  tu qui scriverai 22) <br>
		"nome_quadro_it" : "Nome quadro in ITALIANO",<br>
		"nome_quadro_en" : "Nome quadro in INGLESE",<br>
		"tipo_quadro_id" : 2 o 3 o 4, (RICORDA: 2=Dipinti/Paintings, 3=Disegni/Drawings, 4= Stampe/printmaking<br>
		"dimensioni_quadro_id" : 1 o 2 3, (RICORDA: 1=piccolo, 2=medio , 3=Grande)<br>
		"immagine" : "NOME_QUADRO.jpg",<br>
		"dimensioni_num" : "Numero1 x numero2",<br>
		"descrizione" : "descrizione ITALIANA, anno",<br>
		"descrizioni_en" : "descrizione INGLESE , anno"<br>
	<br>}<br>
 Se vuoi aggiungere più quadri ti basterà fare la stessa cosa più volte

