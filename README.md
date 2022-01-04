# TAREA-CAP-7-8
 
# Objetivos #

**Objetivo General:**

- Analizar de manera adecuada el como se combinan los resistores en serie y en paralelo para asi reconocer importantes tipos de circuitos con el divisor de voltaje con carga resistiva, la red en escalera y el puente de wheatstone presentes en varias situaciones practicas, además, se identifican nuevos metodos que facilitaran el analisis de circuitos complejos debido a que los circuitos son controlados por fuentes de voltaje o corriente y es importante entender como estos elementos funcionan.



**Objetivos específicos:**

-	Comprender,identificar y relacionar  a los circuitos mixtos (serie-paralelo), así como también  las fallas que pueden presentar en el ámbito practico.
-	Aplicar la teoría tanto de los divisores de voltaje como de corriente de ser necesario .
-	Analizar las redes en escalera y el puente Wheatstone para su futura aplicación en los ejercicios del capítulo.
-	Realizar los cálculos correspondientes para medir corrientes, voltajes y resistencias de forma correcta.
-	Aplicar el teorema de superposición para la resolución de ejercicios, así como también el teorema de Norton y Thevening , el cual nos permitirá simplificar el circuito. 
-	Comprender las características que presenta una fuente de voltaje cd y una fuente de corriente.
-	Dibujar los circuitos simplificados para el mejor entendimiento de los problemas.


# Marco Teórico #

**CAPITULO 7**

[![CAPITULO-7-PT1.png](https://i.postimg.cc/W49Jjx2Y/CAPITULO-7-PT1.png)](https://postimg.cc/yJZNyQ30)


[![CAPITULO-7-PT2.png](https://i.postimg.cc/V6d0N4vf/CAPITULO-7-PT2.png)](https://postimg.cc/N9vjJ6RS)

**CAPITULO 8**

[![capitulo8-tarea.jpg](https://i.postimg.cc/L5WqjBwg/capitulo8-tarea.jpg)](https://postimg.cc/T5rY6mRT)


## EJERCICIOS ##

**3. En cada circuito de la figura 7-62, identifique las relaciones en serie-paralelo de los resistores vistas
desde la fuente.**
![imagen](https://user-images.githubusercontent.com/93798427/146658894-048dc7f7-1c8e-4380-80be-ef7d8119bfd4.png)

a) R1 y R4-- Serie
R2 y R3 -- Paralelo 

b) R1-- Serie
R2,3,4-- Paralelo 

c)R2,R3-- Paralelo
R4,5--Paralelo
R1-Paralelo

**5.Trace el diagrama esquemático de la configuración de la tarjeta de circuito impreso mostrada en la figura 7-64 indicando valores de resistor, e identifique las relaciones en serie-paralelo.**

![image](https://user-images.githubusercontent.com/93739242/147988149-eac2ceab-a4d9-4c76-b03d-58a6ad87cd24.png)


En el esquema anterior, la combinación en paralelo de resistencias en serie R1 y R3 y las resistencias en serie R2 y R4 esta en serie con las resistencias R5, R6, R7, R8, R9, R10 y R11

![image](https://user-images.githubusercontent.com/93739242/147988111-3064b64e-653a-4485-94dd-d4bed881e6da.png)







**9 Para cada uno de los circuitos mostrados en la figura 7-62, determine la resistencia total presentada a
la fuente**

A

![imagen](https://user-images.githubusercontent.com/93798427/146658942-88f1767b-6db7-4f40-b184-89f349e3cb7b.png)

![imagen](https://user-images.githubusercontent.com/93798427/146658945-5a8717d4-e841-44e3-8ec8-73b697d6929a.png)

B

![imagen](https://user-images.githubusercontent.com/93798427/146658961-9fff3eb5-f690-4ae4-ae01-d67619d4df1a.png)

![imagen](https://user-images.githubusercontent.com/93798427/146658980-1eada47b-aaa6-4805-af10-f052acaf377f.png)

C

![imagen](https://user-images.githubusercontent.com/93798427/146659007-222a26d1-bd94-4169-8b06-a4ef146df9c7.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659016-39ef1728-571a-457e-82ff-d5562478fb9b.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659026-ab7ce40c-e056-4814-b15a-a06f7ede079f.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659039-b3cb9405-72bc-4336-a2a7-d0aca50cf376.png)



**11. Determine la corriente a través de cada resistor del circuito de la figura 7-62; calcule en seguida cada caída de voltaje.**

![image](https://user-images.githubusercontent.com/93739242/147988216-da0d9cc7-63c5-449b-8d11-dbaa7de167c1.png)

![image](https://user-images.githubusercontent.com/93739242/147988226-60bf51df-ae75-485b-b4e0-271480d3870b.png)

<img src="https://latex.codecogs.com/svg.image?\\&space;R_{2}&space;\textit{&space;es&space;paralelo&space;a&space;}&space;R_{3}\to&space;\frac{100}{2}=50\Omega&space;\\[10pt]R_{T}=R_{1}&space;&plus;R_{2||3}&plus;R_{4}=56\Omega&space;&plus;50\Omega&space;&plus;27\Omega&space;=133\Omega&space;\\[10pt]I_{T}=\frac{V_{T}}{R_{T}}=\frac{1.5}{133}=11.3mA\\[10pt]R_{1}&space;\textit{&space;en&space;serie&space;}&space;R_{4}\\[10pt]\textit{Intensidad&space;de&space;corriente&space;}R_{1},R_{4}\\[10pt]I_{T}=I_{1}=I_{4}=11.3mA\\[10pt]\textit{Voltaje&space;de&space;}R_{1},&space;R_{4}\\[10pt]V_{1}=R_{1}*I_{1}=11.3*56=633mV\\[10pt]V_{4}=R_{4}*I_{4}=11.3*27=305mV\\[10pt]R_{2}&space;\textit{&space;en&space;paralelo&space;}&space;R_{3}\\[10pt]\textit{Intensidad&space;de&space;corriente&space;}R_{2},R_{3}\\[10pt]\frac{I_{T}}{2}=\frac{11.3}{2}=I_{2}=I_{3}=5.65mA\\[10pt]\textit{Voltaje}R_{2},&space;R_{3}\\[10pt]V_{2}=V_{3}=I_{2}*R_{2}=5.63mA*100=563mV\\[10pt]&space;" title="\\ R_{2} \textit{ es paralelo a } R_{3}\to \frac{100}{2}=50\Omega \\[10pt]R_{T}=R_{1} +R_{2||3}+R_{4}=56\Omega +50\Omega +27\Omega =133\Omega \\[10pt]I_{T}=\frac{V_{T}}{R_{T}}=\frac{1.5}{133}=11.3mA\\[10pt]R_{1} \textit{ en serie } R_{4}\\[10pt]\textit{Intensidad de corriente }R_{1},R_{4}\\[10pt]I_{T}=I_{1}=I_{4}=11.3mA\\[10pt]\textit{Voltaje de }R_{1}, R_{4}\\[10pt]V_{1}=R_{1}*I_{1}=11.3*56=633mV\\[10pt]V_{4}=R_{4}*I_{4}=11.3*27=305mV\\[10pt]R_{2} \textit{ en paralelo } R_{3}\\[10pt]\textit{Intensidad de corriente }R_{2},R_{3}\\[10pt]\frac{I_{T}}{2}=\frac{11.3}{2}=I_{2}=I_{3}=5.65mA\\[10pt]\textit{Voltaje}R_{2}, R_{3}\\[10pt]V_{2}=V_{3}=I_{2}*R_{2}=5.63mA*100=563mV\\[10pt] " />

![image](https://user-images.githubusercontent.com/93739242/147988292-875fc2b9-1fe0-4616-a487-f9707496fe3c.png)

<img src="https://latex.codecogs.com/svg.image?\\\textit{En&space;paralelo&space;}&space;R_{2},&space;R_{3},&space;R_{4}\to&space;\frac{1}{\frac{1}{680}&plus;\frac{1}{330}&plus;\frac{1}{180}}=99.43\Omega&space;\\[10pt]R_{T}=R_{1}&space;&plus;R_{2||3||4}=680\Omega&space;&plus;99.43\Omega=779.43\Omega&space;\\[10pt]I_{T}=\frac{V_{T}}{R_{T}}=\frac{3}{779.43}=3.85mA\\[10pt]\textit{Intensidad&space;de&space;corriente&space;}R_{1}\\[10pt]I_{T}=I_{1}=3.85mA\\[10pt]\textit{Voltaje&space;de&space;}R_{1}\\[10pt]V_{1}=R_{1}*I_{1}=680*3.85=2.62V\\[10pt]\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;}R_{4}\\[10pt]R_{eq}=\frac{1}{\frac{1}{680}&plus;\frac{1}{330}}=222.17\Omega&space;\\[10pt]I_{4}=\frac{I_{T}*R_{eq}}{R_{eq}&plus;R_{4}}=3.84*\frac{mA*222.17}{222.17&plus;180}=2.13mA\\[10pt]V_{4}=R_{4}*I_{4}=2.13*180=383mV\\[10pt]&space;" title="\\\textit{En paralelo } R_{2}, R_{3}, R_{4}\to \frac{1}{\frac{1}{680}+\frac{1}{330}+\frac{1}{180}}=99.43\Omega \\[10pt]R_{T}=R_{1} +R_{2||3||4}=680\Omega +99.43\Omega=779.43\Omega \\[10pt]I_{T}=\frac{V_{T}}{R_{T}}=\frac{3}{779.43}=3.85mA\\[10pt]\textit{Intensidad de corriente }R_{1}\\[10pt]I_{T}=I_{1}=3.85mA\\[10pt]\textit{Voltaje de }R_{1}\\[10pt]V_{1}=R_{1}*I_{1}=680*3.85=2.62V\\[10pt]\textit{Intensidad de corriente y voltaje }R_{4}\\[10pt]R_{eq}=\frac{1}{\frac{1}{680}+\frac{1}{330}}=222.17\Omega \\[10pt]I_{4}=\frac{I_{T}*R_{eq}}{R_{eq}+R_{4}}=3.84*\frac{mA*222.17}{222.17+180}=2.13mA\\[10pt]V_{4}=R_{4}*I_{4}=2.13*180=383mV\\[10pt] " />

<img src="https://latex.codecogs.com/svg.image?\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;}R_{3}\\[10pt]R_{eq}=\frac{1}{\frac{1}{680}&plus;\frac{1}{180}}=142.32\Omega&space;\\[10pt]I_{3}=\frac{I_{T}*R_{eq}}{R_{eq}&plus;R_{3}}=3.84*\frac{mA*142.32}{142.32&plus;330}=1.16mA\\[10pt]V_{3}=R_{3}*I_{3}=1.16*330=383mV\\[10pt]\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;}R_{2}\\[10pt]R_{eq}=\frac{1}{\frac{1}{180}&plus;\frac{1}{330}}=116.47\Omega&space;\\[10pt]I_{2}=\frac{I_{T}*R_{eq}}{R_{eq}&plus;R_{2}}=3.84*\frac{mA*116.47}{116.47&plus;680}=562\mu&space;A\\[10pt]V_{2}=R_{2}*I_{2}=0.562*680=383mV\\[10pt]" title="\textit{Intensidad de corriente y voltaje }R_{3}\\[10pt]R_{eq}=\frac{1}{\frac{1}{680}+\frac{1}{180}}=142.32\Omega \\[10pt]I_{3}=\frac{I_{T}*R_{eq}}{R_{eq}+R_{3}}=3.84*\frac{mA*142.32}{142.32+330}=1.16mA\\[10pt]V_{3}=R_{3}*I_{3}=1.16*330=383mV\\[10pt]\textit{Intensidad de corriente y voltaje }R_{2}\\[10pt]R_{eq}=\frac{1}{\frac{1}{180}+\frac{1}{330}}=116.47\Omega \\[10pt]I_{2}=\frac{I_{T}*R_{eq}}{R_{eq}+R_{2}}=3.84*\frac{mA*116.47}{116.47+680}=562\mu A\\[10pt]V_{2}=R_{2}*I_{2}=0.562*680=383mV\\[10pt]" />

![image](https://user-images.githubusercontent.com/93739242/147988331-9e91cd77-efcc-4fd9-ad95-b40040a81d9e.png)

<img src="https://latex.codecogs.com/svg.image?R_{eq_{2,3,4,5}}=5.73k\Omega&space;\\[10pt]I_{T_{2,3,4,5}}=\frac{5}{5.73}=872\mu&space;A&space;\\[10pt]\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;de&space;R2}\\[10pt]I_{2}=\frac{I_{T_{2,3,4,5}}*R_{3}}{R_{3}&plus;R_{2}}=872*\frac{\mu&space;A*3300}{6200&plus;3300}=302\mu&space;A\\[10pt]V_{2}=R_{2}*I_{2}=302\mu&space;A*6200=1.88V\\[10pt]\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;de&space;}R_{3}\\[10pt]I_{3}=\frac{I_{T_{2,3,4,5}}*R_{2}}{R_{3}&plus;R_{2}}=872*\frac{\mu&space;A*6200}{6200&plus;3300}=569\mu&space;A\\[10pt]V_{3}=R_{3}*I_{3}=569\mu&space;A*3300=1.88V\\[10pt]" title="R_{eq_{2,3,4,5}}=5.73k\Omega \\[10pt]I_{T_{2,3,4,5}}=\frac{5}{5.73}=872\mu A \\[10pt]\textit{Intensidad de corriente y voltaje de R2}\\[10pt]I_{2}=\frac{I_{T_{2,3,4,5}}*R_{3}}{R_{3}+R_{2}}=872*\frac{\mu A*3300}{6200+3300}=302\mu A\\[10pt]V_{2}=R_{2}*I_{2}=302\mu A*6200=1.88V\\[10pt]\textit{Intensidad de corriente y voltaje de }R_{3}\\[10pt]I_{3}=\frac{I_{T_{2,3,4,5}}*R_{2}}{R_{3}+R_{2}}=872*\frac{\mu A*6200}{6200+3300}=569\mu A\\[10pt]V_{3}=R_{3}*I_{3}=569\mu A*3300=1.88V\\[10pt]" />

<img src="https://latex.codecogs.com/svg.image?\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;de&space;}R_{4}\\[10pt]I_{4}=\frac{I_{T_{2,3,4,5}}*R_{5}}{R_{4}&plus;R_{5}}=872*\frac{\mu&space;A*5600}{5600&plus;10000}=313\mu&space;A\\[10pt]V_{4}=R_{4}*I_{4}=313\mu&space;A*10000=3.13V\\[10pt]\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;de&space;}R_{5}\\[10pt]I_{5}=\frac{I_{T_{2,3,4,5}}*R_{4}}{R_{4}&plus;R_{5}}=872*\frac{\mu&space;A*10000}{10000&plus;5600}=558\mu&space;A\\[10pt]V_{5}=R_{5}*I_{5}=558\mu&space;A*5600=3.13V\\[10pt]&space;\textit{Intensidad&space;de&space;corriente&space;y&space;voltaje&space;de&space;}R_{1}\\[10pt]I_{T}=\frac{V_{T}}{R_{T}}=\frac{5}{852}=5.86mA\\[10pt]I_{1}=\frac{R_{eq_{2,3,4,5}}*I_{T}}{R_{eq_{2,3,4,5}}&plus;R_{1}}=5.86*\frac{A*5730}{1000&plus;5730}\approx&space;5A\\[10pt]V_{3}=R_{3}*I_{3}=569\mu&space;A*3300=1.88V\\[10pt]&space;" title="\textit{Intensidad de corriente y voltaje de }R_{4}\\[10pt]I_{4}=\frac{I_{T_{2,3,4,5}}*R_{5}}{R_{4}+R_{5}}=872*\frac{\mu A*5600}{5600+10000}=313\mu A\\[10pt]V_{4}=R_{4}*I_{4}=313\mu A*10000=3.13V\\[10pt]\textit{Intensidad de corriente y voltaje de }R_{5}\\[10pt]I_{5}=\frac{I_{T_{2,3,4,5}}*R_{4}}{R_{4}+R_{5}}=872*\frac{\mu A*10000}{10000+5600}=558\mu A\\[10pt]V_{5}=R_{5}*I_{5}=558\mu A*5600=3.13V\\[10pt] \textit{Intensidad de corriente y voltaje de }R_{1}\\[10pt]I_{T}=\frac{V_{T}}{R_{T}}=\frac{5}{852}=5.86mA\\[10pt]I_{1}=\frac{R_{eq_{2,3,4,5}}*I_{T}}{R_{eq_{2,3,4,5}}+R_{1}}=5.86*\frac{A*5730}{1000+5730}\approx 5A\\[10pt]V_{3}=R_{3}*I_{3}=569\mu A*3300=1.88V\\[10pt] " />






**15. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-67**

![imagen](https://user-images.githubusercontent.com/93798427/146659048-ad4cc3ec-88ef-436f-ab5c-cdeaa96018c7.png)


![imagen](https://user-images.githubusercontent.com/93798427/146659078-b85398d5-6f21-4769-a2df-94cdd2d89ccd.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659106-3e2a2c6b-9bbb-4cf7-a742-a39d0ff9edaf.png)


NODO C

![imagen](https://user-images.githubusercontent.com/93798427/146659117-212d6e69-5a59-4a72-bc97-5c278fa7cba3.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659143-8b202a41-de01-43c1-a2fe-12044ddec5b5.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659161-67980cf5-75c2-4e59-b13c-337ca68b2951.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659170-11cc0164-4c23-49a2-b541-09157821287c.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659175-ad6219a8-14a2-4544-97cc-689836c4daff.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659185-62ba5ed1-49db-4c47-9cff-7f932cc77280.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659197-29ea94f3-452b-4ebc-98a5-188002e32260.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659201-cc83e9fa-f7de-4932-93d0-bb7ab8a02199.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659202-9bffc0d2-61c7-4dd5-a741-23157f45ab70.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659225-5f6d3e20-613a-4d1b-9483-238e85b7aafc.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659229-0f36f52f-4661-4de3-a974-036cf84265f9.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659254-4b23a714-cd83-4697-981d-3678dd03f791.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659260-3159506e-af00-4c67-a89d-b5059028cf01.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659263-5f0a41cd-e14a-4396-b25d-7840d79f6778.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659283-e6fe5050-bafc-42ed-a96f-b9de03156a3b.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659294-31306b9d-f5c2-40e2-bff7-d5f4108606b0.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659302-f2e0dadf-725a-4e9a-9b65-d8ed352accd4.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659306-fb67785c-c92f-4089-a8c1-3f85edbadc4a.png)

**17. En la figura 7-68, ¿cómo determinaría el voltaje entre los extremos de R2 por medición sin conectar directamente un medidor entre los extremos del resistor?**

![image](https://user-images.githubusercontent.com/93739242/147988496-b4eea154-98a2-4a57-9f92-c7c338728771.png)

Medir el voltaje en A con respecto a tierra y el voltaje en B con respecto a tierra. La diferencia es VR2.


**21. (a) Determine el valor de R2 en la figura 7-70. (b) Encuentre la potencia en R2**

![imagen](https://user-images.githubusercontent.com/93798427/146659319-7e8ee078-f4a7-4a8e-ad68-f5aa230d5e3d.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659330-7ee3d380-9462-46b8-912e-a0290f21a0d3.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659334-8e36f463-be89-464b-8745-ed5f2cc64a53.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659336-424745fb-f49e-4b2c-b309-57307947038f.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659343-a8c95e36-8204-43c4-8124-4184f2c23283.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659349-e2a9f77e-c239-4f38-ae7f-03097ec51c10.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659357-1e8adbb6-ca67-4936-843f-e6c8e0539aca.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659380-539e8db2-122d-43e6-8e10-e30b4b81eb0d.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659386-e4c93a3c-7e4d-4819-927b-c11b73eb2b81.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659393-93643cb8-fb6f-4be5-a44b-d542e53ab081.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659398-645ff6ab-6d7d-475e-9684-8382eaf3f058.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659406-4d3d32ab-ec5b-4306-8de9-87bdfd938b5c.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659411-3a0a9d0e-67bf-41b5-8bde-01b0cc052924.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659418-8e7014ab-8f52-4142-a27e-857f3e9e5081.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659429-093f5f32-e613-4cc8-9ff1-27d974523b04.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659437-52934521-2fd0-4a54-8494-5dd8fd17f5f8.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659445-f994c1a7-ad4a-4ba2-9f71-cd88efa29c73.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659452-7d38d972-36d8-4563-bcaf-0d15b240383c.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659460-7a2a3846-05f4-4a59-bb1a-4264860f3f8c.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659471-cc92a5b9-e8f9-447c-a469-b6f7b047969b.png)

**23. Encuentre la resistencia entre cada uno de los siguientes juegos de nodos mostrados en la figura 7-72: AB, BC y CD.**

![image](https://user-images.githubusercontent.com/93739242/147988544-936ae4b8-e42b-4e0e-bbbc-7bb84e5661f3.png)

 <img src="https://latex.codecogs.com/svg.image?\textit{En&space;serie&space;}R_{1}&plus;R_{2}\\[10pt]R_{eq1}=3.3&plus;3.3=6.6k\Omega&space;\\[10pt]R_{3}\textit{&space;Paralelo&space;}&space;R_{4}=\frac{3.3*3.3}{3.3&plus;3.3}=1.65k\Omega&space;=R_{eq2}\\[10pt]&space;R_{5}\textit{&space;Paralelo&space;}&space;R_{6}=\frac{3.3*3.3}{3.3&plus;3.3}=1.65k\Omega&space;=R_{eq3}\\[10pt]&space;RAB=&space;R_{eq1}\textit{&space;Paralelo&space;}R_{eq2}=\frac{1.65*6.6}{1.65&plus;6.6}=1.32k\Omega&space;\\[10pt]RBC=&space;R_{eq1}\textit{&space;Paralelo&space;}R_{eq3}=\frac{1.65*6.6}{1.65&plus;6.6}=1.32k\Omega&space;\\[10pt]RCD=&space;0k\Omega&space;\\[10pt]&space;" title="\textit{En serie }R_{1}+R_{2}\\[10pt]R_{eq1}=3.3+3.3=6.6k\Omega \\[10pt]R_{3}\textit{ Paralelo } R_{4}=\frac{3.3*3.3}{3.3+3.3}=1.65k\Omega =R_{eq2}\\[10pt] R_{5}\textit{ Paralelo } R_{6}=\frac{3.3*3.3}{3.3+3.3}=1.65k\Omega =R_{eq3}\\[10pt] RAB= R_{eq1}\textit{ Paralelo }R_{eq2}=\frac{1.65*6.6}{1.65+6.6}=1.32k\Omega \\[10pt]RBC= R_{eq1}\textit{ Paralelo }R_{eq3}=\frac{1.65*6.6}{1.65+6.6}=1.32k\Omega \\[10pt]RCD= 0k\Omega \\[10pt] " />
 
 
 
 
 
 **27. ¿Cuál de dos cargas, una de 10 kÆ y otra de 47 kÆ, provocará una disminución más pequeña en el voltaje de salida de un divisor de voltaje dado?**
 
 ![imagen](https://user-images.githubusercontent.com/93798427/146659519-ed0d7075-2b4b-4cd1-8ddc-b29042e770db.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659528-06a9d063-ecae-41e3-a4a0-81827ed38cf9.png)

Por lo tanto será el de 47

**29. En la figura 7-74, determine el voltaje de salida con una carga de 33 kΩ conectada entre A y B.**

![image](https://user-images.githubusercontent.com/93739242/147988585-7af7524c-38b1-4795-885c-44757d97dfee.png)

<img src="https://latex.codecogs.com/svg.image?R_{ab}=R_{3}&plus;R_{2}||R_{C}\\[10pt]R_{ab}=\frac{8.3k*33k}{8.3k&plus;33k}=6.63k\Omega\\[10pt]R_{1&plus;(2&plus;3)||C}=R_{1}&plus;R_{(2&plus;3)||C}=10k\Omega&space;&plus;6.63k\Omega&space;=16.63k\Omega&space;\\[10pt]V_{ab}=(\frac{6.63k\Omega&space;}{16.63k\Omega&space;})(22V)=8.772V" title="R_{ab}=R_{3}+R_{2}||R_{C}\\[10pt]R_{ab}=\frac{8.3k*33k}{8.3k+33k}=6.63k\Omega\\[10pt]R_{1+(2+3)||C}=R_{1}+R_{(2+3)||C}=10k\Omega +6.63k\Omega =16.63k\Omega \\[10pt]V_{ab}=(\frac{6.63k\Omega }{16.63k\Omega })(22V)=8.772V" />





**33. La figura 7-76 muestra un circuito polarizador de cd para un amplificador de transistor de efecto de
campo. La polarización es un método común empleado para establecer ciertos niveles de voltaje de cd
para la operación apropiada de un amplificador. Aunque no se espera que usted conozca los amplificadores con transistores en este momento, los voltajes y las corrientes de cd presentes en el circuito pueden ser determinados con métodos ya conocidos.
(a) Encuentre VG y VS (b) Determine I1, I2, ID, e IS (c) Encuentre VDS y VDG**

![imagen](https://user-images.githubusercontent.com/93798427/146685728-28adc3fa-0a5a-4c56-9e6f-1b82c3719956.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685746-b59bec50-bd49-415b-be54-714ddd142355.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685787-31935e7b-8e54-47d7-a6bf-d3cd3b57abb2.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686001-5a87623a-10f0-438b-b348-3e618d7149ab.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686020-9548f443-7e20-4d58-a082-02db8a8b71f1.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686031-33ac2360-f3be-41ea-9082-cfcde1b95ccf.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685830-c55370e7-1fa2-4672-aab8-b52a84b84208.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685845-ca49e071-4fe6-411b-af22-f39fe4d11ad8.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685876-c7cb41d2-d703-4ce2-8770-735be75de385.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685905-660c4a39-bab4-4b50-bba4-da077aa8c391.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685930-36f09ad2-e886-48f4-8ce9-9f0c13124f60.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685947-6026f019-b95d-4ffc-a4b5-d50986e6ab91.png)

![imagen](https://user-images.githubusercontent.com/93798427/146685973-beecf8e9-e04f-4b92-be76-3ce3ef7e3853.png)

**35. ¿En cuál de los siguientes intervalos de voltaje presentará un voltímetro la mínima carga que haya en un circuito? (a) 1 V (b) 10 V (c) 100 V (d) 1000 V**

<img src="https://latex.codecogs.com/svg.image?\textit{Sensibilidad&space;tipica&space;de&space;un&space;voltimetro&space;es&space;de&space;}20000\frac{\Omega&space;}{V}\\[10pt]\textit{&space;La&space;resistencia&space;interna&space;del&space;voltimetro&space;se&space;determina&space;como}\\[10pt]\textit{producto&space;de&space;sensibilidad&space;y&space;escala&space;completa&space;lectura&space;del&space;voltimetro.}\\[10pt]\textit{Rango&space;de&space;voltaje&space;1V}\\[10pt]\textit{R.I&space;del&space;voltimetro&space;}=(20000\frac{\Omega&space;}{V})(1V)=20000\Omega&space;\\[10pt]\textit{Rango&space;de&space;voltaje&space;10V}\\[10pt]\textit{R.I&space;del&space;voltimetro&space;}=(20000\frac{\Omega&space;}{V})(10V)=200000\Omega&space;\\[10pt]\textit{Rango&space;de&space;voltaje&space;100V}\\[10pt]\textit{R.I&space;del&space;voltimetro&space;}=(20000\frac{\Omega&space;}{V})(100V)=2000000\Omega&space;\\[10pt]\textit{Rango&space;de&space;voltaje&space;1000V}\\[10pt]\textit{R.I&space;del&space;voltimetro&space;}=(20000\frac{\Omega&space;}{V})(1000V)=20000000\Omega&space;\\[10pt]&space;&space;" title="\textit{Sensibilidad tipica de un voltimetro es de }20000\frac{\Omega }{V}\\[10pt]\textit{ La resistencia interna del voltimetro se determina como}\\[10pt]\textit{producto de sensibilidad y escala completa lectura del voltimetro.}\\[10pt]\textit{Rango de voltaje 1V}\\[10pt]\textit{R.I del voltimetro }=(20000\frac{\Omega }{V})(1V)=20000\Omega \\[10pt]\textit{Rango de voltaje 10V}\\[10pt]\textit{R.I del voltimetro }=(20000\frac{\Omega }{V})(10V)=200000\Omega \\[10pt]\textit{Rango de voltaje 100V}\\[10pt]\textit{R.I del voltimetro }=(20000\frac{\Omega }{V})(100V)=2000000\Omega \\[10pt]\textit{Rango de voltaje 1000V}\\[10pt]\textit{R.I del voltimetro }=(20000\frac{\Omega }{V})(1000V)=20000000\Omega \\[10pt] " />

Debido a que la resistencia interna es mayor, puede evitar el efecto de carga del circuito. Por lo tanto, el voltímetro que tiene un rango de 1000V puede proporcionar una carga mínima en un circuito.






**39. Para el circuito mostrado en la figura 7-77, calcule:
(a) La resistencia total entre las terminales de la fuente (b) La corriente total suministrada por la fuente**

![imagen](https://user-images.githubusercontent.com/93798427/146686128-4ca06bd8-32d9-42ad-8f05-4369d3306ccb.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686143-45677d0d-44e1-48f1-9228-84fe8bc56190.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686164-39f1c0c2-6366-43b0-870b-9201055573d4.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686175-39665365-ff19-4ef2-8491-6202ba5faeaa.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686202-6293e79d-eb9b-4157-a3db-69957c90d9cc.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686220-3f9417c1-6962-47d6-a163-cc335b2dd2ea.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686234-62a379a8-2be8-4d21-9d7b-297071e0b4f2.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686291-a96ea46c-1cea-4406-a62e-52b2dd772815.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686267-49f15e26-e12b-4b91-bb1f-0617a382ec77.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686316-84b280e4-aee7-4e4a-b849-07302ab3f182.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686321-0ca4b288-de55-4b1d-a3fd-5b5329f7f712.png)

![imagen](https://user-images.githubusercontent.com/93798427/146686328-b1821e3a-ced0-4dc1-bf03-5f558a02696e.png)

**41. Determine la resistencia total entre las terminales A y B de la red en escalera de la figura 7-79. Asimismo, calcule la corriente en cada rama con 10V entre A y B.**

![image](https://user-images.githubusercontent.com/93739242/147988653-d3a0d1d8-6471-4c97-b506-305e2e523efe.png)

<img src="https://latex.codecogs.com/svg.image?R_{1}=R100\Omega&space;&plus;R680\Omega&space;&plus;R100\Omega&space;=880\Omega&space;\\[10pt]" title="R_{1}=R100\Omega +R680\Omega +R100\Omega =880\Omega \\[10pt]" />

<img src="https://latex.codecogs.com/svg.image?R_{2}=R820\Omega&space;||R880\Omega&space;\\[10pt]R_{2}=\frac{(820\Omega&space;)(880\Omega&space;)}{820\Omega&space;&plus;880\Omega&space;}&space;=424.47\Omega&space;\\[10pt]" title="R_{2}=R820\Omega ||R880\Omega \\[10pt]R_{2}=\frac{(820\Omega )(880\Omega )}{820\Omega +880\Omega } =424.47\Omega \\[10pt]" />

<img src="https://latex.codecogs.com/svg.image?R_{3}=R220\Omega&space;&plus;R220\Omega&space;&plus;R424.47\Omega=864.47\Omega&space;" title="R_{3}=R220\Omega +R220\Omega +R424.47\Omega=864.47\Omega " />

<img src="https://latex.codecogs.com/svg.image?R_{4}=R820\Omega&space;||R864.47\Omega&space;\\[10pt]R_{4}=\frac{(820\Omega&space;)(864.47\Omega&space;&space;)}{820\Omega&space;&plus;864.47\Omega&space;&space;}&space;=420.82\Omega&space;\\[10pt]" title="R_{4}=R820\Omega ||R864.47\Omega \\[10pt]R_{4}=\frac{(820\Omega )(864.47\Omega )}{820\Omega +864.47\Omega } =420.82\Omega \\[10pt]" />

<img src="https://latex.codecogs.com/svg.image?R_{5}=R420.82\Omega&space;&plus;R100\Omega&space;&plus;R100\Omega&space;\approx&space;621\Omega&space;" title="R_{5}=R420.82\Omega +R100\Omega +R100\Omega \approx 621\Omega " />





**45. Repita el problema 44 para las siguientes condiciones
(a) SW3 y SW4 conectados a 12 V, SW1 y SW2 a tierra
(b) SW3 y SW1 conectados a 12 V, SW2 y SW4 a tierra
(c) Todos los interruptores conectados a 12 V**


![imagen](https://user-images.githubusercontent.com/93798427/146817781-3fcc3ad5-7ce2-4cc5-b83b-a652677eca94.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817807-dd831cca-efb0-4049-8ab0-9efded9d5ce8.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817831-22811d07-67e7-470d-aa85-2b55d3d73970.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817856-2151e5af-b82c-4fa4-bea7-7eee622c45c9.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817890-e93e4c68-8259-40c6-abc3-8acc77faab7a.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817927-6aed09f7-00b0-477e-8471-da0fd841ac89.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817961-9473af65-9ba7-4898-8b24-33956b3bf2be.png)

**47. Una celda de carga tiene cuatro medidores de deformación idénticos con una resistencia ilimitada de 120,000 Ω para cada medidor (un valor estándar). Cuando se agrega una carga, los medidores a tensión incrementan su resistencia en 60 mΩ, a 120,060 Ω, y los medidores a compresión disminuyen su resistencia en 60 mΩ, a 119.940 Ω, como se muestra en la figura 7-82. ¿Cuál es el voltaje de salida con carga?**

![image](https://user-images.githubusercontent.com/93739242/147988703-158c454c-c03e-41a8-8c54-73eab15d299a.png)

<img src="https://latex.codecogs.com/svg.image?\textit{Resistencia&space;de&space;los&space;medidores}\\[10pt]SG1=SG4=120060\Omega&space;\textit{&space;Medidores&space;a&space;tension}&space;\\[10pt]SG2=SG3=119940\Omega&space;\textit{&space;Medidores&space;a&space;compresion}\\[10pt]V_{Salida}=V_{B}\frac{SG_{4}}{SG_{4}&plus;SG_{2}}-V_{B}\frac{SG_{3}}{SG_{3}&plus;SG_{1}}\\[10pt]V_{Salida}=\frac{120060}{\:240000}*&space;12-\frac{119940}{\:240000}*12=6mV" title="\textit{Resistencia de los medidores}\\[10pt]SG1=SG4=120060\Omega \textit{ Medidores a tension} \\[10pt]SG2=SG3=119940\Omega \textit{ Medidores a compresion}\\[10pt]V_{Salida}=V_{B}\frac{SG_{4}}{SG_{4}+SG_{2}}-V_{B}\frac{SG_{3}}{SG_{3}+SG_{1}}\\[10pt]V_{Salida}=\frac{120060}{\:240000}* 12-\frac{119940}{\:240000}*12=6mV" />




**51. En la figura 7-86 hay una falla. Con base en las indicaciones del medidor, determine cuál es la falla.**

![imagen](https://user-images.githubusercontent.com/93798427/146686391-2a8c4109-5403-40ec-b0c2-898f7431aedd.png)

La resistencia R3 está abierta.

**53. Revise las lecturas de los medidores de la figura 7-88 y localice cualquier falla que pudiera existir.**

![image](https://user-images.githubusercontent.com/93739242/147988798-2de75b8c-e9fc-4387-adb8-827d28b7e1f2.png)

<img src="https://latex.codecogs.com/svg.image?V_{A}=(\frac{R_{3}}{R_{1}&plus;R_{2}&plus;R_{3}})V_{S}=(\frac{2.2&space;k\Omega&space;}{4.2&space;k\Omega&space;})10&space;V=5.24V\\" title="V_{A}=(\frac{R_{3}}{R_{1}+R_{2}+R_{3}})V_{S}=(\frac{2.2 k\Omega }{4.2 k\Omega })10 V=5.24V\\" />

La lectura del voltímetro A es correcta. Esto indica que R1, R2 Y R3 están conectados y que no están defectuosos

<img src="https://latex.codecogs.com/svg.image?R_{2&plus;3||4}=\frac{R_{2&plus;3}*R_{4}}{R_{2&plus;3}&plus;R_{4}}=\frac{(3.2k\Omega&space;)(3.3k\Omega&space;)}{6.5k\Omega&space;}=1.62k\Omega\\[10pt]&space;V_{2&plus;3||4}=(\frac{R_{2&plus;3||4}}{R_{1}&plus;R_{2&plus;3||4}}V_{s})=(\frac{1.62k\Omega}{2.62k\Omega}10V)=6.18V" title="R_{2+3||4}=\frac{R_{2+3}*R_{4}}{R_{2+3}+R_{4}}=\frac{(3.2k\Omega )(3.3k\Omega )}{6.5k\Omega }=1.62k\Omega\\[10pt] V_{2+3||4}=(\frac{R_{2+3||4}}{R_{1}+R_{2+3||4}}V_{s})=(\frac{1.62k\Omega}{2.62k\Omega}10V)=6.18V" />

Este calculo muestra que la lectura del medidor no es correcta lo que quiere decir que R4 puede que este abierto.

<img src="https://latex.codecogs.com/svg.image?V_{4}=(\frac{R_{2&plus;3}}{R_{1}&plus;R_{2&plus;3}}*V_{s})=(\frac{3.2k\Omega&space;}{4.2k\Omega&space;}*10V)=7.62V" title="V_{4}=(\frac{R_{2+3}}{R_{1}+R_{2+3}}*V_{s})=(\frac{3.2k\Omega }{4.2k\Omega }*10V)=7.62V" />

Por lo tanto, se demuestra que el resistor de 3.3 kΩ (R4) está abierto.




## Capitulo 8 ##

**3. Una batería tipo D nueva tiene entre sus terminales un voltaje de 1.6 V y puede suministrar hasta 8.0 A
a un cortocircuito durante muy poco tiempo. ¿Cuál es la resistencia interna de la batería?**

![imagen](https://user-images.githubusercontent.com/93798427/146659591-363dc52a-88b2-47fb-955c-bd6e32816626.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659597-f4461fe4-8327-411e-a50d-5373216f14a4.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659604-be86446a-6f00-437b-a925-306aed2fd931.png)

**5. Una fuente de corriente tiene una IS de 600 mA y una RS de 1.2 kΩ. Conviértala en una fuente de voltaje equivalente.**


El voltaje de la fuente es:


<img src="https://latex.codecogs.com/svg.image?\\V_{s}=I_{s}R_{s}=(600mA)(1.2k\Omega&space;)=720V\\[10pt]\textit{La&space;resistencia&space;es&space;la&space;misma&space;para&space;la&space;fuente&space;de&space;corriente&space;y&space;la&space;fuente&space;de&space;voltaje.}\\[10pt]R=1.2k\Omega&space;" title="\\V_{s}=I_{s}R_{s}=(600mA)(1.2k\Omega )=720V\\[10pt]\textit{La resistencia es la misma para la fuente de corriente y la fuente de voltaje.}\\[10pt]R=1.2k\Omega " />





**9. Con el teorema de superposición, determine la corriente a través de R3 en la figura 8-70.**

![imagen](https://user-images.githubusercontent.com/93798427/146816397-303826f4-b193-4238-a1aa-33bd95070204.png)

![imagen](https://user-images.githubusercontent.com/93798427/146816743-d84b380a-9a9e-43a1-a2d3-f709fcfd0e0a.png)

![imagen](https://user-images.githubusercontent.com/93798427/146816535-fed54dfe-48be-4afe-9bf7-0181624d6e41.png)

![imagen](https://user-images.githubusercontent.com/93798427/146816641-8fe7a44d-4137-4020-be47-b2d8629feecd.png)

![imagen](https://user-images.githubusercontent.com/93798427/146816847-faa00a50-2420-4fbd-8455-82ad42025448.png)

![imagen](https://user-images.githubusercontent.com/93798427/146816998-b57614d2-618b-42ab-b113-8e4e8bf6b887.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817081-77b13d41-589c-4dd9-bbb7-6fed225fc903.png)

![imagen](https://user-images.githubusercontent.com/93798427/146817144-c66f3b38-d11e-4b6d-9354-5930b5ffd828.png)

**11. En la figura 8-72 se muestra un circuito comparador. El voltaje de entrada, VENTRADA, se compara con el voltaje de referencia, VREFERENCIA, y se genera una salida negativa si VREFERENCIA > VENTRADA; de lo contrario es positiva. El comparador no carga a una u otra entrada. Si R2 es de 1.0 kΩ, ¿cuál es el intervalo del voltaje de referencia?**

![image](https://user-images.githubusercontent.com/93739242/147988951-6b1c7947-1f19-4dc7-86dd-4c4f33abcce1.png)

La tensión mínima para la tensión de referencia significa solo caída a través de la resistencia R3.
<img src="https://latex.codecogs.com/svg.image?\\V_{REF_{min}}=(\frac{R_{3}}{R_{1}&plus;R_{2}&plus;R_{3}})(30V)-15V\\[10pt]=(\frac{6.8k\Omega&space;}{4.7k\Omega&space;&plus;1k\Omega&space;&plus;6.8k\Omega&space;})(30V)-15V\\[10pt]=(\frac{6.8k\Omega&space;}{12.5k\Omega&space;})(30V)-15V=16.32V-15V=1.32V" title="\\V_{REF_{min}}=(\frac{R_{3}}{R_{1}+R_{2}+R_{3}})(30V)-15V\\[10pt]=(\frac{6.8k\Omega }{4.7k\Omega +1k\Omega +6.8k\Omega })(30V)-15V\\[10pt]=(\frac{6.8k\Omega }{12.5k\Omega })(30V)-15V=16.32V-15V=1.32V" />

El voltaje máximo para el voltaje de referencia significa caída a través de las resistencias R2 y R3 solamente.

<img src="https://latex.codecogs.com/svg.image?\\V_{REF_{max}}=(\frac{R_{2}&plus;R_{3}}{R_{1}&plus;R_{2}&plus;R_{3}})(30V)-15V\\[10pt]=(\frac{1k\Omega&space;&plus;6.8k\Omega&space;}{4.7k\Omega&space;&plus;1k\Omega&space;&plus;6.8k\Omega&space;})(30V)-15V\\[10pt]=(\frac{7.8k\Omega&space;}{12.5k\Omega&space;})(30V)-15V=18.72V-15V=3.72V" title="\\V_{REF_{max}}=(\frac{R_{2}+R_{3}}{R_{1}+R_{2}+R_{3}})(30V)-15V\\[10pt]=(\frac{1k\Omega +6.8k\Omega }{4.7k\Omega +1k\Omega +6.8k\Omega })(30V)-15V\\[10pt]=(\frac{7.8k\Omega }{12.5k\Omega })(30V)-15V=18.72V-15V=3.72V" />




**15. La figura 8-75 muestra dos redes en escalera. Determine la corriente producida por cada una de las baterías cuando se conectan las terminales A (A a A) y las terminales B (B a B).**

![imagen](https://user-images.githubusercontent.com/93798427/146808951-66266b3c-66b8-462a-b0b2-a8dea001cd36.png)

![imagen](https://user-images.githubusercontent.com/93798427/146809127-75cd577d-66ff-4192-b3c9-a6f7aea66775.png)

![imagen](https://user-images.githubusercontent.com/93798427/146809213-2057bd49-5e3c-4051-a764-e7fa0b5e5e0d.png)

![imagen](https://user-images.githubusercontent.com/93798427/146809883-dd1da628-19c8-4d86-b6d3-9998a20e5ba2.png)

![imagen](https://user-images.githubusercontent.com/93798427/146809974-a4f7af05-2de4-4a14-a298-1fcf42fd32bf.png)

![imagen](https://user-images.githubusercontent.com/93798427/146810052-d12e337c-9d00-4815-9735-fde4d874cf1b.png)

![imagen](https://user-images.githubusercontent.com/93798427/146810285-fa073d35-7fb2-4a25-ad19-fa02aa5c250f.png)

![imagen](https://user-images.githubusercontent.com/93798427/146810349-eb48cab9-2692-48fe-9432-60ff4aac5105.png)

![imagen](https://user-images.githubusercontent.com/93798427/146810495-7aa473be-385c-40a3-99ad-d82da51c19dd.png)

![imagen](https://user-images.githubusercontent.com/93798427/146810598-edf868e0-62ed-4795-a2d1-f655ea68220a.png)

![imagen](https://user-images.githubusercontent.com/93798427/146810669-20f5ada6-160e-4338-8e5c-2e429f7c8ec2.png)

![imagen](https://user-images.githubusercontent.com/93798427/146810907-6ea17f74-005d-494a-9eb7-e6578d3260a1.png)

![imagen](https://user-images.githubusercontent.com/93798427/146811021-87805d77-3f42-43c8-b0c3-d7c6fe381dbf.png)

![imagen](https://user-images.githubusercontent.com/93798427/146811204-572c1bb6-f21a-4461-8f6b-e031130f1f56.png)

![imagen](https://user-images.githubusercontent.com/93798427/146811282-ce5d3d9e-1bc3-4151-a0f5-1893caea836f.png)

![imagen](https://user-images.githubusercontent.com/93798427/146811341-9f8103ef-0e09-4e62-8adb-2e786f94af6d.png)

![imagen](https://user-images.githubusercontent.com/93798427/146811829-e2103106-5193-4e23-8a00-6827d06bf9fb.png)

![imagen](https://user-images.githubusercontent.com/93798427/146813172-0b138742-6764-4a8a-b3a3-73ff13528c72.png)

![imagen](https://user-images.githubusercontent.com/93798427/146813270-279e0b6e-5d04-4ad8-8c8c-c2ed7af2e64b.png)

![imagen](https://user-images.githubusercontent.com/93798427/146813413-aecd919c-af93-48ad-9350-8170fa9b7bdf.png)

![imagen](https://user-images.githubusercontent.com/93798427/146813475-363b81cb-5964-47ec-9edb-92e46f187037.png)

**17. Con el teorema de Thevenin, determine la corriente a través de la carga RL en la figura 8-77.**

![image](https://user-images.githubusercontent.com/93739242/147988985-0e4a156a-bf36-4ae2-a342-b9011b4b3f2b.png)

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{TH}}&space;&=\{[((10&space;\mathrm{k}&space;\Omega)&space;\|(5.6&space;\mathrm{k}&space;\Omega))&plus;(10&space;\mathrm{k}&space;\Omega)]&space;\|(5.6&space;\mathrm{k}&space;\Omega)\}&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=\left\{\left[\left(\frac{(5.6&space;\mathrm{k}&space;\Omega)(10&space;\mathrm{k}&space;\Omega)}{(5.6&space;\mathrm{k}&space;\Omega)&plus;(10&space;\mathrm{k}&space;\Omega)}\right)&plus;(10&space;\mathrm{k}&space;\Omega)\right]&space;\|(5.6&space;\mathrm{k}&space;\Omega)\right\}&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=\{[(3.59&space;\mathrm{k}&space;\Omega)&plus;(10&space;\mathrm{k}&space;\Omega)]&space;\|(5.6&space;\mathrm{k}&space;\Omega)\}&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=\{(13.59&space;\mathrm{k}&space;\Omega)&space;\|(5.6&space;\mathrm{k}&space;\Omega)\}&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=\left(\frac{(13.59&space;\mathrm{k}&space;\Omega)(5.6&space;\mathrm{k}&space;\Omega)}{(13.59&space;\mathrm{k}&space;\Omega)&plus;(5.6&space;\mathrm{k}&space;\Omega)}\right)&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=(3.96&space;\mathrm{k}&space;\Omega)&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]R_{\mathrm{TH}}&space;&=13.96&space;\mathrm{k}&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{TH}} &=\{[((10 \mathrm{k} \Omega) \|(5.6 \mathrm{k} \Omega))+(10 \mathrm{k} \Omega)] \|(5.6 \mathrm{k} \Omega)\}+(10 \mathrm{k} \Omega) \\[10pt]&=\left\{\left[\left(\frac{(5.6 \mathrm{k} \Omega)(10 \mathrm{k} \Omega)}{(5.6 \mathrm{k} \Omega)+(10 \mathrm{k} \Omega)}\right)+(10 \mathrm{k} \Omega)\right] \|(5.6 \mathrm{k} \Omega)\right\}+(10 \mathrm{k} \Omega) \\[10pt]&=\{[(3.59 \mathrm{k} \Omega)+(10 \mathrm{k} \Omega)] \|(5.6 \mathrm{k} \Omega)\}+(10 \mathrm{k} \Omega) \\[10pt]&=\{(13.59 \mathrm{k} \Omega) \|(5.6 \mathrm{k} \Omega)\}+(10 \mathrm{k} \Omega) \\[10pt]&=\left(\frac{(13.59 \mathrm{k} \Omega)(5.6 \mathrm{k} \Omega)}{(13.59 \mathrm{k} \Omega)+(5.6 \mathrm{k} \Omega)}\right)+(10 \mathrm{k} \Omega) \\[10pt]&=(3.96 \mathrm{k} \Omega)+(10 \mathrm{k} \Omega) \\[10pt]R_{\mathrm{TH}} &=13.96 \mathrm{k} \Omega\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{EQU}}&space;&=[((5.6&space;\mathrm{k}&space;\Omega)&plus;(10&space;\mathrm{k}&space;\Omega))&space;\|(5.6&space;\mathrm{k}&space;\Omega)]&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=[(15.6&space;\mathrm{k}&space;\Omega)&space;\|(5.6&space;\mathrm{k}&space;\Omega)]&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=\left(\frac{(15.6&space;\mathrm{k}&space;\Omega)(5.6&space;\mathrm{k}&space;\Omega)}{(15.6&space;\mathrm{k}&space;\Omega)&plus;(5.6&space;\mathrm{k}&space;\Omega)}\right)&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]&=(4.12&space;\mathrm{k}&space;\Omega)&plus;(10&space;\mathrm{k}&space;\Omega)&space;\\[10pt]R_{\mathrm{EQU}}&space;&=(14.12&space;\mathrm{k}&space;\Omega)\end{aligned}" title="\begin{aligned}R_{\mathrm{EQU}} &=[((5.6 \mathrm{k} \Omega)+(10 \mathrm{k} \Omega)) \|(5.6 \mathrm{k} \Omega)]+(10 \mathrm{k} \Omega) \\[10pt]&=[(15.6 \mathrm{k} \Omega) \|(5.6 \mathrm{k} \Omega)]+(10 \mathrm{k} \Omega) \\[10pt]&=\left(\frac{(15.6 \mathrm{k} \Omega)(5.6 \mathrm{k} \Omega)}{(15.6 \mathrm{k} \Omega)+(5.6 \mathrm{k} \Omega)}\right)+(10 \mathrm{k} \Omega) \\[10pt]&=(4.12 \mathrm{k} \Omega)+(10 \mathrm{k} \Omega) \\[10pt]R_{\mathrm{EQU}} &=(14.12 \mathrm{k} \Omega)\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}I_{\mathrm{S}}&space;&=\frac{V_{\mathrm{S}}}{R_{\mathrm{EQU}}}&space;=\frac{32&space;\mathrm{~V}}{14.12&space;\mathrm{k}&space;\Omega}&space;\to&space;I_{\mathrm{S}}&space;=2.26&space;\mathrm{~mA}\end{aligned}" title="\begin{aligned}I_{\mathrm{S}} &=\frac{V_{\mathrm{S}}}{R_{\mathrm{EQU}}} =\frac{32 \mathrm{~V}}{14.12 \mathrm{k} \Omega} \to I_{\mathrm{S}} =2.26 \mathrm{~mA}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}I_{5.6&space;\mathrm{k}&space;\Omega}&space;&=\left(\frac{(5.6&space;\mathrm{k}&space;\Omega)}{(5.6&space;\mathrm{k}&space;\Omega)&plus;(10&space;\mathrm{k}&space;\Omega)&plus;(5.6&space;\mathrm{k}&space;\Omega)}\right)&space;I_{\mathrm{s}}&space;\\&=\left(\frac{(5.6&space;\mathrm{k}&space;\Omega)}{(5.6&space;\mathrm{k}&space;\Omega)}\right)(2.26&space;\mathrm{~mA})&space;\\I_{5.6&space;\mathrm{k}&space;\Omega}&space;&=0.59&space;\mathrm{~mA}\end{aligned}" title="\begin{aligned}I_{5.6 \mathrm{k} \Omega} &=\left(\frac{(5.6 \mathrm{k} \Omega)}{(5.6 \mathrm{k} \Omega)+(10 \mathrm{k} \Omega)+(5.6 \mathrm{k} \Omega)}\right) I_{\mathrm{s}} \\&=\left(\frac{(5.6 \mathrm{k} \Omega)}{(5.6 \mathrm{k} \Omega)}\right)(2.26 \mathrm{~mA}) \\I_{5.6 \mathrm{k} \Omega} &=0.59 \mathrm{~mA}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}V_{T&space;H}&space;&=I_{5.6&space;\mathrm{k}&space;\Omega}(5.6&space;\mathrm{k}&space;\Omega)=(0.59&space;\mathrm{~mA})(5.6&space;\mathrm{k}&space;\Omega)\to&space;V_{T&space;H}&space;=3.34&space;\mathrm{~V}\end{aligned}" title="\begin{aligned}V_{T H} &=I_{5.6 \mathrm{k} \Omega}(5.6 \mathrm{k} \Omega)=(0.59 \mathrm{~mA})(5.6 \mathrm{k} \Omega)\to V_{T H} =3.34 \mathrm{~V}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{L}&space;&=\frac{3.34&space;\mathrm{~V}}{(13.96&space;\mathrm{k}&space;\Omega)&plus;(15&space;\mathrm{k}&space;\Omega)}&space;\\&=\frac{3.34&space;\mathrm{~V}}{28.96&space;\mathrm{k}&space;\Omega}R_{L}&space;=115.3&space;\mu&space;\mathrm{A}\end{aligned}" title="\begin{aligned}R_{L} &=\frac{3.34 \mathrm{~V}}{(13.96 \mathrm{k} \Omega)+(15 \mathrm{k} \Omega)} \\&=\frac{3.34 \mathrm{~V}}{28.96 \mathrm{k} \Omega}R_{L} =115.3 \mu \mathrm{A}\end{aligned}" />





**21. Determine la corriente a través del resistor de carga en el circuito puente de la figura 8-81**

![imagen](https://user-images.githubusercontent.com/93798427/146813689-c170f0d1-fd8d-48cc-bcc0-7f737b28842f.png)

![imagen](https://user-images.githubusercontent.com/93798427/146814005-eb9776c8-7a52-4b34-bc9b-6ccf122bde14.png)

![imagen](https://user-images.githubusercontent.com/93798427/146814096-a6811fc8-8aac-4396-8965-6ac67ac90362.png)

![imagen](https://user-images.githubusercontent.com/93798427/146814186-e820caa4-808f-49ea-a235-5e4c4db5b287.png)

![imagen](https://user-images.githubusercontent.com/93798427/146814331-22575f46-58b7-4d65-ab91-952b345db553.png)

![imagen](https://user-images.githubusercontent.com/93798427/146814459-2a9bae7e-5780-47d1-844f-329a9628dc15.png)

![imagen](https://user-images.githubusercontent.com/93798427/146814500-122af5a3-7918-43a3-98ae-98f6bd4780fd.png)

![imagen](https://user-images.githubusercontent.com/93798427/146814667-2fc7ef0c-f797-480e-b080-8031be9eb743.png)

**23. Para cada uno de los circuitos mostrados en la figura 8-76, determine el equivalente Norton visto por RL.**

![image](https://user-images.githubusercontent.com/93739242/147989031-694a5d13-b733-4bb0-89eb-5630bde779ed.png)

![image](https://user-images.githubusercontent.com/93739242/147989037-e3a6c493-8c65-416c-b3cc-a19721ea3616.png)

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{T}}&space;&=(100&space;\Omega)&plus;(47&space;\Omega)&plus;((75&space;\Omega)&space;\|(27&space;\Omega))&space;\\&=(100&space;\Omega)&plus;(47&space;\Omega)&plus;\left(\frac{(75&space;\Omega)(27&space;\Omega)}{(75&space;\Omega)&plus;(27&space;\Omega)}\right)&space;\\&=(100&space;\Omega)&plus;(47&space;\Omega)&plus;\left(\frac{(75&space;\Omega)(27&space;\Omega)}{(102&space;\Omega)}\right)&space;\\&=(100&space;\Omega)&plus;(47&space;\Omega)&plus;(19.85&space;\Omega)&space;\\R_{\mathrm{T}}&space;&=166.85&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{T}} &=(100 \Omega)+(47 \Omega)+((75 \Omega) \|(27 \Omega)) \\&=(100 \Omega)+(47 \Omega)+\left(\frac{(75 \Omega)(27 \Omega)}{(75 \Omega)+(27 \Omega)}\right) \\&=(100 \Omega)+(47 \Omega)+\left(\frac{(75 \Omega)(27 \Omega)}{(102 \Omega)}\right) \\&=(100 \Omega)+(47 \Omega)+(19.85 \Omega) \\R_{\mathrm{T}} &=166.85 \Omega\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}I_{\mathrm{T}}&space;&=\frac{V_{\mathrm{S}}}{R_{\mathrm{T}}}=\frac{25&space;\mathrm{~V}}{166.85&space;\Omega}\to&space;I_{\mathrm{T}}&space;=149.83&space;\mathrm{~mA}\end{aligned}" title="\begin{aligned}I_{\mathrm{T}} &=\frac{V_{\mathrm{S}}}{R_{\mathrm{T}}}=\frac{25 \mathrm{~V}}{166.85 \Omega}\to I_{\mathrm{T}} =149.83 \mathrm{~mA}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}I_{\mathrm{N}}&space;&=\left(\frac{75&space;\Omega}{(75&space;\Omega)&plus;(27&space;\Omega)}\right)&space;I_{\mathrm{T}}&space;=\left(\frac{(75&space;\Omega)}{(102&space;\Omega)}\right)(149.83&space;\mathrm{~mA})\to&space;I_{\mathrm{N}}&space;=110.16&space;\mathrm{~mA}\end{aligned}" title="\begin{aligned}I_{\mathrm{N}} &=\left(\frac{75 \Omega}{(75 \Omega)+(27 \Omega)}\right) I_{\mathrm{T}} =\left(\frac{(75 \Omega)}{(102 \Omega)}\right)(149.83 \mathrm{~mA})\to I_{\mathrm{N}} =110.16 \mathrm{~mA}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{N}}&space;&=[((100&space;\Omega)&plus;(47&space;\Omega))&space;\|(75&space;\Omega)]&plus;27&space;\Omega&space;\\&=[(147&space;\Omega)&space;\|(75&space;\Omega)]&plus;27&space;\Omega&space;\\&=\left(\frac{(147&space;\Omega)(75&space;\Omega)}{(147&space;\Omega)&plus;(75&space;\Omega)}\right)&plus;27&space;\Omega&space;\\&=\left(\frac{(147&space;\Omega)(75&space;\Omega)}{222&space;\Omega}\right)&plus;27&space;\Omega&space;\\&=49.66&space;\Omega&plus;27&space;\Omega&space;\\R_{\mathrm{N}}&space;&=76.66&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{N}} &=[((100 \Omega)+(47 \Omega)) \|(75 \Omega)]+27 \Omega \\&=[(147 \Omega) \|(75 \Omega)]+27 \Omega \\&=\left(\frac{(147 \Omega)(75 \Omega)}{(147 \Omega)+(75 \Omega)}\right)+27 \Omega \\&=\left(\frac{(147 \Omega)(75 \Omega)}{222 \Omega}\right)+27 \Omega \\&=49.66 \Omega+27 \Omega \\R_{\mathrm{N}} &=76.66 \Omega\end{aligned}" />

![image](https://user-images.githubusercontent.com/93739242/147989059-aaede3e2-b302-4ac9-999e-551cc414a539.png)

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}&R_{T}=270\Omega&space;\\&I_{\mathrm{N}}=\frac{3&space;\mathrm{~V}}{270&space;\Omega}&space;\\&I_{\mathrm{N}}=11.11&space;\mathrm{~mA}\end{aligned}" title="\begin{aligned}&R_{T}=270\Omega \\&I_{\mathrm{N}}=\frac{3 \mathrm{~V}}{270 \Omega} \\&I_{\mathrm{N}}=11.11 \mathrm{~mA}\end{aligned}" />

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{N}}&space;&=(10&space;\Omega)&space;\|(270&space;\Omega)&space;\\&=\left(\frac{(10&space;\Omega)(270&space;\Omega)}{(10&space;\Omega)&plus;(270&space;\Omega)}\right)&space;\\&=\left(\frac{(10&space;\Omega)(270&space;\Omega)}{(280&space;\Omega)}\right)&space;\\R_{\mathrm{N}}&space;&=9.64&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{N}} &=(10 \Omega) \|(270 \Omega) \\&=\left(\frac{(10 \Omega)(270 \Omega)}{(10 \Omega)+(270 \Omega)}\right) \\&=\left(\frac{(10 \Omega)(270 \Omega)}{(280 \Omega)}\right) \\R_{\mathrm{N}} &=9.64 \Omega\end{aligned}" />

![image](https://user-images.githubusercontent.com/93739242/147989080-6ad6a81e-d65f-467c-a51e-2ae3a29fc44e.png)

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{T}}&space;&=100&space;\mathrm{k}&space;\Omega&plus;((56&space;\mathrm{k}&space;\Omega)&space;\|(0&space;\Omega))&space;=100&space;\mathrm{k}&space;\Omega&plus;\left(\frac{(56&space;\mathrm{k}&space;\Omega)(0&space;\Omega)}{(56&space;\mathrm{k}&space;\Omega)&plus;(0&space;\Omega)}\right)\rightarrow&space;R_{\mathrm{T}}&space;=100&space;\mathrm{k}&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{T}} &=100 \mathrm{k} \Omega+((56 \mathrm{k} \Omega) \|(0 \Omega)) =100 \mathrm{k} \Omega+\left(\frac{(56 \mathrm{k} \Omega)(0 \Omega)}{(56 \mathrm{k} \Omega)+(0 \Omega)}\right)\rightarrow R_{\mathrm{T}} =100 \mathrm{k} \Omega\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}I_{\mathrm{N}}&space;&=\frac{15&space;\mathrm{~V}-10&space;\mathrm{~V}}{100&space;\mathrm{k}&space;\Omega}&space;=\frac{5&space;\mathrm{~V}}{100&space;\mathrm{k}&space;\Omega}&space;\to&space;I_{\mathrm{N}}&space;=50&space;\mu&space;\mathrm{A}\end{aligned}" title="\begin{aligned}I_{\mathrm{N}} &=\frac{15 \mathrm{~V}-10 \mathrm{~V}}{100 \mathrm{k} \Omega} =\frac{5 \mathrm{~V}}{100 \mathrm{k} \Omega} \to I_{\mathrm{N}} =50 \mu \mathrm{A}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{N}}&space;&=(100&space;\mathrm{k}&space;\Omega)&space;\|(56&space;\mathrm{k}&space;\Omega)=\left(\frac{(100&space;\mathrm{k}&space;\Omega)(56&space;\mathrm{k}&space;\Omega)}{(100&space;\mathrm{k}&space;\Omega)&plus;(56&space;\mathrm{k}&space;\Omega)}\right)\to&space;R_{\mathrm{N}}&space;=35.89&space;\mathrm{k}&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{N}} &=(100 \mathrm{k} \Omega) \|(56 \mathrm{k} \Omega)=\left(\frac{(100 \mathrm{k} \Omega)(56 \mathrm{k} \Omega)}{(100 \mathrm{k} \Omega)+(56 \mathrm{k} \Omega)}\right)\to R_{\mathrm{N}} =35.89 \mathrm{k} \Omega\end{aligned}" />

![image](https://user-images.githubusercontent.com/93739242/147989120-b4102e0d-f23f-4001-90ab-73b02310f392.png)

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}I_{\mathrm{N}}&space;&=\left(\frac{(2.2&space;\mathrm{k}&space;\Omega)}{(2.2&space;\mathrm{k}&space;\Omega)&plus;(1.0&space;\mathrm{k}&space;\Omega)}\right)(0.1&space;\mathrm{~A})&space;\\&=\left(\frac{(2.2&space;\mathrm{k}&space;\Omega)}{(3.2&space;\mathrm{k}&space;\Omega)}\right)(0.1&space;\mathrm{~A})&space;\\&=(0.06875)(0.1&space;\mathrm{~A})&space;\\I_{\mathrm{N}}&space;&=68.75&space;\mathrm{~mA}\end{aligned}" title="\begin{aligned}I_{\mathrm{N}} &=\left(\frac{(2.2 \mathrm{k} \Omega)}{(2.2 \mathrm{k} \Omega)+(1.0 \mathrm{k} \Omega)}\right)(0.1 \mathrm{~A}) \\&=\left(\frac{(2.2 \mathrm{k} \Omega)}{(3.2 \mathrm{k} \Omega)}\right)(0.1 \mathrm{~A}) \\&=(0.06875)(0.1 \mathrm{~A}) \\I_{\mathrm{N}} &=68.75 \mathrm{~mA}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{N}}&space;&=(2.2&space;\mathrm{k}&space;\Omega)&space;\|((2.2&space;\mathrm{k}&space;\Omega)&plus;(1.0&space;\mathrm{k}&space;\Omega))&space;\\&=(2.2&space;\mathrm{k}&space;\Omega)&space;\|(3.2&space;\mathrm{k}&space;\Omega)&space;\\&=\left(\frac{(2.2&space;\mathrm{k}&space;\Omega)(3.2&space;\mathrm{k}&space;\Omega)}{(2.2&space;\mathrm{k}&space;\Omega)&plus;(3.2&space;\mathrm{k}&space;\Omega)}\right)&space;\\&=\left(\frac{(2.2&space;\mathrm{k}&space;\Omega)(3.2&space;\mathrm{k}&space;\Omega)}{(5.4&space;\mathrm{k}&space;\Omega)}\right)&space;\\R_{\mathrm{N}}&space;&=1.3&space;\mathrm{k}&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{N}} &=(2.2 \mathrm{k} \Omega) \|((2.2 \mathrm{k} \Omega)+(1.0 \mathrm{k} \Omega)) \\&=(2.2 \mathrm{k} \Omega) \|(3.2 \mathrm{k} \Omega) \\&=\left(\frac{(2.2 \mathrm{k} \Omega)(3.2 \mathrm{k} \Omega)}{(2.2 \mathrm{k} \Omega)+(3.2 \mathrm{k} \Omega)}\right) \\&=\left(\frac{(2.2 \mathrm{k} \Omega)(3.2 \mathrm{k} \Omega)}{(5.4 \mathrm{k} \Omega)}\right) \\R_{\mathrm{N}} &=1.3 \mathrm{k} \Omega\end{aligned}" />




**27. Determine el circuito equivalente Norton para el puente que aparece en la figura 8-81 sin RL**

![imagen](https://user-images.githubusercontent.com/93798427/146659631-cae3f28b-45ca-4ac3-a992-76e008bb9c81.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659645-60f2af38-c220-4827-90c3-1deec6e2ea64.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659653-5fcdfe62-8f72-4574-b6e8-701428b46076.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659686-2895da80-5770-4c02-96c5-c45db5db6d43.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659699-7e22a2df-6b1e-48d2-94d6-cc08d9404a6c.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659708-eddff782-7d4a-4c6e-98ba-d166bcd89e5d.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659717-7c502708-1d99-4217-9e80-8d3ea3811448.png)

![imagen](https://user-images.githubusercontent.com/93798427/146659741-22ce5a0e-94af-4733-8435-f74dbcbc3994.png)

**29. Aplique el teorema de Norton al circuito de la figura 8-84.**

![image](https://user-images.githubusercontent.com/93739242/147989165-776c1b35-90ef-4369-8147-0de716ff31b6.png)

<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{EQU}}&space;&=((0&space;\Omega)\|(220&space;\Omega)\|(100&space;\Omega))&plus;330&space;\Omega&space;\\&=0&space;\Omega&plus;330&space;\Omega&space;\\R_{\mathrm{EQU}}&space;&=330&space;\Omega\end{aligned}" title="\begin{aligned}R_{\mathrm{EQU}} &=((0 \Omega)\|(220 \Omega)\|(100 \Omega))+330 \Omega \\&=0 \Omega+330 \Omega \\R_{\mathrm{EQU}} &=330 \Omega\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}I_{\mathrm{S}}&space;&=\frac{V_{\mathrm{S}}}{R_{\mathrm{EQU}}}=\frac{3&space;\mathrm{~V}}{330&space;\Omega}\to&space;I_{\mathrm{S}}&space;=9.09&space;\mathrm{~mA}\end{aligned}" title="\begin{aligned}I_{\mathrm{S}} &=\frac{V_{\mathrm{S}}}{R_{\mathrm{EQU}}}=\frac{3 \mathrm{~V}}{330 \Omega}\to I_{\mathrm{S}} =9.09 \mathrm{~mA}\end{aligned}" />


<img src="https://latex.codecogs.com/svg.image?\begin{aligned}R_{\mathrm{N}}&space;&=(330&space;\Omega)\|(100&space;\Omega)\|(220&space;\Omega)&space;\\&=\left(\frac{(330&space;\Omega)(100&space;\Omega)}{(330&space;\Omega)&plus;(100&space;\Omega)}\right)&space;\|(220&space;\Omega)&space;\\&=\left(\frac{(330&space;\Omega)(100&space;\Omega)}{430&space;\Omega}\right)&space;\|(220&space;\Omega)&space;\\&=(76.74&space;\Omega)&space;\|(220&space;\Omega)&space;\\=&\left(\frac{(76.74&space;\Omega)(220&space;\Omega)}{(76.74&space;\Omega)&plus;(220&space;\Omega)}\right)&space;\\=&\left(\frac{(76.74&space;\Omega)(220&space;\Omega)}{296.74&space;\Omega}\right)&space;\\R_{\mathrm{N}}=&56.89&space;\Omega&space;\end{aligned}" title="\begin{aligned}R_{\mathrm{N}} &=(330 \Omega)\|(100 \Omega)\|(220 \Omega) \\&=\left(\frac{(330 \Omega)(100 \Omega)}{(330 \Omega)+(100 \Omega)}\right) \|(220 \Omega) \\&=\left(\frac{(330 \Omega)(100 \Omega)}{430 \Omega}\right) \|(220 \Omega) \\&=(76.74 \Omega) \|(220 \Omega) \\=&\left(\frac{(76.74 \Omega)(220 \Omega)}{(76.74 \Omega)+(220 \Omega)}\right) \\=&\left(\frac{(76.74 \Omega)(220 \Omega)}{296.74 \Omega}\right) \\R_{\mathrm{N}}=&56.89 \Omega \end{aligned}" />





**33. ¿Cuáles son los valores de R4 y RTH cuando la potencia máxima se transfiere de la fuente thevenizada
a la red en configuración de escalera de la figura 8-87?**

![imagen](https://user-images.githubusercontent.com/93798427/146814802-d43ba7eb-a0f2-4f38-9565-f7360eb2e01a.png)

![imagen](https://user-images.githubusercontent.com/93798427/146815073-0126c22b-b80d-4d7a-8955-848bbedd276b.png)

![imagen](https://user-images.githubusercontent.com/93798427/146815218-8baf5d74-9cff-48d0-8140-95ea4e2a105e.png)

![imagen](https://user-images.githubusercontent.com/93798427/146815327-91721ea5-49db-42ef-ac2b-869b90622bbd.png)

![imagen](https://user-images.githubusercontent.com/93798427/146815550-ce289c9c-cb4e-4526-ba83-f94fa2c5c9c3.png)

![imagen](https://user-images.githubusercontent.com/93798427/146815626-8922ef94-5a1a-42a6-a3d1-525779dfbb1f.png)

![imagen](https://user-images.githubusercontent.com/93798427/146815692-bc7dbf7a-e93b-4c24-85c8-a310b2c30f27.png)

![imagen](https://user-images.githubusercontent.com/93798427/146815716-4ea356a1-9243-4fd5-a0de-2311c6a5e9b7.png)

**35. En la figura 8-89, convierta cada red Y en una red delta.**

![image](https://user-images.githubusercontent.com/93739242/147989235-81235b4c-3fd0-4eca-aaf9-294d2e233b77.png)

![image](https://user-images.githubusercontent.com/93739242/147994861-8bea0bc9-536d-4ab5-83af-04ff7bb423c7.png)

<img src="https://latex.codecogs.com/svg.image?\\&space;R_{A}=\frac{R_{1}R_{2}&plus;R_{3}R_{1}&plus;R_{2}R_{3}}{R_{2}}&space;\\[10pt]&space;R_{A}=\frac{(12\Omega&space;)(22\Omega&space;)&plus;(12\Omega&space;)(18\Omega&space;)&plus;(22\Omega&space;)(18\Omega&space;)}{22\Omega&space;}&space;\\[10pt]&space;R_{A}=\frac{(264\Omega^{2}&space;)&plus;(216\Omega^{2}&space;)&plus;(396\Omega^{2}&space;)}{22\Omega&space;}&space;\\[10pt]R_{A}=\frac{(876\Omega^{2}&space;)}{22\Omega&space;}=39.82\Omega&space;&space;" title="\\ R_{A}=\frac{R_{1}R_{2}+R_{3}R_{1}+R_{2}R_{3}}{R_{2}} \\[10pt] R_{A}=\frac{(12\Omega )(22\Omega )+(12\Omega )(18\Omega )+(22\Omega )(18\Omega )}{22\Omega } \\[10pt] R_{A}=\frac{(264\Omega^{2} )+(216\Omega^{2} )+(396\Omega^{2} )}{22\Omega } \\[10pt]R_{A}=\frac{(876\Omega^{2} )}{22\Omega }=39.82\Omega " />

<img src="https://latex.codecogs.com/svg.image?\\&space;R_{B}=\frac{R_{1}R_{2}&plus;R_{3}R_{1}&plus;R_{2}R_{3}}{R_{1}}&space;\\[10pt]&space;R_{B}=\frac{(12\Omega&space;)(22\Omega&space;)&plus;(12\Omega&space;)(18\Omega&space;)&plus;(22\Omega&space;)(18\Omega&space;)}{12\Omega&space;}&space;\\[10pt]&space;R_{B}=\frac{(264\Omega^{2}&space;)&plus;(216\Omega^{2}&space;)&plus;(396\Omega^{2}&space;)}{12\Omega&space;}&space;\\[10pt]R_{B}=\frac{(876\Omega^{2}&space;)}{12\Omega&space;}=73\Omega&space;&space;" title="\\ R_{B}=\frac{R_{1}R_{2}+R_{3}R_{1}+R_{2}R_{3}}{R_{1}} \\[10pt] R_{B}=\frac{(12\Omega )(22\Omega )+(12Omega )(18\Omega )+(22Omega )(18Omega )}{12\Omega } \\[10pt] R_{B}=\frac{(264\Omega^{2} )+(216\Omega^{2} )+(396\Omega^{2} )}{12\Omega } \\[10pt]R_{B}=\frac{(876\Omega^{2} )}{12\Omega }=73\Omega " />

<img src="https://latex.codecogs.com/svg.image?\\&space;R_{C}=\frac{R_{1}R_{2}&plus;R_{3}R_{1}&plus;R_{2}R_{3}}{R_{3}}&space;\\[10pt]&space;R_{C}=\frac{(12\Omega&space;)(22\Omega&space;)&plus;(12\Omega&space;)(18\Omega&space;)&plus;(22\Omega&space;)(18\Omega&space;)}{18\Omega&space;}&space;\\[10pt]&space;R_{C}=\frac{(264\Omega^{2}&space;)&plus;(216\Omega^{2}&space;)&plus;(396\Omega^{2}&space;)}{18\Omega&space;}&space;\\[10pt]R_{C}=\frac{(876\Omega^{2}&space;)}{18\Omega&space;}=48.67\Omega&space;&space;" title="\\ R_{C}=\frac{R_{1}R_{2}+R_{3}R_{1}+R_{2}R_{3}}{R_{3}} \\[10pt] R_{C}=\frac{(12\Omega )(22\Omega )+(12\Omega )(18\Omega )+(22\Omega )(18\Omega )}{18\Omega } \\[10pt] R_{C}=\frac{(264\Omega^{2} )+(216\Omega^{2} )+(396\Omega^{2} )}{18\Omega } \\[10pt]R_{C}=\frac{(876\Omega^{2} )}{18\Omega }=48.67\Omega " />

![image](https://user-images.githubusercontent.com/93739242/147994975-d89b73ba-4de6-49e1-b532-139a2be91be6.png)


![image](https://user-images.githubusercontent.com/93739242/147994878-9194c9cc-7691-4508-a344-f51c9c04b929.png)

<img src="https://latex.codecogs.com/svg.image?\\&space;R_{A}=\frac{R_{1}R_{2}&plus;R_{3}R_{1}&plus;R_{2}R_{3}}{R_{2}}&space;\\[10pt]&space;R_{A}=\frac{(6.8k\Omega&space;)(3.3k\Omega&space;)&plus;(6.8k\Omega&space;)(4.7k\Omega&space;)&plus;(3.3k\Omega&space;)(4.7k\Omega&space;)}{3.3k\Omega&space;}&space;\\[10pt]&space;R_{A}=\frac{(22.44k\Omega^{2}&space;)&plus;(31.96k\Omega^{2}&space;)&plus;(15.51k\Omega^{2}&space;)}{3.3k\Omega&space;}&space;\\[10pt]R_{A}=\frac{(69.91k\Omega^{2}&space;)}{3.3k\Omega&space;}=21.18k\Omega&space;&space;" title="\\ R_{A}=\frac{R_{1}R_{2}+R_{3}R_{1}+R_{2}R_{3}}{R_{2}} \\[10pt] R_{A}=\frac{(6.8k\Omega )(3.3k\Omega )+(6.8k\Omega )(4.7k\Omega )+(3.3k\Omega )(4.7k\Omega )}{3.3k\Omega } \\[10pt] R_{A}=\frac{(22.44k\Omega^{2} )+(31.96k\Omega^{2} )+(15.51k\Omega^{2} )}{3.3k\Omega } \\[10pt]R_{A}=\frac{(69.91k\Omega^{2} )}{3.3k\Omega }=21.18k\Omega " />


<img src="https://latex.codecogs.com/svg.image?\\&space;R_{B}=\frac{R_{1}R_{2}&plus;R_{3}R_{1}&plus;R_{2}R_{3}}{R_{1}}&space;\\[10pt]&space;R_{B}=\frac{(6.8k\Omega&space;)(3.3k\Omega&space;)&plus;(6.8k\Omega&space;)(4.7k\Omega&space;)&plus;(3.3k\Omega&space;)(4.7k\Omega&space;)}{6.8k\Omega&space;}&space;\\[10pt]&space;R_{B}=\frac{(22.44k\Omega^{2}&space;)&plus;(31.96k\Omega^{2}&space;)&plus;(15.51k\Omega^{2}&space;)}{6.8k\Omega&space;}&space;\\[10pt]R_{B}=\frac{(69.91k\Omega^{2}&space;)}{6.8k\Omega&space;}=10.28K\Omega&space;&space;" title="\\ R_{B}=\frac{R_{1}R_{2}+R_{3}R_{1}+R_{2}R_{3}}{R_{1}} \\[10pt] R_{B}=\frac{(6.8k\Omega )(3.3k\Omega )+(6.8k\Omega )(4.7k\Omega )+(3.3k\Omega )(4.7k\Omega )}{6.8k\Omega } \\[10pt] R_{B}=\frac{(22.44k\Omega^{2} )+(31.96k\Omega^{2} )+(15.51k\Omega^{2} )}{6.8k\Omega } \\[10pt]R_{B}=\frac{(69.91k\Omega^{2} )}{6.8k\Omega }=10.28K\Omega " />


<img src="https://latex.codecogs.com/svg.image?\\&space;R_{C}=\frac{R_{1}R_{2}&plus;R_{3}R_{1}&plus;R_{2}R_{3}}{R_{3}}&space;\\[10pt]&space;R_{C}=\frac{(6.8k\Omega&space;)(3.3k\Omega&space;)&plus;(6.8k\Omega&space;)(4.7k\Omega&space;)&plus;(3.3k\Omega&space;)(4.7k\Omega&space;)}{4.7k\Omega&space;}&space;\\[10pt]&space;R_{C}=\frac{(22.44k\Omega^{2}&space;)&plus;(31.96k\Omega^{2}&space;)&plus;(15.51k\Omega^{2}&space;)}{4.7k\Omega&space;}&space;\\[10pt]R_{C}=\frac{(69.91k\Omega^{2}&space;)}{4.7k\Omega&space;}=14.87k\Omega&space;&space;" title="\\ R_{C}=\frac{R_{1}R_{2}+R_{3}R_{1}+R_{2}R_{3}}{R_{3}} \\[10pt] R_{C}=\frac{(6.8k\Omega )(3.3k\Omega )+(6.8k\Omega )(4.7k\Omega )+(3.3k\Omega )(4.7k\Omega )}{4.7k\Omega } \\[10pt] R_{C}=\frac{(22.44k\Omega^{2} )+(31.96k\Omega^{2} )+(15.51k\Omega^{2} )}{4.7k\Omega } \\[10pt]R_{C}=\frac{(69.91k\Omega^{2} )}{4.7k\Omega }=14.87k\Omega " />

![image](https://user-images.githubusercontent.com/93739242/147994951-8a2ce9bd-bb6f-4051-bd25-44a67d55b53c.png)

**SIN EJERCICIOS REALIZADOS DE ESTEBAN CACERES**

# Video #

https://youtu.be/KwGtQCp0JOM

# Conclusiones #

- A través de la lectura del capitulo su comprensión y ejercicios realizados se puede determinar lo importante que son los circuitos mixtos y la variedad de sus aplicaciones de modo que se logro realizar e implementar los diferentes metodos de resolución para estos ejercicios complejos y se determino que aprendizajes revisados anteriormente como la ley de Ohm, leyes del voltaje y la corriente de kirchhoff, y los metodos para determinar resistencia total y potencia forman parte de la resolución de este tipo de circuitos los cuales se pueden observar en muchas situaciones practicas donde se tendrán combinaciones tanto en serie como en paralelo dentro del mismo circuito.
- En conclusión tambien tenemos que gracias a los teoremas de circuitos y conversiones se nos facilitara el analisis de cierto tipo de circuitos, y que ademas este tipo de metodos no reemplazan a la ley de Ohm ni a las leyes de Kirchhoff, mas bien estos conceptos son necesarios y normalmente se utilizan junto a estos teoremas en ciertas situaciones.


# Bibliografía #

Floyd, T. L. (2007). Principios de circuitos eléctricos. (8.ª ed.). México: PEARSON EDUCACIÓN.

Circuitos Mixtos Eléctricos y Ejercicios Resueltos. (s. f.). AREATECNOLOGICA. https://www.areatecnologia.com/Calculo-circuitos-mixtos.htm

M. (2021a, abril 16). Circuito Mixto. Definición y ejemplos. MiElectrónicaFácil.com. https://mielectronicafacil.com/analisis-de-circuitos/circuito-mixto/
