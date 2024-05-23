# Bootcamp Dio - Coding The Future Avanade .NET Developer - Criando um Sistema e Abstraindo um Celular com POO em C#.

 ℹ️ **Note** Desafio de projeto
Um projeto simples que visa apenas aplicar os conhecimentos adquiridos no módulo de orientação a objetos.Desta forma não possui implementações avançadas de seus métodos ou acressímo de classes para compor um cenário mais realista. 

## 🎯 Contexto
Objetivo de  modelar um sistema que trabalha com celulares. Para isso, foi solicitado que se faça uma abstração de um celular e disponibilize maneiras de diferentes de  marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

## Proposta
Sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. 
As classes foram criadas de acordo com o diagrama abaixo:

![Diagrama classes](Imagens/diagrama.png)

## Regras e validações
1. A classe **Smartphone** deve ser abstrata, não permitindo instanciar e servindo apenas como modelo.
2. A classe **Nokia** e **Iphone** devem ser classes filhas de Smartphone.
3. O método **InstalarAplicativo** deve ser sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.

## Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.
