flappyAI
===================

Código desenvolvido para a disciplina de Inteligência Artificial. 

## Instalação e execução

Você provavelmente vai precisar instalar apenas o pygame. 

```bash
pip3 install pygame
``` 


Para executar o código, basta entrar na pasta com o código-fonte

```python
cd flappyAI/src
python3 flappy.py 
``` 
Para remover a aprendizagem (zerar os valores de qvalues.json)

```python
python3 initialize_qvalues.py 
``` 

E, rodar o algoritmo de aprendizagem

```python
python3 learn.py (insira o número de iterações aqui) 
``` 

**Créditos**

https://github.com/chncyhn/flappybird-qlearning-bot
