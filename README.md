Сотрудники (  
идентификатор, первичный ключ, serial,  
фамилия varchar(50),  
имя varchar(50),  
отчество varchar(50),  
оклад float unsigned,  
идентификатор должность, внешний ключ, integer,  
идентификатор типа подразделения, внешний ключ, integer,  
идентификатор структурного подразделения, внешний ключ, integer,  
идентификатор даты найма, внешний ключ, integer,  
идентификатор адреса филлиала, внешний ключ, integer,  
идентификатор проекта, внешний ключ, integer)  
  
Должность (  
идентификатор, первичный ключ, serial,  
название должности, varchar(40)  
)  
  
Тип подразделения (  
идентификатор, первичный ключ, serial,  
тип подразделения, varchar(20)  
)  
  
Структурное подразделение (  
идентификатор, первичный ключ, serial,  
тип подразделения, varchar(60)  
)  
  
Дата найма (  
идентификатор, первичный ключ, serial,  
тип подразделения, date  
)  
  
Адрес филиала (  
идентификатор, первичный ключ, serial,  
адрес филиала, varchar(80)  
)  
  
Проект (  
идентификатор, первичный ключ, serial,  
адрес филиала, varchar(50)  
)  
