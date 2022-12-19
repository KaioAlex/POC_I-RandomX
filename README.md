# POC_I-RandomX

* Dependências necessárias:
    
    cmake (versão mínima 2.8.7) and gcc (versão mínima 4.8, mas versão 7+ é recomendada)

* Para a compilação dos binários no ambiente Linux:
    
    $ git clone https://github.com/kaioalex/POC_I-RandomX
    
    $ cd POC_I-RandomX
    
    $ mkdir build && cd build
    
    $ cmake -DARCH=native ..
    
    $ make

* Para executar o teste de uma das partes do protocolo, estando na raiz do projeto:
    
    $ cd /tests
    
    $ ./rng_protocol {String K} {String H}