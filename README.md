# java-lab-9-solved
**TO GET THIS SOLUTION VISIT:** [Java Lab 9 Solved](https://www.ankitcodinghub.com/product/java-lab-9-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95432&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Lab 9 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Persistence

Continue the application from lab 8, creating an object-oriented model and using JPA (Java Persistence API) in order to communicate with the relational database.

The main specifications of the application are: Compulsory (1p)

<ul>
<li>Create a persistence unit (use EclipseLink or Hibernate or other JPA implementation).

Verify the presence of the persistence.xml file in your project. Make sure that the driver for EclipseLink or Hibernate was added to to your project classpath (or add it yourself).</li>
<li>Define the entity classes for your model (at least one) and put them in a dedicated package. You may use the IDE support in order to generate entity classes from database tables.</li>
<li>Create a singleton responsible with the management of an EntityManagerFactory object.</li>
<li>Define repository clases for your entities (at least one). They must contain the following methods:</li>
</ul>
o create – receives an entity and saves it into the database;

o findById – returns an entity based on its primary key;

o findByName – returns a list of entities that match a given name pattern.

Use a named query in order to implement this method. • Test your application.

Optional (2p)

<ul>
<li>Add support for charts. A chart has a name, a creation date and an ordered list of movies.</li>
<li>Create a generic AbstractRepository using generics in order to simplify the creation of the repository classes. You may take a look at

the CrudRepository interface from Spring Framework.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>Implement both the JDBC and JPA implementations and use

an AbstractFactory in order to create the DAO objects (the repositories).</li>
<li>The application will use JDBC or JPA depending on a parameter given in an initialization file. (At least for one entity!)
Bonus (2p)
</li>
</ul>
• We say that two movies are related if they have the same director (for example). Each day you want to see exactly two movies and you want to create the longest possible playlist that satisfies the following constraints:

o each day you will watch two related movies;

o any two movies from different days cannot be related;

<ul>
<li>Implement an efficient algorithm (for a bonus+) or use one from a third -party
library, like JGraphT.
</li>
<li>Test your algorithm for large subsets of movies from your databa se and
describe the runtime performance in a suggestive manner.

Resources
</li>
</ul>
<ul>
<li>JPA Tutorial</li>
<li>Java EE Tutorial: Persistence</li>
<li>Java Persistence Performance</li>
</ul>
</div>
</div>
</div>
