## Exercici 18
Disposem d�un m�tode que valida les edats que rep com a argument. Una edat �s v�lida si est� en l'interval de 0 a 120.

### Defineix les classes d'equival�ncia per al m�tode que valida les edats.
De 0 a 120
### Indica quins casos d'edat podrien considerar-se extrems i per qu�.
Valors Limits:
Minim 0
Maxim 120
Valors fora del limit 321 777 -12
### Escriu tests per a cadascun dels casos de prova.
1. Test 1
   Entrada: 120
   Resultat Esperat: True
   Resultat Obtingut: 
2. Test 1
   Entrada: 0 
   Resultat Esperat: True
   Resultat Obtingut: 
3. Test 1
   Entrada: 321
   Resultat Esperat: False
   Resultat Obtingut:
4. Test 1
   Entrada: 777
   Resultat Esperat: False
   Resultat Obtingut:
5. Test 1
   Entrada: -12
   Resultat Esperat: False
   Resultat Obtingut:
### La declaraci� del m�tode �s la seg�ent: public static bool IsValidAge(int age);