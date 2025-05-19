🚌 Sistema de Embarque de Passageiros
Este projeto simula um sistema de embarque de passageiros para diferentes cidades, gerenciando filas, emissão de tickets e alocação automática de passageiros em ônibus com capacidade limitada.

🚀 Funcionalidades
Cadastro de passageiros com geração de ticket automático.

Fila de espera por cidade.

Embarque automático de passageiros em ônibus disponíveis.

Criação de novos ônibus conforme necessidade (limite de 3 por cidade).

Registro de viagens finalizadas.

Visualização de passageiros embarcados, filas e histórico de viagens.

🏙️ Cidades disponíveis
São Luís (SL)

Imperatriz (IM)

Barreirinhas (BA)

🧠 Lógica de funcionamento
Cada cidade possui até 3 ônibus simultâneos.

Cada ônibus comporta até 4 passageiros.

Quando um ônibus enche, ele "parte", sendo registrado como viagem finalizada.

Passageiros excedentes aguardam na fila até o próximo embarque.

📁 Estrutura do Código
Passageiro: classe que representa um passageiro com nome, destino e ticket.

OnibusCidade: gerencia a fila, embarque e viagens para uma cidade.

SistemaViagem: gerencia o sistema como um todo (múltiplas cidades).

menu(): interface de texto simples para interagir com o sistema.
