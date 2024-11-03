[TE-14] Test case 12: Export karty pacienta do textového souboru Created: 20/Oct/24  Updated: 21/Oct/24  Resolved: 21/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![exported data to txt format](https://github.com/user-attachments/assets/f33b2ae2-e39d-49b2-8733-64d7bc9c76a6)
  

 Description  	 
Cíl: Ověřit, že karta pacienta může být exportována do textového souboru. 
Kroky: 
1.Exportovat kartu pacienta do textoveho souboru. 
Očekávaný výsledek: Karta je úspěšně exportována a všechny údaje jsou správně zobrazeny v textovém souboru.
Skutečný výsledek: Karta je úspěšně exportována a všechny údaje jsou správně zobrazeny v textovém souboru.

________________________________________

 
[TE-13] Test case 11: Uložení a načtení karty pacienta Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 



 Description  	 
Cíl: Ověřit, že karta pacienta může být správně uložena a načtena. 
Kroky: 
1.Uložit kartu pacienta do souboru. 
2. Načíst kartu zpět do programu.
Očekávaný výsledek: Data pacienta se správně načtou bez ztráty údajů. 
Skutečný výsledek: Data pacienta se správně načitají bez ztráty údaju.

________________________________________

 
[TE-12] Test case 10: Nabídka očkování proti chřipce zdarma Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![Unrealistic_vaccination_date_and_free_vaccination_offer](https://github.com/user-attachments/assets/09ada8a3-31fc-4a48-be6b-d74822083468)

Issue links: 	Relates
relates to 	TE-23 
Chybná nabídka na první očkování prot... 	To Do 


 Description  	 
Cíl: Ověřit, že pacienti splňující věková kritéria dostanou nabídku na očkování zdarma. 
Kroky:
1. Zadat věk pacienta. 
2. Zkontrolovat, zda se zobrazí nabídka na očkování zdarma. 
Očekávaný výsledek: Nabídka se zobrazí pro muže mezi 25-50 lety a pro ženy mezi 25-60 lety.
Skutečný výsledek: I přes zadání nerealistického data očkování (01.01.1601) a správného data narození (01.01.1964) byla nabídka na první očkování proti chřipce zdarma stále zobrazena, což je v rozporu s očekávaným chováním systému.

________________________________________

 
[TE-11] Test case 9: Vypočet slev na brýle na základě věku Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![Discount_20_for_patients_aged_50](https://github.com/user-attachments/assets/c4b6bca8-7134-49e1-9010-c9389096d7cb) ![Discount_50_for_patients_aged_70](https://github.com/user-attachments/assets/eaff64ef-181f-465a-8e8e-2e5bf69aba72)


Issue links: 	Relates
relates to 	TE-21 
Sleva na brýle pro pacienty, kterým ... 	To Do 
relates to 	TE-22 
Sleva na brýle pro pacienty starší 10... 	To Do 


 Description  	 
Cíl: Ověřit, že sleva na brýle je správně uplatněna na základě věku pacienta.
Kroky:
1.Otevřít formulář pro zadání údajů o pacientovi.
2.Zadát datum narození pacienta.
3.Zkontrolovat, zda se sleva automaticky zobrazí.
Očekávaný výsledek: Sleva je správně vypočitána podle věkových kritérií.
Skutečný výsledek: Po zadání data narození, odpovídajícího věku 50 let, se sleva zobrazila jako 20 %, místo očekávané 30 %. Také při zadání věku 101 let se sleva zobrazila jako 0 %, což je chybné, protože by měla být 50 %

________________________________________

 
[TE-10] Test case 8 : Zobrazení očkování proti tetanu, žloutence a chřipce Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Highest 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	![Vaccine_Date_Validation_Failure](https://github.com/user-attachments/assets/a10c68bf-95fa-42c0-9a80-e42dcc21932d)

Issue links: 	Relates
relates to 	TE-20 
Akceptace nevalidního data poslední v... 	To Do 


 Description  	 
Cíl: Ověřit, že karta pacienta správně zobrazuje údaje o očkování proti tetanu, žloutence a chřipce. 
Kroky:
1.Zkontrolovat kartu pacienta. 
2. Ujistit se, že údaje o očkování jsou správně zovrazeny. 
Očekávaný výsledek: Očkování je správně zobrazeno v kartě pacienta.
Skutečný výsledek: Neplatné datum očkování je uloženo bez chybového hlášení.

________________________________________

 
[TE-9] Test case 7: Vstup seznamu pravidelně užívaných léků Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![invalid data for pravidelné léky is accepted](https://github.com/user-attachments/assets/4732c92e-d7e1-45ea-8489-79294f4e3729)
 
Issue links: 	Relates
relates to 	TE-19 
Nedostatečná validace při zadávání pr... 	To Do 


 Description  	 
Cíl: Ověřit, že formulář správně ukládá seznam užívaných léků. 
Kroky: 
1. Zadát léky do odpovídajícího pole. 
2. Uložit údaje. 
Očekávaný výsledek: Léky jsou správně uloženy a zobrazují se.
Skutečný výsledek: Systém povolí přidání, i když název obsahuje pouze číselná hodnota nebo symboly.

________________________________________

 
[TE-8] Test case 6 : Vstup anamnézy a současných onemocnění Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![Tuberkulóza is missing in exported TXT file](https://github.com/user-attachments/assets/482e679e-f38c-4ac3-9d8f-af4e4d127af4)

Issue links: 	Blocks
is blocked by 	TE-18 
Chyba při exportu prodělaných chorob:... 	To Do 


 Description  	 
Cíl: Ověřit, že formulář přijímá seznam onemocnění. 
Kroky: 
1.Zadát text do pole "anamnéza". 
2. Uložit údaje. 
Očekávaný výsledek: Zadáné údaje se uloží bez chyb.
Skutečný výsledek: V exportovaném TXT souboru chybí choroba Tuberkulóza.

________________________________________

 
[TE-7] Test case 5: Výpočet BMI Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 

Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	![BMI calculation for invalid input](https://github.com/user-attachments/assets/c981fdcb-eeb0-4c2a-8a0b-aaacc9dbb3ee)

Issue links: 	Relates
relates to 	TE-17 
Nedostatečná validace pro historická ... 	To Do 


 Description  	 
Cíl: Ujistit se, že BMI je správně vypočítáno na základě zadané výšky a hmotností. 
Kroky:
1. Zadat výšku pacienta. 
2. KLiknout na tlačitko pro uložení. 
Očekávaný výsledek: BMI se vypočítá podle vzorce: váha (kg) /(výška(m))^2 a správně se zobrazí.
Skutečný výsledek: BMI se správně vypočítal na základě zadaných údajů, ale systém neprovedl validaci pro neplatné hodnoty (např. 5 kg), což vedlo k nereálnému výsledku.

________________________________________

 
[TE-6] Test case 4: Výpočet věku na základě data narození Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![the unrealistic date of birth is accepted1](https://github.com/user-attachments/assets/22327dce-1105-470f-949e-ea1c0c9120d9) ![the unrealistic date of birth is accepted](https://github.com/user-attachments/assets/9348f966-423a-4050-ab46-2c7ac56d4559)


Issue links: 	Relates
relates to 	TE-17 
Nedostatečná validace pro historická ... 	To Do 


 Description  	 
Cíl: Ověřit, že věk je vypočítán správně na základě zadaného data narození. 
Kroky: 
1. Zadát datum narození. 
2. Kliknout na tlačitko "Uložit osobu". 
Očekávaný výsledek: Věk pacienta je správně zobrazen.
Skutečný výsledek: Věk pacienta byl vypočítán jako 423 let, a nebylo zobrazeno žádné chybové hlášení při zadání historického data narození 01.01.1601.

________________________________________

 
[TE-5] Test case 3: Vstup dalších údajů pacienta Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![invalid data for výška and váha are accepted](https://github.com/user-attachments/assets/491e8b8f-f85c-43ec-86d2-eab701627e3a) ![invalid data for výška and váha are accepted1](https://github.com/user-attachments/assets/6cde3074-6774-41af-a286-0ee40367216a)


Issue links: 	Relates
relates to 	TE-16 
Akceptace nevalidních dat pro výšku a... 	To Do 


 Description  	 
Cíl: Ověřit, že formulář správně přijímá další pole (pohlaví, výška, váha, krevní skupina, pracovní pozice). 
Kroky: 
1. Zadát údaje do polí pohlaví, výška, váha, krevní skupina, pracovní pozice. 
2. Uložit formulář. 
Očekávaný výsledek: Další údaje jsou správně uloženy.
Skutečný výsledek: Údaje se úspěšně uloží, přestože došlo k chybě.

________________________________________

 
[TE-4] Test case 2: Kontrola nepřítomností povinných polí Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	![the error message is displayed (all)](https://github.com/user-attachments/assets/c30ef42f-8d17-4952-b9ad-d07fa794bfe0) ![the error message is displayed 1](https://github.com/user-attachments/assets/282f2cb8-7561-4200-acf7-166cd702b193) ![the error message is displayed 2](https://github.com/user-attachments/assets/c7c83031-d4d0-492f-87d6-e0ccb0485581)


  

 Description  	 
Cíl: Ujistit se, že povinná pole nelze ponechat prazdná. 
Kroky: 
1.Otevřit formulář. 
2. Nevyplnit jedno nebo více polí. 
3.Stisknout tlačitko "Uložit osobu". 
Očekávaný výsledek: Po kliknutí na tlačítko zobrazuje se chybová zpráva, která jasně informuje uživatele o tom, že pole "Jméno", "Příjmení" (nebo jiná povinná pole) musí být vyplněna.
Skutečný výsledek: Po kliknutí na tlačítko zobrazuje se chybová zpráva, která jasně informuje uživatele o tom, že pole "Jméno", "Příjmení" (nebo jiná povinná pole) musí být vyplněna.

________________________________________

 
[TE-3] Test case 1: Registrace nového pacienta Created: 20/Oct/24  Updated: 20/Oct/24  Resolved: 20/Oct/24 
Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	High 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 

Attachments: 	 ![invalid data is accepted for registration form](https://github.com/user-attachments/assets/37a61bf9-55da-4fa0-a2e3-9e4734f52598) ![negativ testing of registration](https://github.com/user-attachments/assets/9523672d-9ee8-4e83-8237-2c6d23ab7140)


Issue links: 	Blocks
is blocked by 	TE-15 
Chybejicí nápovědy pro validaci a akc... 	To Do 


 Description  	 
Test case 1: Registrace nového pacienta
Cíl: Ověřit, že formulář správně přijímá povinná pole (jméno, příjmení, datum narození, pojišťovnu).
Kroky: 
1.	Otevřit formulář.
2.	Zadat jméno, příjmění, datum narození a pojišťovnu.
3.	Stisknete tlačitko "Uložit osobu".
Očekavaný výsledek: Formulář by měl být uložen bez chyb.
Skutečný výsledek:
1.	Uživatelské nápovědy chybí, což ztěžuje zadání údajů.
2.	Nevalidní data jsou akceptována a registrace probíhá úspěšně, přestože došlo k chybám.
Další informace: Doporučuje se přidat jasné nápovědy pro validaci pro každé pole a zajistit správnou validaci vstupních údajů.

________________________________________

 
[TE-2] Test cases Created: 19/Oct/24  Updated: 20/Oct/24  Due: 21/Oct/24  Resolved: 20/Oct/24 

Status:	Done
Project:	TesterIS3.exe

Components:	None 
Affects versions:	None 
Fix versions:	None 

Type: 	Task 	Priority: 	Medium 
Reporter: 	Anstasiia Lednei 
Assignee: 	Anstasiia Lednei 

Resolution: 	Done 	Votes: 	0 
Labels: 	None 
Remaining Estimate:	Not Specified 
Time Spent:	Not Specified 
Original estimate:	Not Specified 



 Description  	 
1.	Vstup povinných údajů pacienta.
Test case 1: Registrace nového pacienta
Cíl: Ověřit, že formulář správně přijímá povinná pole (jméno, příjmení, datum narození, pojišťovnu).
Kroky: 
1. Otevřit formulář. 
2. Zadat jméno, příjmění, datum narození a pojišťovnu. 
3. Stisknete tlačitko "Uložit osobu".
Očekavaný výsledek: Formulář by měl být uložen bez chyb.
Test case 2: Kontrola nepřítomností povinných polí
Cíl: Ujistit se, že povinná pole nelze ponechat prazdná.
Kroky: 
1.Otevřit formulář. 
2. Nevyplnit jedno nebo více polí. 3.Stisknout tlačitko "Uložit osobu". 
Očekávaný výsledek: Mělo by se zobrazit chybové hlášení o povinných polích.
1.	Vstup dalších údajů pacienta
Test case 3: Vstup dalších údajů pacienta
Cíl: Ověřit, že formulář správně přijímá další pole (pohlaví, výška, váha, krevní skupina, pracovní pozice).
Kroky:
1. Zadát údaje do polí pohlaví, výška, váha, krevní skupina, pracovní pozice. 
2. Uložit formulář.
Očekávaný výsledek: Další údaje jsou správně uloženy.
1.	Výpočet věku a BMI
Test case 4: Výpočet věku na základě data narození
Cíl: Ověřit, že věk je vypočítán správně na základě zadaného data narození.
Kroky:
1. Zadát datum narození. 
2. Kliknout na tlačitko "Uložit osobu".
Očekávaný výsledek: Věk pacienta je správně zobrazen.
Test case 5: Výpočet BMI
Cíl: Ujistit se, že BMI je správně vypočítáno na základě zadané výšky a hmotností.
Kroky:
1. Zadat výšku pacienta. 
2. KLiknout na tlačitko pro uložení.
Očekávaný výsledek: BMI se vypočítá podle vzorce: váha (kg) /(výška(m))^2 a správně se zobrazí.
1.	Anamnéza a léky
Test case 6 : Vstup anamnézy a současných onemocnění
Cíl: Ověřit, že formulář přijímá seznam onemocnění.
Kroky:
1.Zadát text do pole "anamnéza". 
2. Uložit údaje.
Očekávaný výsledek: Zadáné údaje se uloží bez chyb.
Test case 7: Vstup seznamu pravidelně užívaných léků
Cíl: Ověřit, že formulář správně ukládá seznam užívaných léků.
Kroky:
1. Zadát léky do odpovídajícího pole. 
2. Uložit údaje.
*Očekávaný výsledek:*Léky jsou správně uloženy a zobrazují se.
1.	Očkování a slevy
Test case 8 : Zobrazení očkování proti tetanu, žloutence a chřipce
*Cíl:*Ověřit, že karta pacienta správně zobrazuje údaje o očkování proti tetanu, žloutence a chřipce.
Kroky:
1.Zkontrolovat kartu pacienta.
2. Ujistit se, že údaje o očkování jsou správně zovrazeny.
Očekávaný výsledek: Očkování je správně zobrazeno v kartě pacienta.
Test case 9: Vypočet slev na brýle na základě věku
Cíl: Ověřit, že sleva na brýle je správně uplatněna na základě věku pacienta.
Kroky:
1. Otevřít formulář pro zadání údajů o pacientovi.
2. Zadát datum narození pacienta.
3. Zkontrolovat, zda se sleva automaticky zobrazí.
Očekávaný výsledek: Sleva je správně vypočitána podle věkových kritérií.
Test case 10: Nabídka očkování proti chřipce zdarma
Cíl: Ověřit, že pacienti splňující věková kritéria dostanou nabídku na očkování zdarma.
Kroky:
1. Zadat věk pacienta. 
2. Zkontrolovat, zda se zobrazí nabídka na očkování zdarma.
Očekávaný výsledek: Nabídka se zobrazí pro muže mezi 25-50 lety a pro ženy mezi 25-60 lety.
1.	Uložení a export
Test case 11: Uložení a načtení karty pacienta
Cíl: Ověřit, že karta pacienta může být správně uložena a načtena.
Kroky: 
1.Uložit kartu pacienta do souboru. 
2. Načíst kartu zpět do programu.
Očekávaný výsledek: Data pacienta se správně načtou bez ztráty údajů.
Test case 12: Export karty pacienta do textového souboru
Cíl: Ověřit, že karta pacienta může být exportována do textového souboru.
Kroky: 
1.Exportovat kartu pacienta do textoveho souboru.
Očekávaný výsledek: Karta je úspěšně exportována a všechny údaje jsou správně zobrazeny v textovém souboru.

________________________________________
