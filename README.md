<div align="center">
  <img height="300" src="https://media1.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif?cid=ecf05e47qjrmoqge505dv90o0u0lb37q32bv3y9mo40e7ms2&ep=v1_gifs_search&rid=giphy.gif&ct=g"  />
</div>

###

<div align="center">
  <a href="https://www.linkedin.com/in/ali-kerem-simsek/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
</div>

###

<h1 align="center">Hey Everyone 👋</h1>

###

<h3 align="center">Today we will take a closer look at the Data Warehouse concept. We will try to understand this concept better.</h3>

###

<p align="left">What are differences between these terms? If we understand this, probably we can understand these terms better.</p>

###

<h2 align="left">• DataBase vs DataWarehouse vs DataLake vs DataMart</h2>

###

<p align="left">· DataMart : They are subsections of the data warehouse created for business lines. They are created for jobs such as sales transactions, products, and inventory records.</p>

###

<div align="center">
  <img height="400" src="https://github.com/krmsmsk/Resimler/blob/main/DWH/Screenshot_3.png?raw=true"  />
</div>

###

<p align="left">· DataLake : It stores unformatted data in its raw form for a specific purpose. We can format these datas which are unformatted, and then upload them to DataWarehouse.</p>

###

<div align="center">
  <img height="400" src="https://github.com/krmsmsk/Resimler/blob/main/DWH/Screenshot_2.png?raw=true"  />
</div>

###

<p align="left">And the most confused DataBase vs DWH<br>· DataBase, stores data for a specific business area. DWH, stores current and historical data for the entire business.<br>· DataBase, designed to save data. DWH, designed to analyze data.<br>· Online transaction processing (OLTP) uses in the DataBase. Online analytical processing (OLAP) uses in the DWH.<br>· DataBase is messy because the tables are normalized. It is easy as it is denormalized in DWH.<br>· ER modeling techniques are used while designing the DataBase. Data modeling techniques are used in DWH.</p>

###

<h2 align="left">•  What is normalization?</h2>

###

<p align="left">Normalization aims to minimize data integrity issues, data redundancy, and irregular structures within databases. It provides the necessary steps to enhance the performance of a database. <br><br>Normalization is based on the following general steps to store data in a more organized, consistent, and efficient manner:<br>1. First Normal Form (1NF): Each data cell must contain only atomic (indivisible) values. In other words, a cell should not contain multiple values. If a table doesn't conform to 1NF, data needs to be divided into smaller parts.<br>2. Second Normal Form (2NF): A table must adhere to 1NF and, additionally, all non-key attributes must be functionally dependent on the entire primary key. This eliminates unnecessary data repetition and meaningless relational structures.<br>3. Third Normal Form (3NF): A table should conform to 2NF and, furthermore, all data not dependent on the primary key should be eliminated. This process removes unnecessary dependencies among data.</p>

###

<h2 align="left">•  Modelling Techniques</h2>

###

<p align="left">There are two techniques we should know. There are Inmon model and Kimball model.</p>

###

<p align="left">· Inmon Model:<br><br>Developed by Bill Inmon before Ralph Kimball's model, the Inmon Model asserts that a data warehouse should be a centralized repository containing all of an organization's business data. The Inmon model adopts a "top-down" or "big-to-small" approach:<br><br>- Central Integration: The Inmon model aims to gather the data of all business processes and departments in an integrated data warehouse. This centralized data warehouse ensures that all of the organization's data comes from a single source.<br>- Data Normalization: Data normalization is common in the Inmon model. Data is decomposed into smaller and normalized databases. This can enhance data integrity and reliability.<br>- Single Version of Truth (SVOT): According to Inmon, there should be a single, authoritative source (SVOT - Single Version of Enterprise) for each data element. This minimizes data inconsistencies and differing interpretations among different departments.</p>

###

<div align="center">
  <img height="400" src="https://github.com/krmsmsk/Resimler/blob/main/DWH/inmon.png?raw=true"  />
</div>

###

<p align="left">· Kimball Model:<br><br>Ralph Kimball developed a model that focuses on building data warehouses faster and in a department-centric manner. The Kimball model adopts a "bottom-up" or "small-to-big" approach:<br><br>- Data Warehouse Components (Data Marts): In the Kimball model, the data warehouse is divided into smaller, specific, and regional databases called data marts. Each data mart focuses on the needs of a particular department or business process.<br>- Dimensional Modeling: The Kimball model embraces dimensional modeling. Data is organized based on the relationships between measures (business metrics) and dimensions (descriptive attributes).<br>- Rapid Development: The Kimball model aims for faster data warehouse construction. Data marts can be built in parallel, enabling quicker results tailored to specific needs.</p>

###

<div align="center">
  <img height="400" src="https://github.com/krmsmsk/Resimler/blob/main/DWH/kimball.png?raw=true"  />
</div>

###

<p align="left">· Differences:<br><br>-Approach: The Inmon model emphasizes a centralized and integrated structure, whereas the Kimball model aims for quicker results and highlights department-focused data marts.<br>-Data Normalization vs. Dimensional Modeling: While the Inmon model stresses data normalization, the Kimball model emphasizes dimensional modeling. Dimensional modeling provides a user-friendly and understandable data structure.<br>- Data Warehouse Structure: The Inmon model adopts a centralized data warehouse structure, while the Kimball model can be more distributed because data marts can be independently created.</p>

###

<h2 align="left">•  What are OLTP and OLAP?</h2>

###

<div align="center">
  <img height="200" src="https://media4.giphy.com/media/3oeHLhzRkRX1bQQBPi/giphy.gif?cid=ecf05e47jg3cs446txfq3sgm7gzofyzh91qiaqqzdy5vvlky&ep=v1_gifs_search&rid=giphy.gif&ct=g"  />
</div>

###

<p align="center">Loading...</p>

###
