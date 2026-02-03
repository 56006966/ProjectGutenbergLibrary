# Project Gutenberg Library

### Table of Contents
[I. Description and README](https://github.com/56006966/ProjectGutenbergLibrary/main/README.md#i-description-and-readme)

[II. Wireframe solution architecture diagrams - DRAFT](https://github.com/56006966/ProjectGutenbergLibrary/main/README.md#ii-wireframe-solution-architecture-diagrams-DRAFT)

[III. User Stories](https://github.com/56006966/ProjectGutenbergLibrary/main/README.md#iii-user-stories)

[IV. Initial Use Cases](https://github.com/56006966/ProjectGutenbergLibrary/main/README.md#iv-initial-use-cases)

[V. Use Case Diagrams](https://github.com/56006966/ProjectGutenbergLibrary/main/README.md#v-use-case-diagrams)


I. Description and README
-------------------------

In this paper, I will be specifying the key parts that I am proposing for my project. With this project, I would be creating a mobile application for an interactive library interface by using the free website Project Gutenberg as a database. I specifically chose this website because they do not have a designated application for their website as it is accessible for mobile-device view and e-reader view with accompanying downloadable PDF files. This would be an example of a database GUI.

I will create script that reads the website and lists the books in the application. The book will be downloaded from the website and saved locally on the device. The app will then present the book in an e-reader format, like Amazon Kindle. The app will have multiple views for different devices including computers, tablets, and phones. I'd also like to incorporate accessibility features so that text size can change and read aloud the text, and at a minimum include a dark mode.

When you first launch the app, it will reflect the website homepage where the Newest Releases will always appear on the top shelf. The second shelf will have the Most Popular books. The books lined up on shelves that will scroll horizontally. From there you can filter the shelves by genre or search for a book by name or author.

I would also like to have a floating navigation bar that, when clicked on, displays the About, Frequently Downloaded, Main Categories, Reading Lists, and Search Options tabs. The About section of the navigation menu has a sub menu with: Contact Us, History & Philosophy, Kindles & eReaders, Help Pages, Offline Catalogs, and Donate. Donate and PayPal buttons will launch a browser to these designated websites.

II. Wireframe solution architecture diagrams - DRAFT
----------------------------------------------------
![Wireframe 1](https://github.com/56006966/ProjectGutenbergLibrary/blob/main/wireframe1.drawio.png "Wireframe Diagram 1")
![Wireframe 2](https://github.com/56006966/ProjectGutenbergLibrary/blob/main/wireframe2.drawio.png "Wireframe Diagram 2")
![Wireframe 3](https://github.com/56006966/ProjectGutenbergLibrary/blob/main/wireframe3.drawio.png "Wireframe Diagram 3")
![Wireframe 4](https://github.com/56006966/ProjectGutenbergLibrary/blob/main/wireframe4.drawio.png "Wireframe Diagram 4")

III. User Stories
-----------------

1. As a Developer, I want/need a floating navigation bar, so that when clicked on, it displays the About, Frequently Downloaded, Main Categories, Reading Lists, and Search Options tabs   

2. As a Customer, I want/need dark mode and text scalability, so that it incorporates accessibility features so that text size can change, be read aloud, and at a minimum include a dark mode.               

3. As a Developer I want/need the app will have multiple views, so that the app will have multiple views for different devices including computers, tablets, and phones

4. As a Developer I want/need The About section of the navigation menu has a sub menu so that The About section of the navigation menu has a sub menu with: Contact Us, History & Philosophy, Kindles & eReaders, Help Pages, Offline Catalogs, and Donate.     

5. As a Developer I need the app to present the book in an e-reader format, so that I will create script that reads the website and lists the books in the application. The book will be downloaded from the website and saved locally on the device. The app will then present the book in an e-reader format, like Amazon Kindle.

IV. Initial Use Cases
---------------------

1. Brief description (or title): Floating navigation bar

The [relevant] system: Floating navigation bar menu

The actor(s) including those initiating or responding to events: When clicked on, it displays the About, Frequently Downloaded, Main Categories, Reading Lists, and Search Options tabs

Scenario usually will include the pre-existing conditions and (all) relevant action sequences: The About section of the navigation menu has a sub menu with: Contact Us, History & Philosophy, Kindles & eReaders, Help Pages, Offline Catalogs, and Donate.

Expected result:A fully functional floating navigation bar that when clicked on, it displays the About, Frequently Downloaded, Main Categories, Reading Lists, and Search Options tabs.

2. Brief description (or title): Script

The [relevant] system: Mobile application API script

The actor(s) including those initiating or responding to events: The script that reads the Project Gutenberg website and lists the books in the application. The book will be downloaded from the website and saved locally on the device.

Scenario usually will include the pre-existing conditions and (all) relevant action sequences: The book will be downloaded from the website and saved locally on the device.

Expected result: A full functional script that reads the Project Gutenberg website and lists the books in the application. The book will be downloaded from the website and saved locally on the device.       

3. Brief description (or title): Multiple views

The [relevant] system: Multiple views for different devices

The actor(s) including those initiating or responding to events: The app will have multiple views for different devices including computers, tablets, and phones.

Scenario usually will include the pre-existing conditions and (all) relevant action sequences: The app will have multiple views for different devices including computers, tablets, and phones.

Expected result: The book will be downloaded from the website and saved locally on the device. The app will then present the book in an e-reader format, like Amazon Kindle. The app will have multiple views for different devices including computers, tablets, and phones. 

4. Brief description (or title): Scrolling shelves

The [relevant] system: Horizontal scrolling shelves filtered by genre

The actor(s) including those initiating or responding to events: The books are lined up on shelves that will scroll horizontally.

Scenario usually will include the pre-existing conditions and (all) relevant action sequences: The books are lined up on shelves that will scroll horizontally.

Expected result: When you first launch the app, it will reflect the website homepage where the Newest Releases will always appear on the top shelf. The second shelf will have the Most Popular books. The books are lined up on shelves that will scroll horizontally.             

5. Brief description (or title): Advanced Search filtering

The [relevant] system: Advanced Search filtering

The actor(s) including those initiating or responding to events: Advanced Search filtering for fields such as Author, Title, Subject, Subject Areas, Language, Datatype, and Filetype.

Scenario usually will include the pre-existing conditions and (all) relevant action sequences: Advanced Search filtering for fields such as Author, Title, Subject, Subject Areas, Language, Datatype, and Filetype.

Expected result: From there you can filter the shelves by genre or search for a book by name or author.

V. Use Case Diagrams
--------------------
![Floating Navigation Bar Use Case Diagram](https://github.com/56006966/ProjectGutenbergLibrary/blob/main/usecasediagram1.png "Use Case Diagram 1")
![Advanced Search Use Case Diagram](https://github.com/56006966/ProjectGutenbergLibrary/blob/main/usecasediagram2.png "Use Case Diagram 2")
