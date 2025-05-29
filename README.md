# Neanderwin
Programa:soma de um numero par com um numero impar e subtraindo por um numero par
; Autor:Elias Ferreira 
; Data:29-05-25
;---------------------------------------------------
inicio: 
          LDA  num1           ; carrega o valor de num1 no acumulador
          ADD  num2           ; soma o valor de num2 ao acumulador
          SUB  num3           ; subtrai o valor do acumulador 
          STA  resultado      ; armazena o resultado em resultado 
          HLT                 ; termina a execução

num1:           DB   12             ; primeiro numero é (12)
num2:           DB   7              ; segundo numero é (7)
num3:           DB   6              ; o terceiro numero é (6)
resultado :     DB   0              ; local para armazenar o resultado 
