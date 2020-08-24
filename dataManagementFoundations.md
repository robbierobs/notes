**Data Management Foundations**
* File Structures
* 	Flat Files - Have no internal hierarchya
* 		Unstructured
* 		Plain text or binary files
* 		After finished, entire file is written back.
* 	Heap Files - Containing unsorted set of records uniquely identified by id which allows to be inserted or deleted using that id.
* 	Index Files - Store a list of lookup field values from a data file, along with location in the data file of the corresponding record. Entire index will usually fit in main memory for quick look up. Once loaded, entire record can be accessed instead of reading the entire file record by record.
* 	Like a book, use index in a book to find location.
* 	Contains keywords, phrases
* 	Contains a pointer to the location
* 	Hashed Files - Use a hash funcito to decode where a record should be placed. Faster without the use of an index file

* Data Versus Information
* 	Data 
* 		Consists of raw facts
* 		Have not been processed
* 	Information
* 		Result of processing raw data to reveal its meaning
* 		Organizing data to reveal patterns
* 		Making forecasts, drawing inferences using statistical modeling
* 		Requires context
* 	Raw data must be properly ***formatted*** for storage, processing, presentation.
* 	**Knowledge** - Body of information and facts about a specific subject
* 		Implies familiarity, awareness, understanding of information
* 		"New knowledge can be derived from old knowledge"
* 	**Key Points**
* 		Data constitues the building blocks of information
* 		Information is produces by processing data
* 		Information is used to reveal the meaning of data
* 		Accurate, relevant, timely information is the key to good decision making
* 		Good decision making is the key to organizational survival in a global environment
* 	**Data Management** is a discipline that focuses on the proper generation, storage, and retrieval of data.
* Introducing the Database 1.4
* 	A **database** is a shared, integrated computer structure that stores a collection of:
* 		End-user data - raw facts of interest to the end user
* 		**Metadata** - data about data
* 		A database can be described as a "collection of self-describing data"
* 	**Database management system** is a collection of programs that manage the structure and controls access.
* 	DBMS (Database management system) serves as an intermediary between the user and the database.
* 		Enables the data in the database to be shared amoung multiple applications or users
* 		Integrates many different users' views of the data into a single all-encompassing data repository
* 		**Provides**
* 			Improved data sharing
* 				Better access to more and better-managed data
* 				Can respond quickly to changes in end users environment
* 			Improved data security
* 				More access, greater risk of breaches
* 				Framework for better enforcement of data privacy and security policies
* 			Minimized data inconsistency
* 				**Data inconsistency** exists when different version of the same data appear in different places
* 				Probability of data inconsistency is greatly reduced in a properly designed database
* 			Improved data access
* 				Quick answers to ad hoc queries
* 				**Query** is a request for data manipulation
* 				Query is a question, adhoc query is a spur-of-the-moment quest
* 					Answer is called **query result set**
* 			Improved decision making
* 				**Data quality** is a comprehensive approach to accuracy, validity, timeliness
* 			Increased end-user productivity
*		Types of databases
*			Single-user database - one user at a time, if on a desktop it's a **desktop database**
*			Multi-user database - multiple users at a time 
*				**workgroup database** - single department
*				**enterprise database** - across many departments
*			Single site location - **centralized database**
*			Multiple site - **distributed databases**
*			**cloud database** - created/maintained via Azure, AWS
*			**general purpose** - wide varierty of data in multiple disciplines
*				Examples
*					Census
*					LexisNexis
*					ProQuest
*			**Discipline-specific** - focused on specific subject areas
*			**Operation database** - support day-to-day operations
*				AKA
*					**online transaction processing (OLTP) database**
*					**transactional database**
*					**production database**
*			**Analytical database** - strong historical data/business metrics
*				Forecasts
*				Market strategies
*				**advanced analysis of business data**
*				Two components
*					**data warehouse** - stores data in optimized format
*					**Online analytical processing (OLAP)** - tools to provide data analysis
*					**business intelligence** - approach to capture and process business data to support business decision making
*			**Unstructured data** - data in raw state
*			**Structured data** - result of formatting unstructured data
*			**Semi-structured** - already processed to some extent
*			**Extensible Markup Language (XML)** - language used for textual format
*			**XML Database** storage/management of semistructured XML data
*			**NoSQL (Not only SQL)** - describes new generation of database management not based on traditional relational database model. Handle volume, variety, structures and velocity well.
*	Why Database Design is important
*		**Database design** -activities that focus on design of database structure used to store/manage end-user data
*	**Problems with File System Data Processing**
*		Lengthy development times
*		Difficulty getting quick answers
*		Complex system administration
*		Lack of security and limited data sharing
*		Extensive programming
*	Structural and Data Dependence
*		**structural dependence** - file is dependent on its structure
*		**Structural independence** - Can change the file structure without affecting the application's ability to acces the data
*		**Data dependence**  - Data access programs are subject to change when any of the file's data storage characteristics change
*		**Data independence** - Change data storage characterists without affecting hte program's ability to access the data
*		**Logical data format** - How the human being views the data
*		**Physical data format** - How the computer must work with the data
*		**Data redundancy** - data occurs unneccesarily in different places
*		**Island of information** - Storaage of the same basic data in different locations
*		Uncontrolled data redundancy sets the stage for the following:
*			Poor data security
*			Data inconsistency
*			Data-entry errors
*			Data integrity problems
*		**data anomoly** - Not all required changes in the redundant data are made succesfully
*			Update anomalies
*			Insertion anomalies
*			Deletion anomalies
*	**Database systems**
*		Database system refers to an organization of components that define/regulate the collection/storage/management/use of data within database environment
*		Five components
*			Hardware
*			Software
*				Operating system
*				DBMS Software
*				Application programs and utility software
*			People
*				System admin
*				Database admin
*				Database designer
*				System analyst and programmers
*				End users
*			Procedures
*			Data
*		DBMS Functions
*			Data dictionary management
*				Data dictionary - stores definitions of data elements and relationships
*				Data storage management - Creates/manages complex structures for storage
*					Performance tuning - make the database perform more efficiently (speed/access)
*				Data transformation and presentation
*					Ex. Showing the date in UK vs US (11/07/2017 vs 07/11/2017 for July 11th, 2017)
*				Security management
*				Multiuser access control
*				Backup and recovery management
*				Data integrity management
*				Database access languages and application programming interfaces
*					**query language** - nonprocedural language - specify what must be done without having to specify how
*					**SQL (Structured Query Language)** - de facto query language
*				Database communication interfaces
*					Generate answers to queries
*					DBMS automatically publish predefined reports to a website
*					DMBS can connect to third-party system to distribute information via email/other applications
*	**1.9 Summary** 
*		Data consists of raw facts
*		Data stored in database
*		Design defines the structure
*		Database classified according to number of users, where located, type of data, intended usage, degree of structure
*		Evolved from manual and then computerized file systems
*		Limitations
*			Extensive programming
*			system administration complex/difficult
*			Making changes to existing structures is difficult
*			Security less than adequate
*			Independent files tend to contain redundant data
*			Management systems developed to address the file system's inherit weakness.
* **Data Modeling**
* 	**Data modeling** - process of creating a specific data model for a determined problem domain
* 		Simple, graphical representation of more complex real-world data structures
* 	**entity** - a person, place, thing or event which data will be collected and stored
* 	**attribute** - characteristic of an entity
* 	**relationship** - describes an association among entities
* 	**One-to-many (1:M or 1..*)* relationship** - Painter creates many paintings, but each is painted by only one painter
* 	**Many-to-many (M:N or *..*) relationship** - Employee learns many job skills, each skill learned by many employees
* 	**One-to-one (1:1 or 1..1) relationship** - Company needs 1 manager per store. Each store has 1 manager
* 	**Constraint** - restriction placed on the data
* 		Examples
* 			Salary must be between x and x
* 			Student's GPA must be between 0.00 and 4.00
* 			Each class must have one and only one teacher
* 	**business rule** - a brief, precise, and unambiguous description of a policy, procedure, principle within a specific organization.
* 		Misnamed - apply to any organization, large or small, business government unit, religious group, research lab that stores or uses data to generate information
* 		Derived rendered in writing and updated to reflect any change in the orgs operational environment
* 		Define entities, attributes, relationships and constraints
* 		Examples
* 			Customer may generate many invoices
* 			Invoice is generated by only one customer
* 			Training session cannot be scheduled for fewer than 10 employees or for more than 30 employees
* 		Process  to identifying and documenting business rules are essential for several reasons:
* 			Standardizing company's view of data
* 			Communication tool between users and designers
* 			Allow designer to understand nature, role and scope of the data
* 			Allow desinger to understand business processes
* 			Allow designer to develop relationship participation and constrains, create an accurate data model
* 		Noun - Entity
* 		Verb - relationship
* 		**relationships are bidirectional** - 1:M is the same as M:1
* 		**naming conventions**
* 			Descriptive of the objects and terminology familiar to the users
* 			Name should be descriptive of hte data represented by the attribute
* 			Prefix the name of an attribute with the name or abbreviation of the entity in which it occurs
* 				CUSTOMER entity, credit limit may be called CUS_CREDIT_LIMIT
* 	**heirachical model** - represented by an upside-down tree
* 		contains levels or **segments** (equivalent of a file system's record type).
* 		depicts a set of one-to-many (1:M) relationships between a parent and its children segments
* 	**network model** - created to represent complex data relationships more effectively than the heirarchical model to improve performance and impose a database standard. **1:M** relationships
* 		Allows a record to have more than one parent
* 		Concepts used today
* 			**schema** - conceptual organization of the entire database as viewed by the DB admin
* 			**subschema** - portion of the database "seen" by the application programs that produce information from the data within the database
* 			**DML (data manipulation language)** - defines the environment in which data can be managed, used to work with the data in the database
* 			**DDL (Data definition language)** - enables the DB admin to define the schema components
* 	**relational model**
* 		represented a major breakthrough for users and designers
* 		**relation/table** - two-dimensional structure composed of intersecting rows/columns
* 			each row called a **tuple**
* 			each column represents an attribute
* 		describes a precise set of data manipulation constructs based on advanced mathematical concepts
* 		**RDBMS (relational database management system)**
* 			performs the same basic functions provided by the heirarchical and network DBMS in addition to a host of other functions that make the relational data model easier to understand and implement
* 			**ability to hide complexity of the model from the user**
* 				RDMS manages all the physical details
* 				user sees the database as a collection of tables
* 				user can manipulate and query the data in a way that seems intuitive and logical
* 			**relational diagram** - representation of the relational database's entities
* 				Application involves three parts
* 					End user interface
* 					Collection of tables stored in the database
* 					SQL Engine
* 			**Entity Relationship Model** (ERM)
*			**Hadoop** - Java based, open source, high spee,d fault-tolerant distrubuted storage and computational framework
*			**HDFS** - highly distributed, fault tolerant storage system designed to manage large amounts of data at high speeds.
*			**MapReduce** - open source app interface that provides fast data analytics services
Chapter 3
* Relational Table
	* A table is perceived as two-dimensional structure composed of rows and columns
	* Each row (**tuple**) single entity occurrence within the entity set
	* Column represents attribute, each column has a distinct name
	* All values in the column must conform to the same data format
	* Each column specific range of values (attribute **domain**)
	* Order is immaterial to the DBMS
	* Each table must have an attribute or combination of attributes that uniquely indentifies each row
* **Key** consists of one or more attribute(s) that determine other attributes
* **Determination** - state in which knowing the value of one attribute makes it possible to determine the value of another
* **Functinoal dependence** - value of one or more attributes determines the value of one or more other attributes
* **Determinant** - attribute whose value determines another
* **Dependent** - attribute whose value is determined by another
* **Full functional dependence** - funtional dependencies which the entire collection of attributes in the determinant is necessasry for the relationship.

* **Types of keys**
*	**Composite key** - composed of more than one attribute
*	**key attribute** - an attribute that is a part of a key
*	**superkey** - key that can uniquely identify any row in the table, determines every attribute in the row
*	**candidate key** - minimal superkey (without any unnecessary attributes)
*	**Entity integrity** - condition in each row (entity instance)) in the table has its own unique identity
*	**null** - absence of any data value, never allowed in any part of the primary key
*	**foreign key** - primary key of one table that has been placed into another table to create a common attribute
*	**referential integrity** - condition which every reference to entity instance by another entity instance is valid
*	**secondary key** - a key that is used strgictly for data retrieval purposes
* **Referential integrity**
*	Following rules are in place to avoid incorrect reference
*		Delete rules
*		Insert rules
*		Update rules
*	**Cascade delete rule**
*		If an attempt is made to delete a record in one table where one or more records with matching foreign key values exist in another table, all associated records will be deleted
*	**Restrict delete rule**
*		If an attempt is made to delete a record in one table where one or more records with matchin foreign keys exist in another table, delete operation not allowed
*	**Set-to-null delete rule**
*		If an attempt is made to delete a record in one table where one or more records with matching foreign key values exists in another table, foreign key values are set to NULL so we know that the record they used to point to has been deleted.
* **Integrity rules**
* **Entity integrity**
*	Requirment - primary key entries are unique, no part of the key may be null
*	Purpose - Each row will have a unique identity, foreign key values can be properly referene primary key values.
*	Example - No invoice can have a duplicate number, nor can it be null; all invoices are uniquely identified by their invoice number
* **Referential integrity**
*	Requirement - foreign key may have a null entry as long as not part of its table's primary key or an entry that matches primary key value in table which it is related.
*	Purpose - Possible for attribute not to have corresponding value, impossible to have invalid entry.
*	Example - customer might not yet have an assigned sales representative (number), but it will be impossible ot have an invalid sales repressentative (number)
* **Relationships within the Relational Databse**
*	**composite entity** (aka bridge entity, associative entity)
*		used to link tables that originally related in an MN relationship
* 	**Linking table** - links tables together STUDENT - ENROLL - CLASS, implements M:M relationship
*	**index** - a orderly arrangment used to logically access rows in a table
*	**index key** - index's reference point
*	**unique index** - index key can only have one pointer value associated with it (row)
* **Relational Model of Data**
* **IMPORTANT: The Entity Relationship Model (ERM)**
