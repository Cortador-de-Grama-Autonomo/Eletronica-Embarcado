# Eletronica-Embarcado
Repositório de Desenvolvimento dos Códigos de Conexão com os Sensores

## Requisitos:
* ROS Noetic

## Pacotes:
* Controle_Locomocao: Implementação do código de controle e dos nós de comunicação para movimento do robô cortador de grama.
* Controle_Corte:Implementação do código de controle da altura e velocidade do corte da grama.
* Sensores: Biblioteca de códigos para obtenção de dados dos sensores.

## Por onde começar:
- Passo 1: Criar um workspace do projeto e fazer o download do repositório
```bash
  mkdir -p ~/Eletronica-Embarcado_ws/
  cd ~/Eletronica-Embarcado_ws/
  git clone https://github.com/Cortador-de-Grama-Autonomo/Eletronica-Embarcado.git
```

- Passo 2: Compilar o workspace

```bash
  cd ~/Eletronica-Embarcado_ws/Eletronica-Embarcado
  catkin_make
```



