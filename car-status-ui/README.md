Rotas da API:

URL padrão:
  localhost:8080/api/

Pessoas:
  Salvar: 
    pessoa/ (POST)
  Buscar por ID: 
    pessoa/{id} (GET)
  Buscar todos: 
    pessoa/ (GET)
  Editar: 
    pessoa/{id} (PUT)
  Deletar:
    pessoa/{id} (DELETE)

 Mecanico:
  Salvar: 
    mecanico/ (POST)
  Buscar por ID: 
    mecanico/{id} (GET)
  Buscar todos: 
    mecanico/ (GET)
  Editar: 
    mecanico/{id} (PUT)
  Deletar: 
    mecanico/{id} (DELETE)
  
  Carro:
    Salvar: 
      carro/ (POST)
    Buscar por ID: 
      carro/{id} (GET)
    Buscar todos:
      carro/ (GET)
    Editar:
      carro/{id} (Put)
    Deletar:
      carro/{id} (DELETE)
    Buscar todos por ID do dono:
      carro/dono/{id}
   
   Manutenção:
    Salvar: 
      manutencao/ (POST)
    Buscar por ID: 
      manutencao/{id} (GET)
    Buscar todos: 
      manutencao/ (GET)
    Editar: 
      manutencao/{id} (PUT)
    Editar: 
      manutencao/{id} (DELETE)
    Buscar por Id do cliente:
      manutencao/cliente/{id}
    Buscar por Id do mecanico:
      manutencao/mecanico/{id}
    Iniciar:
      manutencao/{id}/iniciar
    Finalizar:
      manutencao/{id}/finalizar
    Cancelar:
      manutencao/{id}/cancelar
