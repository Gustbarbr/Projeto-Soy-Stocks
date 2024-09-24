# Projeto-Soy-Stocks
Projeto de Modelagem de Software Orientado a Objeto
# DIAGRAMAS:

## Diagrama de acesso:
![image](diagrama_acesso3.png)

### Mudancas:
* Agregacao do Login e Cadastro ao Acesso
* Acesso gerar uma instancia de acesso para o cliente

## Diagrama do Extrato:
![image](diagrama_extrato.png)

### Mudancas:
* Agregacao do Registrar OC e Registrar OV com Extrato
* Atributo "Cancelado" adicionado para controlar o status das OCs e OVs
* Classe Extrato agora gera uma intancia de extrato para o cliente

## Diagrama das OCs:
![image](diagrama_OC.png)

### Mudancas:
* Duas camadas de segurancas foram adicionadas: uma antes de realizar a OC e outra antes de alterar a OC
* Atribuicao da Verificacao com Enviar_OC e Atribuicao do ClienteOC com Acessar_OCs
* Agregacao de Acessar_OCs a Modificar_OC e Cancelar_OC

## Diagrama das OVs:
![image](diagrama_OV.png)
* Duas camadas de segurancas foram adicionadas: uma antes de realizar a OV e outra antes de alterar a OV
* Atribuicao da Verificacao com Enviar_OV e Atribuicao do ClienteOV com Acessar_OVs
* Agregacao de Acessar_OVs a Modificar_OV e Cancelar_OV

## Diagrama Sequencial:
![image](Sequencia_(6).png)
