# datasetadapter
A delphi dataset adapter that allows abstraction and automatic release of resources via interfaces

Use of database adapter technology:

    q_cust := db.GetIQuery('select * from customer',[daoOneway]);//
    
    while q_cust.loop() do              // loop example
    
    q_cust.s['fieldname']:= 'string';   // assign example
    
    q_cust out of scope will automaticly free memory (its an interface)
    
    
    
