# Interview Preparation

* The STAR (or STARR) method should be used where possible with these questions and answers

## DevOps

* **Insert modified Elevators Pitch here**, should include what DevOps is and why DevOps in the first place
	* Check the why DevOps section in this, maybe  rewrite third paragraph

Hello, my name is Amaan Hashmi-Ubhi and I've recently graduated with a BSc in Biomedical Science from the University of Birmingham, where I undertook a year in computer science. I have been using Linux for around 4 years, 3 of those exclusively and have found that my interests lean towards computing rather than medical research, mainly because I can learn and practice from home which is not currently possible in my area of medical research.

I have built my PC which uses Arch Linux and have a server running Fedora Server Edition of an old laptop, which I run BOINC, seed Linux distributions and use as a remote backup; with many exciting projects to come. I have been running Fedora to familiarise myself with RedHat distributions that are common throughout the industry whilst being rolling-relase so it is reasonably up-to-date, whereas I use Arch as you build it from the ground up and get to know many aspects of Linux which excites me.

My skills currently focus on the operations side of computing, though I am enthusiastic about moving into DevOps because of its often tight integration with Linux and the opportunity to learn new tools and ways of thinking, as well as bridging the historically large gap between software and operations. DevOps also focuses on automation and efficiency that I am keen to embrace as I have in the past, by making shell scripts that update my vim plugins, for example.

Additionally, I have developed a variety of soft skills such as conflict resolution and decision making throughout my university career due to securing leadership roles as treasurer, chair and teaching assistant in a Kung Fu Society and the CTO in the Birmingham Medical Research Society.

## Agile And Scrum

* **What is Agile?**
	* Agile is an iterative approach to project management and software development that helps teams deliver value to their customers faster and with fewer headaches. Instead of betting everything on a "big bang" launch, an agile team delivers work in small, but consumable, increments. Requirements, plans, and results are evaluated continuously so teams have a natural mechanism for responding to change quickly.
		* **Manifesto for Agile:**
			* Individuals and interactions over processes and tools
			* Working software over comprehensive documentation
			* Customer collaboration over contract negotation
			* Responding to change over following a plan
* **What is Scrum?**
	* Scrum is a framework that helps teams work together, which encourage them to learn through experiences, self-organisation whilst working on a problem, and reflection on their wins and losses to continuously improve.
		* *Values:*
			* Courage to do the right thing and work on tough problems
			* Focus on the work of the sprint and the goals of the Scrum team
			* Commitement to achieving the goals of the Scrum team
			* Respect each other to be capable, independent people
			* Openness about all work and challenges with performing the work to the team and stakeholder
* **Difference between Agile and Scrum?**
	* Agile is a model of continuous iteration of development and testing whereas Scrum is a methodology that is an implementation of Agile that focuses on delivering the business value in the shortest amount of time.
* **What are the 3 amigos?**
	* Primary perspectives to examine an increment of work before, during, and after development. These include:
		* *Business*:
			* What problem are we trying to solve?
		* *Devlopment*:
			* How might we build a solution tp solve that problem?
		* *Testing*:
			* What could possibly happen?
	* *Benefits:*
		* Shared understanding about the intent of an increment of work
		* Identifies misunderstandings and confusion early and allows learning to happen sooner in the delivery of an increment of work
		* Provides a limit to the number of people who should be involved in discussions about any given increment of work
* **What are personas in Scrum?**
	* Essentially detailed, synthetic biographies of fictitious users of a future product
	* *Benefits:*
		* Provide an anchor for justifying design choices, put emphasis on goals and behaviours
* **What are Scrum artifacts, Scrum roles?**
	* **Roles:**
		* *Development team members*
			* Those that do the work to make the project. Can include designers, programmers etc
		* *Product owner*
			* Sets clear direction of the project. Understand the customer and have a vision for the value the scrum team is delivering the customer
		* *Scrum master*
			* Servant leader, help product owner understand and communicate values
			* Encourage self-organisation in the development team
			* Maintain the values of the Scrum
* **What are Sprints and Sprint Reviews?**
	* *Sprints:*
		* Time box during which a "done", usable, potentially releasable increment is created
	* *Sprint Reviews:*
		* Held at the end of the sprint to inspect the increment and adapt the 'product backlog' (ordered list of everything that is known to be needed in the product .i.e. requirements to do the project) if needed
* **User and Epic Stories?**
	* *User Stories:*
		* A user story is the smallest unit of work in an agile framework, though they can be used in other methodologies. It is often an end goal expressed from the software user's perspective.
			* *Benefits:*
				* Keeps focus on user
				* Enable collaboration as end goal defined
				* Drive creative solutions, encourages critical thinking
				* Create momentum, lots of small wins
	* *Epic Stories:*
		* In short, an epic is a body of work that can be broken down into specific tasks (user stories) based upon the needs and requests of customers or end users. They can be a helpful way to organise work and create a hierarchy so that work can be broken down into shippable pieces so that large projects can get done on time and can continue to be shipped to customers on a regular basis.
* **Difference between and use cases between V-model, Waterfall, and Agile?**

## SQL Questions (Potential)

* **What is a foreign key?**
	* Primary key in a secondary table (which builds the relationship to the primary table)
	* Can repeat many times (no uniqueness constraints)
	* *When used?:*
		* Situation - A couple of tables containing product details, customer details, orders etc
		* Task - Print out all relevant order details (.i.e. products ordered) with the customers grouped by a column (city?)
		* Action - Found where the tables connected, with foreign keys, and what columns I needed to print out
		* Result - Used the foreign key to join multiple tables together with INNER JOIN (as didn't need or want NULL values), outputted the relevant columns in the SELECT portion and used a GROUP BY statement to group by City
		* Reflection - it is easy to do when you can visualise where each table connects where, would spend more time on this in the future so the query can be made quicker with less trial and error
* **What is DML and DDL?**
	* DML (data manipulation language) is more to do with the actual data on the table. Includes commands such as:
		* SELECT
		* INSERT
		* UPDATE
		* DELETE
	* DDL (data definition language) defines tables and the structure of a database. Commands include:
		* CREATE
		* ALTER
		* DROP
		* TRUNCATE

## Python Questions (Potential)
* **What is OOP and the four pillars?**
	* OOP - Object-oriented programming (OOP) is a programming paradigm based on the concept of "objects", which can contain data and code: data in the form of fields (often known as attributes or properties), and code, in the form of procedures (often known as methods)
	* *Four Pillars:*
		* Abstraction:
			* Abstraction is the process of showing only essential/necessary features of an entity/object to the outside world and hide the other irrelevant information. For example to open your TV we only have a power button, It is not required to understand how infra-red waves are getting generated in TV remote control
		* Encapsulation:
			* Encapsulation means wrapping up data and member function (Method) together into a single unit i.e. class. Encapsulation automatically achieve the concept of data hiding providing security to data by making the variable as private and expose the property to access the private data which would be public
		* Inheritance:
			* The ability of creating a new class from an existing class. Inheritance is when an object acquires the property of another object. Inheritance allows a class (subclass) to acquire the properties and behavior of another class (super-class). It helps to reuse, customize and enhance the existing code. So it helps to write a code accurately and reduce the development time
		* Polymorphism:
			* Polymorphism is derived from 2 Greek words: poly and morphs. The word "poly" means many and "morphs" means forms. So polymorphism means "many forms". A subclass can define its own unique behavior and still share the same functionalities or behavior of its parent/base class. A subclass can have their own behavior and share some of its behavior from its parent class not the other way around. A parent class cannot have the behavior of its subclass
* **Example of when you implemented OOP?**
	* Situation - Had a database, wanted some information of it
	* Task - Create a file with a method to get the average number of units in stock from a table, and use another file to essentially run this method
	* Action - Created first file with constructor etc and used `pyodbc` to connect to the database.
		* Created a methoid with an SQL statement to calculate the average UnitsInStock and print only this, with everything in a `try except` section
		* Create second file that inherits from this class (with relevant constructor), and instantiate an object and run the method to test (Abstraction, and Inheritance)
	* Result - Did all this
	* Reflection - Maybe have an interface of some sort in the file that does the inheriting to make it easier for the user to use, though all the main requirements was met, so this could be a second iteration
* **What is TDD and how you used it?**
	* First write the tests, then write the code to the tests, then in the next iteration make more tests and the more code etc until releasable
		* Reduce the risk of failure before sending a product to production
	* Situation - testing how to use pytest and unittest in Python
	* Task - Create a simple application to test if a number is positive and if a number is fully divisible (.i.e. no remainder) as separate functions
	* Actions - Created a test file, wrote the tests for a these functions using `assertTrue` and `assertFalse` given that planned for the functions that testing would return `True/False` answers. Tested, failed as should, then created the functions based on the behaviours decided on these tests
	* Results - Worked after the main functions implemented. Added some extra tests to check different cases within these test functions (checking both true and false answers)
