change column name of table : 

        ALTER TABLE Subjects CHANGE sub_name subject_name varchar(100);



default value for column : 

        create table Subjects (sub_id int not null, sub_name varchar(100) default 'some subject');
