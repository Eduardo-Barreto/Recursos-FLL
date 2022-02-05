# Recursos-FLL
Base de recursos de programação para a FLL

# Andar em CM
Anda para frente ou para trás na distância, velocidade e direção desejadas.

<p align="center">
    <img src="./Assets/Exemplos/AndarCM/Bloco.png" alt="Bloco de andar em cm"></img>
</p>

## Uso

### Requisitos

Para usar o bloco de Andar em Centímetros você deve ter realizado pelo menos uma vez os seguintes passos em alguma parte do código.

**Obrigatórios**:
- [**Definir os motores de movimento**](./Requisitos.md#definir-os-motores-de-movimento)

- [**Definir a circunferência da roda**](./Requisitos.md#definir-a-circunferência-da-roda)

- [**Definir o KP para  a correção de direção**](./Requisitos.md#definir-o-kp)
    > Pelo menos uma vez ou quando necessário

**Opcionais**:
- [**Definir o tipo de parada**](./Requisitos.md#definir-o-tipo-de-parada)

### Parâmetros
- **Centímetros**
    - Tipo: número
    - Descrição: A distância em centímetros desejada.

        > Valores positivos para ir para frente e negativos para ir para trás

- **Velocidade**
    - Tipo: Número
    - Descrição: A velocidade em % desejada.

        > Valores entre 0 e 100

- **Direção**
    - Tipo: Número
    - Descrição: A direção em graus (em relação ao ponto inicial) desejada.

        > Valores entre 0 e 359


## Exemplos
### Exemplo 1
<p align="center">
    <img src="./Assets/Exemplos/AndarCM/Exemplo1/Bloco.png" alt="Exemplo do código de andar em cm"></img>
</p>

Anda 30 centímetros para frente na metade da velocidade máxima, tentando sempre se manter reto em 0 graus em relação a direção inicial.

<p align="center">
    <img src="Assets/Exemplos/AndarCM/Exemplo1/Demo.gif" alt="Demonstração" width="31%"></img>
    <img src="Assets/Exemplos/AndarCM/Exemplo1/Sensores.gif" alt="Leituras dos sensores" width="58%"></img> 
</p>

---
### Exemplo 2
<p align="center">
    <img src="./Assets/Exemplos/AndarCM/Exemplo2/Bloco.png" alt="Exemplo do código de andar em cm"></img>
</p>

Anda 55 centímetros para trás com 40% da velocidade máxima, tentando sempre se manter a 90 graus da direção inicial

<p align="center">
    <img src="Assets/Exemplos/AndarCM/Exemplo2/Demo.gif" alt="Demonstração" width="31%"></img>
    <img src="Assets/Exemplos/AndarCM/Exemplo2/Sensores.gif" alt="Leituras dos sensores" width="58%"></img> 
</p>

# Aceleração
Anda para frente ou para trás na distância, velocidade e direção desejada, com um controle de curva de aceleração em trapézio para minimizar os erros.

<p align="center">
    <img src="./Assets/Exemplos/Aceleracao/Bloco.png" alt="Bloco de aceleração"></img>
</p>


## Uso
### Requisitos
Para usar o bloco de Aceleração você deve ter realizado pelo menos uma vez os seguintes passos em alguma parte do código.

**Obrigatórios**:
- [**Definir os motores de movimento**](./Requisitos.md#definir-os-motores-de-movimento)

- [**Definir a circunferência da roda**](./Requisitos.md#definir-a-circunferência-da-roda)

- [**Definir o KP para  a correção de direção**](./Requisitos.md#definir-o-kp)
    > Pelo menos uma vez ou quando necessário

**Opcionais**:
- [**Definir o tipo de parada**](./Requisitos.md#definir-o-tipo-de-parada)

### Parâmetros
- **Centímetros**
    - Tipo: número
    - Descrição: A distância em centímetros desejada.

        > Valores positivos para ir para frente e negativos para ir para trás

- **Velocidade mínima**
    - Tipo: Número
    - Descrição: A velocidade mínima em % desejada para o início e finalização do percurso.

        > Valores entre 0 e 100

- **Velocidade máxima**
    - Tipo: Número
    - Descrição: A velocidade máxima em % desejada para o segundo estágio/meio do percurso.

        > Valores entre 0 e 100

- **Direção**
    - Tipo: Número
    - Descrição: A direção em graus (em relação ao ponto inicial) desejada.

        > Valores entre 0 e 359

## Exemplos
### Exemplo 1
<p align="center">
    <img src="./Assets/Exemplos/Aceleracao/Exemplo1/Bloco.png" alt="Exemplo do código de aceleração"></img>
</p>

Anda 60 centímetros para frente, variando a velocidade entre 10 e 100% da velocidade máxima, tentando sempre se manter reto em 0 graus em relação a direção inicial.

<p align="center">
    <img src="Assets/Exemplos/Aceleracao/Exemplo1/Demo.gif" alt="Demonstração" width="31%"></img>
    <img src="Assets/Exemplos/Aceleracao/Exemplo1/Sensores.gif" alt="Leituras dos sensores" width="58%"></img> 
</p>

**Gráfico de aceleração**:
<p align="center">
    <img src="Assets/Exemplos/Aceleracao/Exemplo1/CodigoGrafico.png" alt="Código do gráfico de aceleração" width="43%"></img>
    <img src="Assets/Exemplos/Aceleracao/Exemplo1/Grafico.jpg" alt="Gráfico de aceleração" width="45%"></img> 
</p>


---
### Exemplo 2
<p align="center">
    <img src="./Assets/Exemplos/Aceleracao/Exemplo2/Bloco.png" alt="Exemplo do código de aceleração"></img>
</p>

Anda 60 centímetros para frente, variando a velocidade entre 10 e 100% da velocidade máxima, tentando sempre se manter reto em 0 graus em relação a direção inicial.

<p align="center">
    <img src="Assets/Exemplos/Aceleracao/Exemplo2/Demo.gif" alt="Demonstração" width="31%"></img>
    <img src="Assets/Exemplos/Aceleracao/Exemplo2/Sensores.gif" alt="Leituras dos sensores" width="58%"></img> 
</p>

**Gráfico de aceleração**:
<p align="center">
    <img src="Assets/Exemplos/Aceleracao/Exemplo2/CodigoGrafico.png" alt="Código do gráfico de aceleração" width="43%"></img>
    <img src="Assets/Exemplos/Aceleracao/Exemplo2/Grafico.jpg" alt="Gráfico de aceleração" width="45%"></img> 
</p>