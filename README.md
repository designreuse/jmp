JavaMail Pages Tag Library (JMP)
================================

Thanks for using JavaMail Pages Tag Library (JMP), a tag library based on
JavaMail API, and used for building JSP-based templates of JavaMail messages.

Using the Tag Library
---------------------

To use tag library with your own web applications, simply copy the JAR
files in the 'lib' directory (javaplus-jmp.jar)to your application's
WEB-INF/lib directory. Then, import the template tag library into your
pages with the following directives:

  <%@ taglib prefix="m" uri="http://www.javaplus.org/jmp" %>

or introducing a new namespace with the above URI in a JSP document
in XML syntax.

Rumtime Dependencies
--------------------

This version of JMP has the following runtime dependencies provided
by Java EE containers:

- JavaMail 1.4
- Servlet 2.4
- JSP 2.0
- JSTL 1.2 (needed by example web application)

WAR Files
---------

The following file is a standalone web application (WAR) in order to help
you to learn and use JMP. Deploy the application to your container, and
follow the examples to familiarize yourself with the usage of JMP.

  jmp-examples.war            Example application of JMP usage

Documentation
-------------

See documentation in 'docs/' directory for more information.

Building from Source Code
-------------------------

Download a source distribution. Build JMP from the source code with Maven.

Comment and Feedback
--------------------

Any comment, question and feedback should go to rogersuen@live.com.

Enjoy!
