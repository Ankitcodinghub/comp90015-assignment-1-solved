# comp90015-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [COMP90015 Assignment 1 Solved](https://www.ankitcodinghub.com/product/comp90015-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116104&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP90015 Assignment 1  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Problem Description

Using a client-server architecture, design and implement a multi-threaded server that allows concurrent clients to search the meaning(s) of a word, add a new word, and remove an existing word.

This assignment has been designed to demonstrate the use of two fundamental technologies that have been discussed during the lectures:

• Sockets

• Threads

Hence, the assignment must make an EXPLICIT use of the two above. By explicit, we mean that in your application, sockets and threads must be the lowest level of abstraction for network communication and concurrency.

Architecture

• The system will follow a client-server architecture in which multiple clients can connect to a (single) multi-threaded server and perform operations concurrently.

Interaction

• All communication will take place via sockets. These sockets can be either TCP or UDP, however, keep in mind that all communication between clients and server is required to be reliable.

Failure Model

• It is expected that, on both the server and the client side, errors (by means of exception handling) are properly managed. The errors include the following:

• Input from the console for what concerns the parameters passed as command line.

• Network communication (address not reachable, bad data…).

• I/O to and from disk (cannot find the dictionary file, error reading the file, etc…). • Other errors you might come up with.

The application will be tested and validated against all these errors.

Functional Requirements

• Query the meaning(s) of a given word

The client should implement a function that is used to query the dictionary with the following minimum (additional input/output parameters can be used as required) input and output:

Input: Word to search

Output: Meaning(s) of the word

Error: The client should clearly indicate if the word was not found or if an error occurred. In case of an error, a suitable description of the error should be given to the user.

• Add a new word

Add a new word and one or more of its meanings to the dictionary. For the word to be added successfully it should not exist already in the dictionary. Also, attempting to add a word without an associated meaning should result in an error. A new word added by one client should be visible to all other clients of the dictionary server. The minimum input and output parameters are as follows:

Input: Word to add, meaning(s)

Output: Status of the operation (e.g., success, duplicate)

Error: The user should be informed if any errors occurred while performing the operation.

• Remove an existing word

Remove a word and all of its associated meanings from the dictionary. A word deleted by one client should not be visible to any of the clients of the dictionary server. If the word does not exist in the dictionary then no action should be taken. The minimum input and output parameters are as follows:

Input: Word to remove

Output: Status of the operation (e.g., success, not found)

Error: The user should be informed if any errors occurred while performing the operation.

• Update meaning of an existing word

Update associated meanings of a word from the dictionary. If multiple meanings exist, all of them should be replaced by new meaning(s) provided by user. Update made by one client should be visible to any of the clients of the dictionary server. If the word does not exist in the dictionary, then no action should be taken. The minimum input and output parameters are as follows:

Input: Word to update, meaning(s)

Output: Status of the operation (e.g., success, not found)

Error: The user should be informed if any errors occurred while performing the operation.

User Interface

A Graphical User Interface (GUI) is required for this project. You are free to design it and to use any existing tools and libraries for this purpose.

Implementation Guidelines

These are guidelines only, you are allowed and encouraged to come up with your own design and interfaces.

• When the server is launched, it loads the dictionary data from a file containing the initial list of words and their meanings. These data is maintained in memory in a structure that enables an efficient word search. When words are added or removed, the data structure is updated to reflect the changes.

A sample command to start the server is:

&gt; java –jar DictionaryServer.jar &lt;port&gt; &lt;dictionary-file&gt;

Where &lt;port&gt; is the port number where the server will listen for incoming client connections and &lt;dictionary-file&gt; is the path to the file containing the initial dictionary data.

• When the client is launched, it creates a TCP socket bound to the server address and port number. This socket remains open for the duration of the client-server interaction. All messages are sent/received through this socket.

A sample command to start the client is:

&gt; java –jar DictionaryClient.jar &lt;server-address&gt; &lt;server-port&gt;

Implementation Language

The assignment should be implemented in Java. Utilization of technologies such as RMI and JMS are not allowed.

Report

You should write a report describing your system and discussing your design choices. Your report should include:

• The problem context in which the assignment has been given.

• A brief description of the components of the system.

• An overall class design and an interaction diagram.

• A critical analysis of the work done followed by the conclusions.

Please mind that the report is a WRITTEN document, do not put only graphs. A report without any descriptive text addressing the problem, architecture, protocols, and the analysis of the work done will not be considered valid.

The length of the report is not fixed. A good report is auto-consistent and contains all the required information for understanding and evaluating the work done. Given the level of complexity of the assignment, a report in the range of 4 to 6 pages is reasonable. Please mind that the length of the report is simply a guideline to help you in avoiding writing an extremely long or incomplete report.

It is important to put your details (name, surname, student id) in:

• The head page of the report.

• As a header in each of the files of the software project.

This will help to avoid any mistakes in locating the assignment and its components on both sides.

Submission

You need to submit the following via LMS:

• Your report in PDF format only.

• Two executable jar files (DictionaryClient.jar and DictionaryServer.jar) that will be used to run your system on the day of the demo.

• Your source files in a .ZIP or .TAR archive only.

Marking

The marking process will be structured by first evaluating whether the assignment (application + report) is compliant with the specification given. This implies the following:

• Use of TCP/UDP sockets and threads for the application;

• proper use of concurrency in the server;

• proper handling of the errors;

• a report with the requested content and format (PDF);

• timeliness in submitting the assignment in the proper format (names, directory structure, etc.).

Note 2: Don’t document anything you haven’t implemented in the report. This is misconduct and will result in severe penalties.

You are free to develop your system where you are more comfortable (at home, on one pc, on your laptop, in the labs…) but keep in mind that the assignment is meant to be a distributed system that works on at least two different machines in order to separate the client from the server.

If you need any clarification on the assignment, kindly ask questions during the tutorials or in the LMS forum, so that all students benefit from it.

Assignments submitted late will be penalized in the following way:

• 1 day late: -1 mark
