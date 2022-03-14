<h1> Case Prompt </h1>

<p> A friend of yours recently got promoted to the position of director of a university library. Yesterday, your friend received a call from the Ministry of Education, who offered him to be part of a national RFID pilot with his library. As your friend is unsure if he should pursue this option, he asks you for your advice.

Your task is to assess the RFID technology for his library. How would you approach such a request? </p>

<a href = "https://www.preplounge.com/en/management-consulting-cases/candidate-led-usual-style/intermediate/dhl-consulting-case-books-codes-77"> Case Source </a>

<p> Thank you for this very interesting case. I am glad I have the opportunity to solve it. 
I am going to recap the case based on my understanding, then I might ask some questions for clarifications
and to make sure we are on the same page. Finally, I will announce my approach for this problem. 
Does that sound okay? </p>

<p> So, our client is a recently promoted director of a university library. He was offered, by the MoE to join 
  the RFID pilot with his library. Our client needs advice whether or not to accept the offer and we need to asses the
  RFID technology for his library. </p>
  
  <p> Before we dive in, I would like to ask a question. Do we have any information if other libraries were
  offered this or not? And if they did, do we know if they accepted or rejected? </p>
  <p> I am familiar with the RFID technology, but may I ask you to briefly explain it to me, if possible? </p>
  
  <h3> Additional information </h3>
  <ul>
  
  <li> Radio-frequency identification (RFID) is the use of an electronic chip (RFID tag) applied to e.g. a product in order to identify and track it using radio waves. </li>
  <li> Latter is done by a RFID scanner </li>
  <li> RFID tags can be scanned over a wide range (~7 meters) </li>
  <li> RFID tags can be scanned in bulk </li>
  
  </ul>
  <p> Okay, can I get a couple of minutes to structure my approach and reach a promising solution? </p>
    
  <p> I believe the factors that we can look into are: cost, functionalities, risks </p>
  Costs:
  <ul>
  <li> Initial implementation costs </li>
  <li> Maintenance costs </li>
  <li> Training personnel (employees and users) costs </li>
  </ul>
  
  Functionalities:
  <ul>
  <li> Ease of use </li>
  <li> Benefits of the this technology such as faster barcode scanning and increases security </li>
  <li> Potential for longer openning hours </li>
  </ul>
  
  Risks:
  <ul>
  <li> New technology (might not be accepted or teething problems) </li>
  <li> System might not work </li>
  </ul>
  
</p>Okay so the current situation is that each book is scanned manually by an employee for lending or return.
  What RFID offers is automating the process and saving the overhead of the time and allows bulk checkouts. 
  It also might reduce the need for employees saving costs. </p>
  
 <p> Can I get more information about the library such as the working hours, number of items and how many visitors or users per day? </p>


Current system:

Barcode, each book scanned manually by employee for lending/ return


RFID pilot offer:

2 tiers: bulk checkout process conducted by employee (all books scanned at once) + automatic return process (for non opening hours)


Financial aspects of investment negligible (covered mostly by governmental ministry)


Library:

4 employees, working 8h a day
Media, mainly books: 900,000 books
20,000 students, 1,000 faculties, 100,000 inhabitants of city

![image](https://user-images.githubusercontent.com/47666430/158189109-8b4e9807-c9db-40d9-96af-5ac29e39a040.png)

I assume  we can save time at the lending and the return step.


Calculating time using barcodes:
- Assume 10 sec per book for checkout
- How many books are borrowed per year?
  - How many book for students:
  -       8 courses per semester, 2 books per course
  -       books borrowed by students per year = (8*2 + 8*2) * 20000 = 640,000
  - How many books for faculty:
  -       20 books per faculty per year
  -       books borrowed by faculty per year = 20*1000 = 20,000
  - How many books per inhabitants:
  -       2 books per inhabitant per year
  -       books borrowed by inhabitant per year = 2*100,000 = 200,000
  - Total borrowed books per year = 200,000 + 20,000 + 640,000 = 860,000
- Time spent on yearly basis:
  - 8,600,000sec = 143,333min = 2,388h = 298.5 FTE (full time employees) days (assumption: 8h working time/day)
  - Auxiliary calculation FTE days per year:
      365 days - 52*2 weekend days - 30 vacation days - 10 public holidays = 221 FTE days / year and FTE

Calculating time using RFID:
- Key question: How many borrowers per year?
Who borrows books?

Students (20,000)
Faculty (1,000)
Inhabitants of city (100,000)
Detailed computation for students :

Ceteris paribus assumptions of barcode computation
Books borrowed by students per year = (8*2 + 8*2) * 20,000 = 640,000
Each time a student borrows 4 books at once when she goes to the library (assumption)
Borrower per year from students = 640,000 / 4 = 160,000
The interviewee could doublecheck this by evaluating whether the implicitly assumed number of library visits per student is plausible or not. In this case the implicity assumed number of library visits is 160,000 / 20,000 (#students) = 8 per year. This sounds reasonable.

Detailed computation for faculty (simplified):

4 library visits per faculty per year
Borrower per year from faculty =4 * 1,000 = 4,000
Detailed computation inhabitants (simplified assumption):

2 library visits per inhabitant per year
Borrower per year from inhabitants: 100,000 * 2 = 200,000
Total number of borrowers books per year:

= 160,000 + 4,000 + 200,000 = 364,000

- Total duration of process on yearly basis:
= 364,000 borrowers * 10sec = 3,640,000sec

= 60,666min = 1,011h = 126.5 FTE days (assumptions c.p.)

Calculated in FTE (Full-time employees) you need 0.57 FTE to carry out this new checkout process throughout the year.

Recommendations:

Based on the pure time savings it is highly recommended to switch to RFID. 
The library can save almost one entire FTE which equals ~30,000 EUR per year in savings 
(assumed salary: 30,000 EUR + social insurance). 
In addition it is highly likely that the perceived service quality will be better at the same time; 
e.g. due to possible returns during non-opening hours (as indicated in the SWOT analysis).













