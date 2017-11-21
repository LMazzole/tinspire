# Ti-nspire
Sammlung von Programmen für Ti-Nspire CX CAS
### HowTo
.tns file downloaden.  
.tns file in MyLib abspeichern  
Der Standardspeicherort lautet:  
•	Windows®: Eigene Dateien\TI‑Nspire\MyLib.  
•	Macintosh®: Dokumente/TI‑Nspire/MyLib.  
•	Handheld: MyLib  
.tns auf den Rechner laden  
Biblithek aktualisieren  
     doc -> Bibliotheken aktualisieren
     
## Programme
### lm\init()
Gibt den aktuellen Modus zurück (Winkel, Reell oder Komplex)  
Definiert:
- e0  
- u0  
- j als i  
  
<img src="https://github.com/LMazzole/tinspire/blob/master/images/init.PNG?raw=true" height=150 />  

### lm\arctan2(y,x)
phi= arctan2(r * sin(phi),r * cos(phi))  
x=r * cos(phi)  
y=r * sin(phi)  
r=sqrt(x^2+y^2)  
  
Note: Wikipedia hat die Notation arctan2(x,y)  
[Arctan2](https://de.wikipedia.org/wiki/Arctan2)

### lm\dhmat(a,α,d,θ)
Denavit-Hartenberg:  
a→Linklänge  
α→Linkdrehung  
d→Link Offset  
θ→Gelenkwinkel  

<img src="https://github.com/LMazzole/tinspire/blob/master/images/dhmat.PNG?raw=true" height=100 />

### lm\jacobi(f1,f2,f3,α,β,γ)
Jacobi Matrix  
<img src="https://github.com/LMazzole/tinspire/blob/master/images/jacobi.PNG?raw=true" height=150 />
