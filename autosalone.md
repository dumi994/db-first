# Database Concessionario

## (table) Autmobili
- id                           BIGINT PRIMARY KEY UNIQUE NOTNULL INDEX
- numero_di_telaio             VARCHAR(17)  NOTNULL UNIQUE 
- marca                        VARCHAR(20)  NOTNULL INDEX
- modello                      VARCHAR(15)  NOTNULL 
- versione (gti, plus, ecc)    VARCHAR(10)  NOTNULL                       
- carrozzeria                  VARCHAR(10)  NULL
- anno_immatricolazione        INT          NOTNULL    
- carburante                   VARCHAR(7)   NULL         
- chilometraggio               INT          NULL             
- potenza                      VARCHAR(10)  NOTNULL       
- cambio                       VARCHAR(15)  NULL    
- n_di_porte                   TINYINT      NULL        
- n_di_posti                   TINYINT      NULL         
- condizioni_del_veicolo       VARCHAR(255) NOTNULL                    
- equipaggiamento              TEXT         NULL              
- esterni                      VARCHAR(255) NULL     
- interni                      VARCHAR(255) NULL      
- classe_emissioni             VARCHAR(25)  NOTNULL             
- prezzo                       INT          NOTNULL     