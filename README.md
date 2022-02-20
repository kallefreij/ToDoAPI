# ToDoAPI
 Todo-app API project

 Öppna solutionen 

 Projektet är byggt med Code First approachen, så måste generera upp databasen.

 Gå in i appsettings.json och se under ConnectionStrings vad DBconnectionen är satt till.
 Jag har kört på en SQLExpress server (Kräver att en sån är installerad) så om man är okej med det är det bara att låta det vara, och databasnamnet kommer bli todoDB om man vill att den ska heta något annat kan man ändra det. 
 Om man vill använda någon annan SQL server så får man stoppa in en egen connection string.

 När du är nöjd med connection stringen så får man öppna package manager console i VS och köra commandet Update-Database. Då kommer VS köra de magrations som finns och skapa upp databasen efter modellerna.

 Nu borde det finnas en todoDB. Kontrollera det, sen ska det bara vara att köra igång API projektet.
