# extra-2
# PINES IO

# OBJETIVO GENERAL:

- Aprender y explicar los pines de entrada y salida en un arduino 1 R3 mediante la aplicacion BLOCKLYDUINO Y una simulacion virtual en la plataforma tinkercad para eviatar complicaciones en una simulacion real 

OBJETIVO ESPECIFICOS:

- Conocer y manipular la plataforma BLOCKLYDUINO para la programacion del circuito 

- Saber el funcionamiento de la programcion en bloques en la plataforma  BLOCKLYDUINO

- Conocer como funcionan los pines de un arduino y como se ejecutan 

 # MARCO TEORICO :

![image](https://user-images.githubusercontent.com/93900233/156907162-61fb68f2-8906-4c09-bd2b-075aab11f6f4.png)

![image](https://user-images.githubusercontent.com/93900233/156906862-1262c90b-d6d7-4446-bf25-34fb83af0703.png) 

![image](https://user-images.githubusercontent.com/93900233/156907127-9a4a7921-7a19-476a-a1b4-00334d9c677d.png)

![image](https://user-images.githubusercontent.com/93900233/157170956-c31867e7-bf70-4593-a85c-523a963bca40.png)

 # PROCEDIMIENTO :
 
 # PASO 1

![image](https://user-images.githubusercontent.com/93900233/156907425-b9cdb36f-ad7f-4665-b102-9ad54214d15b.png)

![image](https://user-images.githubusercontent.com/93900233/156907495-b4a0852a-66eb-404b-94a8-164fcb2b0e21.png)

![image](https://user-images.githubusercontent.com/93900233/156907656-abf85a4a-337c-47fd-99c1-47d948b060dd.png)

 # PASO 2

![image](https://user-images.githubusercontent.com/93900233/156907977-1d85b216-b463-4ca0-a5b8-1b5369207050.png)

![image](https://user-images.githubusercontent.com/93900233/157314410-ed632861-a669-4d5e-96b3-b0614f2ec41b.png)

 # PASO 3
 
 ![image](https://user-images.githubusercontent.com/93900233/157314528-c17916ee-782d-46cd-a7b7-d2be56f386a0.png)

![image](https://user-images.githubusercontent.com/93900233/156910927-2194b965-a063-4039-b3ca-fa18f277e508.png)

 # PASO 4
 
![image](https://user-images.githubusercontent.com/93900233/156911183-77660c02-a655-4177-bd88-bbaa97ccdeb1.png)

 # PASO 5
 
 ![image](https://user-images.githubusercontent.com/93900233/156911529-150b7e71-0e14-471e-a6fb-8c44718a5231.png)
 
 ![image](https://user-images.githubusercontent.com/93900233/156911591-729b8d04-1ce2-43a1-b656-f2e063ae1c61.png)

![image](https://user-images.githubusercontent.com/93900233/156911650-538fd38d-f445-492a-86c5-d0e972af2eef.png)

 ![image](https://user-images.githubusercontent.com/93900233/156911752-d7382669-9df0-46a6-9253-872fad89ca8b.png)
 
 ![image](https://user-images.githubusercontent.com/93900233/156912025-3ec1da8f-3a30-45db-856c-46950371716f.png)
 
 # PASO 6
 
 ![image](https://user-images.githubusercontent.com/93900233/156911909-23c9801c-855e-4652-b9a8-4b83610410c6.png)

 
 # PASO 7
 
 # CIRCUITO ARMADO
 
 ![image](https://user-images.githubusercontent.com/93900233/156912460-353c9fcb-0b04-4577-ba95-337c6254fd98.png)
 
![image](https://user-images.githubusercontent.com/93900233/156912411-8340c336-2aad-48a1-9558-718918149802.png)

 # PASO 8

![image](https://user-images.githubusercontent.com/93900233/156913270-b1f96bb8-3169-4cd1-b794-6ed9b29cc408.png)

![image](https://user-images.githubusercontent.com/93900233/156913274-82692975-d2e5-4f91-80c0-294af3425dfe.png)

 # PASO 9

![image](https://user-images.githubusercontent.com/93900233/156913343-de3bb0ac-f9e7-4ea9-a5a4-a1f0c30cbaed.png)

![image](https://user-images.githubusercontent.com/93900233/156913552-63c8d43e-e359-4535-bc08-be1db522ae10.png)

![image](https://user-images.githubusercontent.com/93900233/156913571-d4301744-57cd-4e39-9e36-c00a42e3e6bd.png)

 # PASO 10
 
![image](https://user-images.githubusercontent.com/93900233/157315369-856c8de6-cfbd-421a-83b0-50e1db00931b.png)

![image](https://user-images.githubusercontent.com/93900233/157315529-a89f4513-ceb2-4994-8417-7b184f447ffb.png)

# codigo 

void setup()
{
  pinMode(8, INPUT);
  pinMode(4, OUTPUT);
  pinMode(10, INPUT);
  pinMode(3, OUTPUT);
}


void loop()
{
  if (digitalRead(8) == HIGH) {
    digitalWrite(4, HIGH);

  } else {
    digitalWrite(4, LOW);

  }
  if (digitalRead(10) == HIGH) {
    digitalWrite(3, HIGH);

  } else {
    digitalWrite(3, LOW);

  }

}
# VIDEO:
https://www.youtube.com/watch?v=mgmheJWm8WQ

# CONCLUSIONES:

-  BLOCKLYDUINO es  una  manera  excelente  para comezar a programar ya que te facilita la programacion en bloques y lo transcribe a programacion en texto 
-  Se supo el funcionamiento tanto de un pin de salida  como de entrada dependiendo del circuito a ejecutar 
-  Tanto BLOCKLYDUINO como TINKERCAD son herramientas que me sirvio para para corregir y evitar  errores antes deuna simulacion real.

# BIBLIOGRAFIAS:

- COMPU HOY. (s.f.). Obtenido de https://www.compuhoy.com/que-es-un-pin-io-digital/

- FRAMEBOXXIN. (2022). Obtenido de https://frameboxxindore.com/es/apple/best-answer-what-is-an-io-pin.html

- MAKERELECTRONICO. (19 de MARZO de 2019). Obtenido de https://www.makerelectronico.com/io-puertos-digitales-tris-port-lat-con-pic18f4550/

- PROGRAMAMOS. (s.f.). Obtenido de https://programamos.es/entornos-graficos-de-programacion-con-
arduino/#:~:text=Blockly%20es%20un%20entorno%20gr%C3%A1fico,con%20el%20IDE%20de%20Arduino.



