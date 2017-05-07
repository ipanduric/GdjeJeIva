# GdjeJeIva

GdjeJeIva jednostavna je Android aplikacija koja pokazuje trenutnu lokaciju korisnika koriste�i Google mape. Omogu�eno je i
postavljenje markera na bilo koju lokaciju na karti, pritom se emitira zvuk, koriste�i SoundPool klasu, i privremeno se ispisuje 
lokacija markera. Na svaki klik na marker, ponovno se ispisuje lokacija. Za dodavanje markera pomogao je slijede�i link:
[//stackoverflow.com/questions/17143129/add-marker-on-android-google-map-via-touch-or-tap]. 
Omogu�eno je i pokretanje kamere iz aplikacije, spremanje slike i slanje notifikacije korisniku. Klikom na notifikaciju 
otvara se uslikana slika. Za te potrebe kori�ten je kod sa linka: 
[https://github.com/nuuneoi/Lab-Intent-FileProvider/blob/master/app/src/main/java/com/inthecheesefactory/lab/intent_fileprovider/MainActivity.java].
Za kori�tenje senzora, kamere [http://stackoverflow.com/questions/38552144/how-get-permission-for-camera-in-android-specifically-marshmallow] 
i pristup memoriji telefona zatra�ena su dopu�tenja, koja su definirana i u manifest datoteci.
Osim stackoverflowa i githuba, za izradu su kori�teni materijali sa laboratorijskih vje�bi. Aplikacije je potpisana klju�em u 
trajanju od 50 godina. Prilikom izrade bilo je problema kod pristupanja kameri, vrlo vjerojatno zbog nove verzije Androida na ure�aju, 
no gore navedeni kod s Githuba je pomogao rje�iti problem.