# Trabalho-8-Valdir
# Nome: Paola Beatriz Gonçalves Ribeiro
# RA: 2039403
# Curso: 1°C ADS, Noturno
# UNIMAR (Universidade de Marilia)
# Cenário: Sistema de Gerenciamento de Clínica Médica 

**Descrição do Sistema:**

A clínica médica deseja implementar um sistema para gerenciar consultas, médicos,
pacientes e prontuários médicos. O sistema deve permitir que os pacientes agendem
consultas online, que os médicos acessem e atualizem prontuários e que os
administradores gerenciem o cadastro de médicos e pacientes. 

**Atores:**
* **Paciente:** Usuário que agenda consultas e visualiza seu histórico médico.
  
* **Médico:** Profissional de saúde que realiza consultas, acessa e atualiza
prontuários dos pacientes.

* **Administrador:** Usuário que gerencia o cadastro de médicos e pacientes, além
de gerenciar as consultas.

# Lista dos casos de uso:
* Cadastrar pacientes;
* Cadastrar médicos;
* Agendar consultas;
* Gerenciar consultas;
* Acessar prontuários;
* Atualizar prontuários;
* Visualizar histórico médico.
  
# Relacionando cada ator com seus respectivos casos de uso:

**Paciente:** Agendar consultas e Visualizar histórico médico.

**Médico:** Acessar prontuários e Atualizar prontuários.

**Administrador:** Cadastrar pacientes, Cadastrar médicos e Gerenciar consultas.

# Detalhamento dos casos de uso escolhidos:

# Primeiro caso de uso: Agendar consultas

**Ator:**
1. Paciente.
  
**Objetivo:**
1. Realizar o agendamento de uma consulta.
  
**Pré-condições:**
1. O paciente deve estar cadastrado no sistema.
  
**Fluxo principal:**
1. O paciente acessa a aba "Agendar nova consulta";
2. O sistema exibe as consultas disponíveis;
3. O paciente seleciona a consulta desejada e preenche com seus dados;
4. O sistema verifica os dados, se forem validos, o sistema permite o agendamento;
5. Caso os dados sejam inválidos, o sistema exibe uma mensagem de erro.
   
**Fluxos alternativos (exceção):**
1. O paciente não esta cadastrado;
2. O sistema apresenta falhas.
   
**Pós-condições (exemplo feito em sala):**
1. O paciente realizou o agendamento de uma consulta.

# Segundo caso de uso: Acessar prontuários

**Ator:** 
1. Médico
  
**Objetivo:**
1. Acessar prontuários.
  
**Pré-condições:**
1. O médico deve estar cadastrado no sistema.
  
**Fluxo principal:**
1. O médico acessa a aba "Prontuários";
2. O sistema exibe os prontuários de seus pacientes;
3. O médico seleciona um prontuário;
4. O médico atualiza o prontuário (Caso a consulta já foi realizada, ele pode colocar uma "verificação" naquele prontuário).
   
**Fluxos alternativos (exceção):**
1. O médico não esta cadastrado;
2. O sistema apresenta falhas.

**Pós-condições (exemplo feito em sala):**
1. O médico visualizou o prontuário e realizou devida atualização.
