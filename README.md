# gwt-javax-persistence
GWT Module required if you use javax.persistence annotations in objects that are compiled to Javascript

Instructions to use: 
1.Download lib/hibernate-jpa-2.1-api-1.0.0.final-sources.jar and add it to your GWT project classpath
2.Download src/javax/Persistence.gwt.xml and add it to your sources so that it is located in "javax" package
3.Include following in your *.gwt.xml file: 

<pre><code>
    <module> 
       <inherits name='com.google.gwt.user.User'/>
       <inherits name='javax.Persistence'/>
</code></pre>
