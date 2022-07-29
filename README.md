# Fourth Week Homework
## TodebBootcamp Data Access Layer 

1. The **Blank Solution** project named **TodebBootcamp** was created in Visual Studio.

2. **Models** class library project was created on solution. Models contains **DTO** folder and **Entities** folder. In Entities folder, 4 type of Entity was created. They are **Address, Product, Category** and **Supplier**. Some of them linked to another table with one to one relation, some of them linked to another table with one to many relation. For example in Category table Category linked Product Id in Product entity. This form is one to many relation. Because one category can have more than one product.

3. **DataAccessLayer** was created on **TodebBootcamp** solution. In this layer, **TodebCampDbContext** class was created and database was setted in this class. Used **PostgreSql** in this project.

4. Migration proccess was done and database was updated.

5. Finally console application named **ConsoleUI** was created on solution. Some of database datas were inserted **Program.cs** class like **Category, Products** etc.
