# Mule_Splitter_Aggregator


Splitting xml payload based on node provided in xpath in splitter component

Splitter — Splitter can split all types of data like Object, XML, JSON, and Payload based on MEL (Mule expression language) and processes each split into individual thread. .

Collection Splitter – If input type is collection, then collection splitter split data based on collection and process each element in individual thread.

Chunk Splitter – Chunk of splitter spilts message into chunk of bytes based on user input and processes each chunk of bytes in individual thread

URL: http://localhost:8086/split
POST call payload

<Employees>
<Employee>
<FirstName>Sampath</FirstName>
<LastName>Reddy</LastName>
<Salary>1000</Salary>
</Employee>
<Employee>
<FirstName>Sai</FirstName>
<LastName>Krishna</LastName>
<Salary>3000</Salary>
</Employee>
<Employee>
<FirstName>Rakesh</FirstName>
<LastName>Reddy</LastName>
<Salary>4000</Salary>
</Employee>
<Employee>
<FirstName>Rahul</FirstName>
<LastName>Yadav</LastName>
<Salary>7000</Salary>
</Employee>
</Employees>

