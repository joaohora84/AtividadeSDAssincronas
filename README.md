# AtividadeSDAssincronas
Atividade sobre chamadas assíncronas para atividade sistema distribuídos

1 - Qual problema percebeu ao realizar tais alterações;

    R: Mesmo que o **h2** seja executado após request(), a resposta do **h2** aparece primeiro na tela.
    
2 - Explique porque o problema ocorreu e o qual a relação com chamadas assíncronas;

    R: O problema ocorreu porque a função request() é assíncrona, assim o sistema não espera a resposta dela para iniciar a próxima linha.
    
3 - Altere o código para resolver o problema.

    R: Inserir um IF para ao h2 ser mostrado somente se a request() tiver um retorno.
    
