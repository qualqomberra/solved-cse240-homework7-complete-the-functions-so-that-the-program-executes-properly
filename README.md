Download Link: https://assignmentchef.com/product/solved-cse240-homework7-complete-the-functions-so-that-the-program-executes-properly
<br>
<strong>Reading</strong>: Textbook Chapter 2, Section 2.5.4 on linked list and Section 2.6 on parameter passing and Section 2.10.

<strong>Preparation</strong>: Complete the multiple choice questions in the textbook exercise section. The answer keys can be found in the course Web site. These exercises can help you prepare for your weekly quiz and the exam. You are encouraged to read the other exercise questions and make sure you understand these questions in the textbook exercise section, which can help you better understand what materials are expected to understand after the lectures and homework on each chapter.

You are expected to do the majority of the assignment outside of class meetings.   Should you need assistance, or have questions about the assignment, please contact the instructor or TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board.  However, <strong>do not share your answers and code</strong> in the course discussion board.

<h1>Homework Description</h1>

The following figure shows an instance of the linked list that you will be building and managing in these two homeworks. The node of the main linked list ‘list’ is called libraryList, which contains two members: (1) book member is a pointer to the book node, (2) a pointer to next libraryList node. The book node contains three members: (1) book title, (2) aisle number, and (3) a pointer to bookType list. The node in the bookType list has two members: (1) book type (2) a pointer to next bookType node.

HW 7 Programming Assignment

You are given a partially completed program hw7.c. You should follow the instructions given in the program to complete the functions so that the program executes properly. You will be completing a program that creates a list of books. It is a menu driven program where user is given following options:

<ol>

 <li>Add an book’s information (Book title and aisle number) is already implemented. The new book is added to the head of the linked list. We do not ask user for bookTypes to add in this function. So simply NULL is assigned to *bookType member of the ‘book‘ node when a new book is added to the list in this function. (Note: *bookType is used in further functions)</li>

 <li>Display the book list is already implemented. This function prints each book’s title and aisle number. It does not print bookType of the book.</li>

</ol>




<strong>These functions need to be implemented: </strong>

<ol>

 <li>Search a book in the list by book title. It prints if the book exists on the list or not. This function should return the ‘book‘ node if that book is found in the list, else return NULL. It is used as a helper function in executeAction() to check if the book exists in the list.</li>

</ol>




The next part focuses on using ‘bookType’ linked list. In this part, the user should be able to use the following menu options:

<ol>

 <li>Add a bookType to an book’s profile. This function assumes that the book is added in the list and assigns book type using the *bookType member of ‘book’ node. You may add the new bookType to the head or tail of the ‘bookType’ linked list. (Sample solution adds the bookType to the tail)</li>

 <li>This function prompts the user to input a book type. Then it displays the list of books that have the entered book type only. Lastly, it should display the number of books that met this requirement. This function should display both book’s title and aisle number. See expected output below.</li>

 <li>Removes the book from the list. This function removes the book’s title, aisle number and bookType list of the book when removing the book from the list.</li>

</ol>




Expected outputs:




<h2>addBook (already implemented)</h2>

<h2>displayLibraryList (already implemenetd)</h2>

<strong> </strong>

(New books are added to the head of ‘list’. So newer books appear first. Not necessary to print ‘end of list’ message.)

<strong> </strong>

<h2>searchBook (5 points)</h2>




<strong> </strong>

<strong>             </strong>

<strong>             </strong>

<h2>addBookType</h2>

<strong> </strong>




<h2>displayBookTypeList</h2>




<strong> </strong>( Sapiens recently added book type as ‘Nonfiction’ which was added to tail of her *bookType list. So, it’s name appears when ‘l’ option is used ).

<strong> </strong>

<strong> </strong>

<h2>removeBook</h2>




<strong> </strong>

(After removing a book, you should use the display option to verify it functioned correctly)

<strong>What to Submit</strong><strong>? </strong>