# 0036468186

# Pitanje 1.:
Dodani su ClassLibrary.dll i ClassLibrary.pdb file-ovi u folderu Debug. 
Ako maknemo .dll file aplikacije prestane raditi jer konzolna aplikacija sad ovisi i o Class Library projektu.
Datoteke koje treba poslati su KonzolnaAplikacija.exe i ClassLibrary1.dll

# Pitanje 2.:
Konzolna aplikacija je pokazala novi string jer se prevođenjem konzolne aplikacije automatski prevodi i Class Library.

# Pitanje 3.:
Ispisalo se Pero: Hello World

# Pitanje 4.:
Dodana je PeroClassLibrary.dll datoteka.

# Pitanje 5.:
Radi jer je konzolna aplikacija preuzela .dll file prilikom prevođenja bez obzira što je originalan izbrisan.
File .dll se traži se u konzolnoj aplikaciji, zato i build radi.

# Pitanje 6.:
Uspjesno se proveo samo jedan build proces. Ponovo se stvorio NodaTime folder.
