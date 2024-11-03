[TE-23] Chybná nabídka na první očkování proti chřipce zdarma Created: 20/Oct/24  Updated: 20/Oct/24 
Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	Highest 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	![Unrealistic_vaccination_date_and_free_vaccination_offer](https://github.com/user-attachments/assets/ca4632f7-e2f1-4ef2-8857-07fffe452c92)

)   
Issue links: 	Relates
relates to 	TE-12 
Test case 10: Nabídka očkování proti ... 	Done 


 Description  	 
Popis:
Při zadání nerealistického data očkování proti chřipce (01.01.1601) a data narození pacienta (01.01.1975) se v zobrazila nabídka na první očkování proti chřipce zdarma, přestože pacient již má záznam o očkování.
Kroky:
1. Otevřít kartu pacienta.
2. V sekci Očkování (Chřipka ) zadat nerealistické datum očkování (01.01.1601).
3. Zadát datum narození pacienta (01.01.1975) (věk 49).
4. Zkontrolovat, zda se zobrazí nabídka na první očkování proti chřipce zdarma.
Očekávaný výsledek: Systém by neměl nabízet první očkování proti chřipce zdarma, pokud pacient již má záznam o očkování, a to i s nerealistickým datem.
Skutečný výsledek: Systém nabízí první očkování proti chřipce zdarma i přesto, že pacient má záznam o očkování.

________________________________________

 
[TE-22] Sleva na brýle pro pacienty starší 100 let se zobrazuje jako 0 % Created: 20/Oct/24  Updated: 20/Oct/24 
Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	High 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 Discount_50_for_patients_aged_70.png     ![Alt text](path/to/image)
Issue links: 	Relates
relates to 	TE-11 
Test case 9: Vypočet slev na brýle na... 	Done 


 Description  	 
Popis:
Sleva na brýle by měla být 50 % pro pacienty od 70 let. Při zadání data narození 01.01.1923 (věk 101 let) se však sleva zobrazuje jako 0 %.
Kroky:
1. Otevřít formulář pro zadání údajů o pacientovi.
2. Zadat datum narození 01.01.1923 (věk 101 let).
3. Ověřit zobrazenou slevu.
Očekávaný výsledek: Sleva by měla být 50 % pro pacienty od 70 let.
Skutečný výsledek: Sleva se zobrazuje jako 0 %.

________________________________________

 
[TE-21]  Sleva na brýle pro pacienty, kterým je 50 let, není správně uplatněna. Created: 20/Oct/24  Updated: 20/Oct/24 
Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	High 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 Discount_20_for_patients_aged_50.png     ![Alt text](path/to/image)
Issue links: 	Relates
relates to 	TE-11 
Test case 9: Vypočet slev na brýle na... 	Done 


 Description  	 
Popis:
Sleva na brýle by měla být 30 % pro pacienty, kterým je 50 let. Při zadání data narození 01.01.1974 (věk 50 let) se však sleva zobrazuje jako 20 %.
Kroky: 
1. Otevřít formulář pro zadání údajů o pacientovi.
2. Zadat datum narození 01.01.1974 (věk 50 let).
3. Ověřit zobrazenou slevu.
Očekávaný výsledek: Sleva by měla být 30 % pro pacienty, kterým je 50 let.
Skutečný výsledek: Sleva se zobrazuje jako 20 %.

________________________________________

 
[TE-20] Akceptace nevalidního data poslední vakcinace v aplikaci Created: 20/Oct/24  Updated: 20/Oct/24 
Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	Highest 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 Vaccine_Date_Validation_Failure.png     ![Alt text](path/to/image)
Issue links: 	Relates
relates to 	TE-10 
Test case 8 : Zobrazení očkování prot... 	Done 


 Description  	 
Popis:
V aplikaci je možné zadat neplatné datum očkování, což může vést k chybám v evidenci pacientů.
Kroky:
1. Otevřít kartu pacienta.
2. Zadát neplatné datum očkování (např. 01.01.1601).
Očekávaný výsledek: Aplikace by měla zobrazit chybové hlášení a zabránit uložení neplatného data.
Skutečný výsledek: Neplatné datum očkování je uloženo bez chybového hlášení.

________________________________________

 
[TE-19] Nedostatečná validace při zadávání pravidelně uživaných léků Created: 20/Oct/24  Updated: 20/Oct/24 
Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	Highest 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 invalid data for pravidelné léky is accepted.png    ![Alt text](path/to/image) 
Issue links: 	Relates
relates to 	TE-9 
Test case 7: Vstup seznamu pravidelně... 	Done 


 Description  	 
Popis: 
Při zadávání názvů léků do pole „Pravidelné léky“ je možné vložit pouze číselné hodnoty nebo řetězce bez písmen (např. “123456789“nebo “-------“). Tento výsledek není v souladu s očekávaným výsledkem, protože názvy léků by měly obsahovat alespoň jedno písmeno. Systém by měl zabránit zadání takových hodnot a upozornit uživatele na chybu.
Kroky:
1. Otevřete formulář zdravotní karty pacienta.
2. Přejděte na sekci „Pravidelné léky“.
3. Zadejte do pole pouze číselnou hodnotu (např. “123456789“) nebo pouze symboly (např. “-------“).
4. Klikněte na tlačítko „+” pro přidání léků.
Očekávaný výsledek: Systém by měl zabránit přidání léků, pokud název neobsahuje alespoň jedno písmeno.
Skutečný výsledek: Systém povolí přidání, i když název obsahuje pouze číselná hodnota nebo symboly.
Další poznámky: Ujistěte se, že validace vstupu odpovídá specifikaci a že uživatelé nemohou zadávat neplatné názvy léků.

________________________________________

 
[TE-18] Chyba při exportu prodělaných chorob: Tuberkulóza není zobrazena v exportovaném TXT souboru Created: 20/Oct/24  Updated: 20/Oct/24 

Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	Highest 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 Tuberkulóza is missing in exported TXT file.png    ![Alt text](path/to/image) 
Issue links: 	Blocks
blocks 	TE-8 
Test case 6 : Vstup anamnézy a součas... 	Done 


 Description  	 
Popis:
Po výběru všech Prodělané choroby a Trvající obtíže a následném exportu karty do formátu TXT, není v souboru zobrazena choroba Tuberkulóza, i když byla vybrána v aplikaci.
Kroky:
1. Otevřít formulář pacienta v aplikaci.
2. Vybrat všechny možnosti v sekcích Prodělané choroby a Trvající obtíže.
3. Kliknout na tlačítko Export karty do TXT.
4. Otevřít exportovaný TXT soubor a zkontrolovat seznam prodělaných chorob.
Očekávaný výsledek: V exportovaném TXT souboru jsou zobrazeny všechny vybrané choroby, včetně Tuberkulózy.
Skutečný výsledek: V exportovaném TXT souboru chybí choroba Tuberkulóza.

________________________________________

 
[TE-17] Nedostatečná validace pro historická data narození Created: 20/Oct/24  Updated: 20/Oct/24 
Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 the unrealistic date of birth is accepted.png      the unrealistic date of birth is accepted1.png   ![Alt text](path/to/image)  
Issue links: 	Relates
relates to 	TE-6 
Test case 4: Výpočet věku na základě... 	Done 
relates to 	TE-7 
Test case 5: Výpočet BMI 	Done 


 Description  	 
Popis: 
Systém neprovádí validaci pro historická data narození, což umožňuje zadání dat, jako je 01.01.1603, bez chybového hlášení.
Kroky:
1. Otevřit formulář pro zadání údajů pacienta.
2. Vybrat datum narození 01.01.1601.
3. Kliknout na tlačitko “Uložit osobu“.
Očekávaný výsledek: Mělo by se zobrazit chybové hlášení upozorňující na nerealistické datum narození.
Skutečný výsledek: Datum bylo akceptováno a věk pacienta byl vypočítán jako 423 let bez chybového hlášení.


 Comments  	 
Comment by Anstasiia Lednei [ 20/Oct/24 ] 

Tento bug se vztahuje na výpočet BMI, protože chybí validace pro pole výška a váha, což umožňuje zadání neplatných dat.
________________________________________

 
[TE-16] Akceptace nevalidních dat pro výšku a váhu Created: 20/Oct/24  Updated: 20/Oct/24 

Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 invalid data for výška and váha are accepted.png      invalid data for výška and váha are accepted1.png     ![Alt text](path/to/image)
Issue links: 	Relates
relates to 	TE-5 
Test case 3: Vstup dalších údajů pac... 	Done 


 Description  	 
Popis: 
Systém umožňuje uložit hodnoty "1" do polí výška a váha, což je nepřijatelné. Mělo by se zobrazit chybové hlášení, pokud jsou zadané hodnoty nižší než minimální.
Kroky:
1. Otevřte formulář.
2. Zadejte “1“ do pole výška.
3. Zadejte “1“ do pole váha.
4. Klikněte na tlačitko “Uložit osobu“.
Očekaváný výsledek: Systém by měl zobrazit error message.
Skutečný výsledek: Údaje se úspěšně uloží, přestože došlo k chybě.

________________________________________

 
[TE-15] Chybejicí nápovědy pro validaci a akceptace nevalidních dat v registračním formuláři Created: 20/Oct/24  Updated: 20/Oct/24 

Status:	To Do
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Bug 	Priority: 	High 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Unresolved 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 invalid data is accepted for registration form.png      negativ testing of registration.png     ![Alt text](path/to/image)
Issue links: 	Blocks
blocks 	TE-3 
Test case 1: Registrace nového pacienta 	Done 


 Description  	 
Popis:
Ve registračním formuláři chybí uživatelské nápovědy a zprávy o validaci, což ztěžuje uživateli správné zadání údajů. Kromě toho formulář přijímá neplatná data, což může vést k nesprávné funkci systému.
Kroky:
1. Otevřte aplikaci.
2. Přejděte na formulář pro registraci.
3. Zadejte nevalidní data do jednoho nebo více polí (např. zadejte “-*/+“ v polí “Jméno“, “Příjmení“ nebo “Pojišťovna“).
3. Klikněte na tlačitko “Uložit osobu“.
Očekaváný výsledek: 
1. Uživatelské nápovědy a zprávy o validaci by měly být zobrazeny v příslušných polích, aby pomohly uživateli.
2. Systém by měl zobrazit error message a zabranit registraci s nevalidními daty.
Skutečný výsledek: 
1. Uživatelské nápovědy chybí , což ztěžuje zadání údajů.
2. Nevalidní data jsou akceptována a registrace probíhá úspěšně, přestože došlo k chybám.
Další informace: Doporučuje se přidat jasné nápovědy pro validaci pro každé pole a zajistit správnou validaci vstupních údajů.

________________________________________

 

 


Generated at Sat Nov 02 22:07:40 GMT 2024 by Anstasiia Lednei using Jira 1001.0.0-SNAPSHOT#100272-rev:32ba8f90a7d1afb98edd0d36582aadeb545e0940. 

