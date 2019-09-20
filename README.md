# lab04andy
day 4 lab

Requirements
Finish the tests

Using TDD ...
Add tests to support the other CRUD Methods
delete()
update()
Replace the memory.js parent class' sanitize() method with YOUR Validate class to support type checking (string, number, boolean)
How will this change your schemas?
How will you use this class in your CRUD methods?
Genericize the model test to run the same set of core tests on any model
Create another model

Using TDD ...
Create a data model called products
Add the following fields - use your own judgement on field type and validation rules
category_id - string, required
price - number, required
weight - number
quantity_in_stock - number, required
TDD?
Shouldn't your generic model test "just work" once you add the Products model to it's list?
Yep ...
