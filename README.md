# programming-techniques-assignment-2--queues-simulator-solved
**TO GET THIS SOLUTION VISIT:** [Programming-Techniques Assignment 2 –Queues Simulator Solved](https://www.ankitcodinghub.com/product/programming-techniques-assignment-2-queues-simulator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97135&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming-Techniques Assignment 2 –Queues Simulator Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1. Requirements

Design and implement a simulation application aiming to analyse queuing based systems for determining and minimizing clients’ waiting time.

Queues are commonly used to model real world domains. The main objective of a queue is to provide a place for a “client” to wait before receiving a “service”. The management of queue-based system is interested in minimizing the time amount their “clients” are waiting in queues before they are served. One way to minimize the waiting time is to add more servers, i.e. more queues in the system (each queue is considered as having an associated processor) but this approach increases the costs of the service supplier. When a new server is added the waiting customers will be evenly distributed to all current available queues.

The application should simulate (by defining a simulation time 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛) a series of N clients arriving for service, entering Q queues, waiting, being served and finally leaving the queues. All clients are generated when the simulation is started, and are characterized by three parameters: ID (a number between 1 and N), 𝑡𝑎𝑟𝑟𝑖𝑣𝑎𝑙 (simulation time when they are ready to go to the queue; i.e. time when the client finished shopping) and 𝑡𝑠𝑒𝑟𝑣𝑖𝑐𝑒 (time interval or duration needed to serve the client by the cashier; i.e. waiting time when the client is in front of the queue). The application tracks the total time spend by every customer in the queues and computes the average waiting time. Each client is added to the queue with minimum waiting time when its 𝑡𝑎𝑟𝑟𝑖𝑣𝑎𝑙 time is greater than or equal to the simulation time (𝑡𝑎𝑟𝑟𝑖𝑣𝑎𝑙 ≥ 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛).

The following data should be considered as input data read from a text file for the application:

<ul>
<li>– &nbsp;Number of clients (N);</li>
<li>– &nbsp;Number of queues (Q);</li>
<li>– &nbsp;Simulation interval (𝑡 𝑀𝐴𝑋 );</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

<ul>
<li>– &nbsp;Minimum and maximum arrival time (𝑡 𝑀𝐼𝑁 𝑎𝑟𝑟𝑖𝑣𝑎𝑙</li>
<li>– &nbsp;Minimum and maximum service time (𝑡 𝑀𝐼𝑁 𝑠𝑒𝑟𝑣𝑖𝑐𝑒</li>
</ul>
</div>
<div class="column">
≤ 𝑡 𝑎𝑟𝑟𝑖𝑣𝑎𝑙

≤ 𝑡 𝑠𝑒𝑟𝑣𝑖𝑐𝑒

</div>
<div class="column">
≤ 𝑡 𝑀𝐴𝑋 ); 𝑎𝑟𝑟𝑖𝑣𝑎𝑙

</div>
</div>
<div class="layoutArea">
<div class="column">
The output of the application is a text file containing a log of the execution of the application and the average waiting time of the clients, as shown in the following example.

In-Test.txt Explanation

</div>
</div>
<div class="layoutArea">
<div class="column">
≤ 𝑡 𝑀𝐴𝑋 𝑠𝑒𝑟𝑣𝑖𝑐𝑒

</div>
<div class="column">
);

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

2

60 2,30 2,4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
The application reads from In-Test.txt the simulation parameters: N=4 clients, Q = 2 queues, 𝑡𝑀𝐴𝑋 = 60, a 60 second simulation

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
interval. It also reads the bounds for the client parameters, respectively a minimum and maximum arrival time 2, 30, meaning that clients will go to the queues from second 2 up to second 30. Furthermore, the bounds for the service time are read from the final line, 2 and 4, meaning that a client has a minimum time to wait in front of the queue 2 seconds and a maximum time of 4 seconds. Using these parameters, a set of 4 clients are generated random, each client

</div>
</div>
<div class="layoutArea">
<div class="column">
i being defined by the following tuple: (𝐼𝐷𝑖, 𝑡𝑖 ,𝑡𝑖

the following constraints:

</div>
<div class="column">
), with

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑎𝑟𝑟𝑖𝑣𝑎𝑙 𝑠𝑒𝑟𝑣𝑖𝑐𝑒

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
• 1≤𝐼𝐷𝑖≤𝑁

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>𝑡𝑀𝐼𝑁 𝑎𝑟𝑟𝑖𝑣𝑎𝑙</li>
<li>𝑡𝑀𝐼𝑁 𝑠𝑒𝑟𝑣𝑖𝑐𝑒</li>
</ul>
</div>
<div class="column">
≤ 𝑡𝑖 𝑎𝑟𝑟𝑖𝑣𝑎𝑙

≤ 𝑡𝑖 𝑠𝑒𝑟𝑣𝑖𝑐𝑒

</div>
<div class="column">
≤ 𝑡𝑀𝐴𝑋 𝑎𝑟𝑟𝑖𝑣𝑎𝑙

≤ 𝑡𝑀𝐴𝑋 𝑠𝑒𝑟𝑣𝑖𝑐𝑒

</div>
</div>
<div class="layoutArea">
<div class="column">
A number of Q threads will be launched to process in parallel the clients. Another thread will be launched to hold the simulation time 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 and distribute each client i to the queue with the smallest

waiting time when 𝑡𝑖 ≥ 𝑡

𝑎𝑟𝑟𝑖𝑣𝑎𝑙 𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
The output of the simulation is a text file containing the status of the pool of waiting clients and the queues as the simulation time 𝑡 goes from 0 to 𝑡𝑀𝐴𝑋 .

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
Out-Test.txt Explanation

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Time 0

Waiting clients: (1,2,2); (2,3,3); (3,4,3); (4,10,2) Queue 1: closed

Queue 2: closed

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
At time 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 = 0, a number of 4 clients are generated. Client with ID = 1 has an arrival time equal to 2, meaning that it will be ready to go to a queue when 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 ≥ 2. Furthermore, it has a service time equal to 2, meaning that is needs to stay 2 timesteps in the front of the queue.

The same rules apply for the next 3 clients.

The two queues are closed since there are not clients available.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Time 1

Waiting clients: (1,2,2); (2,3,3); (3,4,3); (4,10,2) Queue 1: closed

Queue 2: closed

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
At time 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 = 1, none of the clients can be sent to the queues because none of them has the arrival time greater or equal to 2.

The two queues are closed since there are not clients available.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Time 2

Waiting clients: (2,3,3); (3,4,3); (4,10,2)

Queue 1: (1,2,2);

Queue 2: closed

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Queue 1 is opened and client with ID =1 is sent to the first queue since 𝑡1 ≥ 𝑡 = 2.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑎𝑟𝑟𝑖𝑣𝑎𝑙 𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
Other clients are still waiting. Queue 2 is closed.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Time 3

Waiting clients: (3,4,3); (4,10,2)

Queue 1: (1,2,1);

Queue 2: (2,3,3);

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Queue 2 is opened time 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 = 3, client with ID = 2 is sent to it since 𝑡2 ≥ 𝑡 = 3, and the waiting time at the second

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑎𝑟𝑟𝑖𝑣𝑎𝑙 𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
queue (0) is smaller than the waiting time at the first queue (1), where a client is still processed.

The client from queue 1 has its service time decreased to 1 (coloured in yellow) because it is being processed.

Other clients are still waiting.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Time 4

Waiting clients: (4,10,2) Queue 1: (3,4,3);

Queue 2: (2,3,2);

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
At time 𝑡𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 = 4, client with ID = 3 is sent to the first queue since 𝑡3 ≥ 𝑡 = 4.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑎𝑟𝑟𝑖𝑣𝑎𝑙 𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
Furthermore, client with ID =1 was eliminated from the queue because its service time has dropped to 0 (it was 1 at the previous iteration and was decreased with one at the simulation step)

The client from queue 2 has its service time decreased to 2 (coloured in yellow) because it is being processed.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
An example of input/output files is the following: In-Test.txt

Out-Test.txt

</div>
</div>
<div class="layoutArea">
<div class="column">
The final client is still waiting.

</div>
</div>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Average waiting time

</div>
</div>
<div class="layoutArea">
<div class="column">
2.5

</div>
</div>
<div class="layoutArea">
<div class="column">
:

</div>
</div>
<div class="layoutArea">
<div class="column">
The simulation is finished when there are no more clients in the waiting queue or at the service queues or 𝑡 &gt; 𝑡𝑀𝐴𝑋

</div>
</div>
<div class="layoutArea">
<div class="column">
The average waiting time is computed and appended to the file.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛 𝑠𝑖𝑚𝑢𝑙𝑎𝑡𝑖𝑜𝑛

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

2

60 2,30 2,4

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Time 0

Waiting clients: (1,2,2); (2,3,3); (3,4,3); (4,10,2) Queue 1: closed

Queue 2: closed

Time 1

Waiting clients: (1,2,2); (2,3,3); (3,4,3); (4,10,2) Queue 1: closed

Queue 2: closed

Time 2

Waiting clients: (2,3,3); (3,4,3); (4,10,2) Queue 1: (1,2,2);

Queue 2: closed

Time 3

Waiting clients: (3,4,3); (4,10,2) Queue 1: (1,2,1);

Queue 2: (2,3,3);

Time 4

Waiting clients: (4,10,2) Queue 1: (3,4,3);

Queue 2: (2,3,2);

…

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Average waiting time: 2.5

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
1.2 Design considerations

• Use an object-oriented programming design

1.3 Implementation considerations

<ul>
<li>Use the Java programming language</li>
<li>Implement classes with maximum 300 lines</li>
<li>Implement methods with maximum 30 lines</li>
<li>Use the Java naming conventions (https://google.github.io/styleguide/javaguide.html)
2. Deliverables
</li>
</ul>
<ul>
<li>A solution description document (minimum 2000 words, Times New Roman, 10pt,
Single Spacing) with the structure specified in the Lab Description document.
</li>
<li>Source files – will be uploaded on the personal gitlab account created at the Lab
Resources Gitlab laboratory work, following the steps:

o Create a repository on gitlab named according to the following template

PT2020_Group_FirstName_LastName_Assignment_2

o Push the source code and the documentation (push the code not an archive with the code)
</li>
</ul>
o A PT2020_Group_FirstName_LastName_Assignment_2.jar file containing the project configured to run from the terminal and read 2 parameters: the name of the input file and the name of the output file. The application should permit to be run with the following command:

java -jar PT2020_Group_FirstName_LastName_Assignment_2.jar in.txt out.txt

<ul>
<li>Three test files (in-test-1.txt, in-test-2.txt, in-test-3.txt) and their corresponding outputs
(out-test-1.txt, out-test-2.txt, out-test-3.txt) for the following configurations: in-test-1.txt in-test-2.txt in-test-3.txt
</li>
<li>Share the repository with the user utcn_dsrl.</li>
</ul>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

2

60 2,30 2,4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
50

5

60 2,40 1,7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1000 20

200 10,100 3,9

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
3. Evaluation

The assignment will be graded as follows:

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Requirement

</div>
</div>
<div class="layoutArea">
<div class="column">
Grading

</div>
</div>
<div class="layoutArea">
<div class="column">
Minimum to pass

<ul>
<li>Object-oriented programming design</li>
<li>Classes with maximum 300 lines</li>
<li>Methods with maximum 30 lines</li>
<li>Java naming conventions</li>
<li>Random Client Generator</li>
<li>Multithreading: one thread per queue</li>
<li>One test run and saved: in-test-1.txt</li>
<li>.jar file uploaded and configured to run according to deliverable
requirement
</li>
<li>Appropriate synchronized data structures to assure thread safety (avoid
synchronized keyword as much as possible)
</li>
<li>Queues should open/close dynamically. Initially all queues are closed.
When clients are distributed to the queues, they become open as needed. When a queue becomes empty, it is closed, and the corresponding thread is paused.

•
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
5 points

</div>
</div>
<div class="layoutArea">
<div class="column">
Documentation

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Other two tests given in requirements (in-test-2.txt, in-test-3.txt)

Quality of documentation

Compute average waiting time

Other tests run when evaluating homework using the compiled code as .jar file uploaded and configured to run according to deliverable requirement

4. Bibliography

</div>
<div class="column">
1 point 2 points 1 point 1 point

</div>
</div>
<div class="layoutArea">
<div class="column">
– http://docs.oracle.com/javase/tutorial/essential/concurrency/index.html

– http://www.tutorialspoint.com/java/util/timer_schedule_period.htm

– http://www.javacodegeeks.com/2013/01/java-thread-pool-example-using-executors-and-

threadpoolexecutor.html

</div>
</div>
</div>
