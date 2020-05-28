Assessment 2

# Question 1 (https://adrianmejia.com/ruby-on-rails-architectural-design/)

Rails is a web application development framework which adheres to a rule of convention over configuration. This allows programmers to be more productive as structure of the program is prefabricated allowing for more time to focus on the programs content. The rails framework is comprised of the model, view and controller also known as MVC. The model contains the logic of data being handled by the code framework. It allows for the manipulation and validation of data being stored as well as being passed to and from the client. The view is concerned with rendering the data from the server into a meaningful "view" for the end client. 

Apart from convention over configuration, rails philosophy also involves the DRY principle. DRY, which stands for do not repeat yourself encourages programmers to reduce the lines of code they write, by developing unambiguous code, which can be reused throughout the program. This allows for a less buggy, easy to maintain and efficient code.


# Question 2
https://www.techopedia.com/definition/1178/data-independence
https://thenewstack.io/why-and-when-you-need-transactional-ddl-in-your-database/
https://www.aalpha.net/blog/pros-and-cons-of-using-postgresql-for-application-development/

Database management systems enables users to store, create, retrieve, edit and delete data. DBMS allows for data independece, which permits for a logical schema to be modified, without affecting the structure of the next level data structure. Data independence also means that data is stored at a different location rather than within the application, allowing for more versatile use of data and a more portable and efficient application. 
An example of a widely used database management system is postgresql.

Postgresql has several benefits compared to other databases such as, transactional DDL, extensibility and security. A transactional DDL is concerned with a group of operations observing ACIDity (atomic, consistent, isolated and durable) being treated as a single operation. This grouping of transactions enable better responsiveness and flexibility to application problems, as programmers will be able to rollback to a previous working code and resolve the issue, without interrupting the functionality and accessibility of the entire application. Extensibility refers to the ability of postgresql to install multiple extensions allowing the user to execute additional functions, that may not even be the main language used by the programmer, which does not pose as a problem since postgresql handles the functionality automatically.
Security wise  postgresql provides parameter based security wherein database can be locked down at an OS level. Application security is also delivered through the basis of segregated user privileges.

Some of postgresql's limitations involve a strict database structure, wherein a schema cannot consist of new data until it's column has been defined prior to addition. This structure may also lead to a slower performace when running a query on a large scale databse, as the query will have to be run through numerous rows and columns. Postgresql is also an open source software, which means it is run by the community, this implies a lack of warranty and indemnity protection.

# Question 3 (https://www.smartsheet.com/comprehensive-guide-values-principles-agile-manifesto)
https://www.dummies.com/careers/project-management/applying-agile-management-value-2-working-software-over-comprehensive-documentation/
<!-- Discuss the implementation of Agile project management methodology	 -->

Agile is a methodology which adheres to four values. 

1)Individuals and Interactions Over Processes and Tools. 

   Promotes a smoother flow of communication between team members and customers allowing for faster reactions when change must be done to a project, as in the case of process these conversations will be scheduled and may be limited to specific topics of discussion making reactions to changes sluggish.

2)Working Software Over Comprehensive Documentation,

   Rather than developers dedicating a huge and particular amount of time in documentation,which may retard the progress of project development this encourages workers to streamline documentation. Developers create documentation on the go, normally depicting the requirements of the project and technical specifications as to how the individual approached creating the project. This method allows easier identification of potential issues as assessment is concurrent with development of the application.

3)Customer Collaboration Over Contract Negotiation
  
  Collaboration allows the customer and developers to constantly monitor and guide the direction of the project, this proves to be more flexible as any issues that may arrise can be quickly discussed and resolved. This also provides a realistic perception of how the project will turn out. Since negotiation occurs periodically, it is less flexible as the customer normally presents expectation before the project even begins. Customers are not as involved in the development process, which may lead to unmet expectations and unexpected changes which can cause delays.
  
4) Responding to Change Over Following a Plan.

   With the agile methodology, teams work on small segments of a project at a time, rather than spreading the team across a wide plain. This again enables the team to be more reactive as resources can be moved to specific parts of the project when required. The ability to make the project fit the team also can increase productivity and ingenuity as interplay of ideas is more likely to occur when tackling projects in a more focused group.

# Question 4 (https://www.perforce.com/blog/vcs/what-source-control)
<!-- Provide an overview and description of a standard source control workflow	 -->

Source control is a crucial part of coding, especially for development teams. This allows for a source of truth for the developers working on a particular code. Source control paves a path for collaborations, as it enables multiple programmers to work a similar code base, where there will be no conflict if any of the developers commit or merge code. History of code alterations are also recorded in order to manage versions of the code, in case an update causes errors or bugs.

 A standard workflow for source control involves, creating a new project, coding, add it to the staging area, commit the staged changes to local repository, create an online repository and push your file to that online repository. Otherwise if a user plans to add a new feature or create a bug fix he/she must create a new branch which will not affect the master, and merge that branch if no issues arise, or continue working on a separate branch.

# Question 5 (https://reqtest.com/testing-blog/the-a-to-z-guide-to-the-software-testing-process/)
https://www.toolsqa.com/software-testing/test-process-in-software-testing/
<!-- Provide an overview and description of a standard software testing process (e.g. manual testing) -->
1)Testing Strategy and Planning

2)Test Designing

3)Test Execution

4)Test Closure

# Question 6
https://www.proserveit.com/blog/information-security-requirements maybe?
<!-- Discuss and analyse requirements related to information system security and how they relate to the project -->

ACME's project must ensure that it is not succeptible to cybersecurity attacks, and it must uphold its responsibility towards the business, regulatory bodies and customers.

# Question 7
<!-- Discuss common methods of protecting information and data and how you would apply them to the project	 -->
# Question 8

# Question 9
<!-- Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.-->
https://www.guru99.com/relational-data-model-dbms.html
Relational database models are simply data represented as a collection of relations or table of values. The table is composed of a name, tuple and column. The column represents each of the attributes a data must comprise of, while each row identifies a particular set of related data within that particular table, which is normally identified through the primary key.
The model is a separate entity from the relational database management system, which enables the manipulation of stored data. Examples of RDM are Oracle, SQL adn DB2. The simple layout of relational database makes it scalable, data retrieval is also easier as it is information is organized. Different tables can also be connected through special join cases such as foreign keys, allowing for more dynamic and meaningful results during queries.

# Question 10
https://www.techopedia.com/definition/811/data-integrity-databases

Relational integrity refers to the conditions required in order to uphold meaningful relations. It is divided into three categories domain constraints, key constraints and referential integrity constraints. Domain constraints state that columns of a relational database must be defined and that every column definition must be unique along with its data type being declared. Key constraints dictates that every row must have it's own unique primary key and a primary key must not be null. 
While referential integrity permits foreign keys to be in two states, first is as a primary key of another table and second is it being null, which represents no relationship to another table.
These rules being implemented allow for a well defined and reliable data structure, as the paramaters ties down each data input at a particular section of the table.
# Question 11
   Database management systems are responsible for manipulating the data within a database model. SQL or structured query language is a commonly used language by these management systems in order to handle data.Database management systems utilizing SQL such as Postgresql is an improved version, which support additional functionalities such as support of unicode characters, additional options for setting triggers and support for arrays. SQL was specifically made to handle databases, as it has builin statements with particular syntaxes to create, edit, delete and retrieve data. Some of the crucial commands built in to SQL involve select,update,delete,insert into,drop table, create table, create index and create database. These commands must then be executed in a strict arrangement in order to obtain meaningful results. An example of a common SQL query to update is placed below.
   (UPDATE nameOfTable)
   (SET    parameterOfDataToBeChanged)
   (WHERE  primaryKeyofData)

# Question 12
https://www.toptal.com/developers/sorting-algorithms same for 13

A sorting algorithm enables the rearrangement of an array of data in a particular pattern, through the use of comparison operators. The sorting of data is crucial as it optimizes the efficiency of other algorithms, mainly the search algorithm. As a sorted database enables for faster location of data and produces a more readable output. Sorting algorithms include and is not limited to the ff: selection sort, bubble sort, insertion sort, merge sort, quick sort, heap sort and radix sort.

In order to measure the performance of these algorithms the Big-O notation is used. Big-O implies how code complexity is affected by the amount of input being handled by code. 
# Question 13
https://www.studytonight.com/data-structures/selection-sorting same for 12
# Question 14