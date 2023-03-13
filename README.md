## Projeto para vaga de estágio

### Questão numero 1: 
Código em linguagem C:

#include <stdio.h>

int main() {
int INDICE = 13, SOMA = 0, K = 0;

   while(K < INDICE){
   
       K = K + 1;

       SOMA = SOMA + K;
   }
   
   printf("%d",SOMA);
   
return 0;
}

### Questão 2:
Termo1 = int(0)

Termo2 = int(1)

Termo3 = int(0)

print ('-' *42)

print (' ' *3, 'Consulta da Sequência de Fibonacci')

print ('-' *42)

Valor = int(input('Digite um número: '))

while Valor > Termo3:

Termo3 = Termo1 + Termo2

Termo1 = Termo2

Termo2 = Termo3

if Valor == 0 or Valor == 1:

print ('O número faz parte da sequência de Fibonacci.')

elif Valor == Termo3:

print ('O número faz parte da sequência de Fibonacci.')

else:

print ('O número digitado não faz parte da sequência de Fibonacci.')

### Questão 3:
a) 1, 3, 5, 7

Cada número é igual ao anterior + 2, formando os números ímpares. Assim, o próximo número é igual a 7 + 2 = 9.

b) 2, 4, 8, 16, 32, 64


Cada número é igual ao anterior multiplicado por 2. Assim, o próximo número é igual a 64 x 2 = 128.

c) 0, 1, 4, 9, 16, 25, 36

Cada número é igual ao anterior acrescido de um número ímpar que segue a sequência 1, 3, 5, 7, 9. Realizando a subtração dos dois últimos números, temos que 36 - 25 = 11. Assim, devemos acrescentar 11 + 2 = 13 ao último número, obtendo 36 + 13 = 49.

d) 4, 16, 36, 64

Cada número é igual ao quadrado dos números pares. Com isso, temos que 64 = 8². Então, o próximo número par é 10, e o seu quadrado é 10² = 100.

e) 1, 1, 2, 3, 5, 8

Cada número é igual à soma do número atual com o número anterior. Assim, o próximo número é igual a 8 + 5 = 13.

f) 2, 10, 12, 16, 17, 18, 19

Sequência formada através de todos os números que iniciam com a letra d. Assim, o próximo número em ordem crescente que inicia com a letra d é 200.

### Questão 4:
Como o caminhão sai de um local 100 km distante do ponto de referência e se aproxima dele, sua equação horária é:
x² = 100 - v?.t

Como o caminhão tem 2 pedágios como obstáculo e perde 5 minutos em cada um deles, podemos calcular o tempo de viagem sem os obstáculos:
t = 100/80 = 1,25h

Porém, como perde 10 minutos (ou 0,17 horas) nos pedágios, o tempo de viagem para o caminhão será de 1,25h+0,17h=1,42h. Sua velocidade média é:
v²100/1,42 = 70,6 km/h

Nas equações horárias podemos limpar o tempo e igualar ambas para achar o ponto em que o carro e o caminhão se cruzam:
t = x² - 100/-v²
x¹= x² = x/v¹ = x-100/-v²
-v².x = v¹.x - v¹.100
x = v¹.100/v¹+v² = 110.100/110+70,6
x = 60,9

Essa é a distância da cidade de Ribeirão Preto em que o carro e o caminhão se cruzam, ambos estão à mesma distância.

### Questão 5:
#include<stdio.h>

#include<string.h>

#include<stdlib.h> 

     
main(){

       char string[50],auxiliar[50];
       
       int a,b;
       
       printf("Digite a frase para ser invertida: ");
       
       gets(string);  //Armazena a frase
       
       b=strlen(string)-1;    
       
       for(a=0;string[a]!='\0';a++){    
       
       auxiliar[b]=string[a];
       
       b--;     
       
       }
       
       auxiliar[a]='\0';      
       
       strcpy(string,auxiliar); 
       
       printf("\n\nA frase inversa e:\n%s\n\n",string);
       
system("pause");

}
