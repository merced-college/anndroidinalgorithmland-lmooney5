[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23175351)
# AnnDroidInAlgotihmLand
a sample project to practice sorting and searching

🎵 Download Required Audio File

This project uses an audio file that is too large to store directly in the GitHub repository.
Please download the file from Google Drive before running the program.

Download the audio file here:

➡️ Download the required audio file from Google Drive

Instructions

Open the Google Drive folder using the link above.

Download the ZIP file that contains the audio file.

Extract (unzip) the file on your computer.

Place the extracted audio file into the project folder named content.

Download all of the whole content folder, and put this in your project.

Name: Logan Mooneyham

3/17/26

This project has been difficult to set up in Eclipse so far, but it looks interesting.

Project setup completed successfully.

1. What types of files are located in the src folder?

The src folder contains the Java source code files (.java). These files define the logic of the program, including classes, methods, and the main application behavior.

2. What appears to be stored in the content folder?

The content folder stores assets used by the program, such as images, sounds, or other resource files. For example, files like splash.png are used by the program to display visuals.

3. What is the purpose of the uml folder?

The uml folder contains UML diagrams, which are visual representations of the program’s structure. These diagrams show how classes, methods, and relationships are organized in the project.

4. Why do software projects often separate code from content/assets?

Software projects separate code from content to keep the project organized and easier to manage. It allows developers to update images or other assets without changing the code, and it keeps the logic of the program separate from the resources it uses. This also makes collaboration easier since different team members can work on code and assets independently.

1. Which class contains the main() method?

The Main class contains the main() method. This is the entry point of the program where execution begins.

2. What does the program do when it first starts running?

When the program starts, it initializes the application and sets up the main user interface as well as creates the main window and loads the initial screen, which is typically the main menu. It may also load assets such as images that are needed for display.

3. What objects or classes are created when the program begins?

At startup, the program creates an AppRouter object, which manages switching between different screens, and a MainMenuPanel object, which represents the main menu interface. Also Asset-related objects (such as image loaders) to load resources like splash.png.

1. Which class appears responsible for drawing graphics?

The MainMenuPanel class appears responsible for drawing graphics. It handles displaying visual elements on the screen, such as images and menu components, using methods like paintComponent() to render the interface.

2. Which class appears responsible for loading files or content?

The Assets class is responsible for loading files and content. It includes methods (such as loadImage) that load resources like images. 

3. How does the game update what appears on the screen?

The game updates the screen by redrawing it whenever something changes. It refreshes the display so the player can see the updated graphics.

1. What does the UML diagram help you understand about the program?

The UML diagram helps show how the different classes are connected and organized. It makes it easier to understand the structure of the program and how different parts work together.

2. Which class appears to be the central class in the system?

The AppRouter class appears to be the central class because it controls which screens are shown and connects different parts of the program.

3. Which classes depend on or interact with other classes?

Classes like MainMenuPanel interact with other classes such as Assets to load images. The AppRouter interacts with multiple classes to switch between different screens. This shows that several classes depend on each other to run the program.

1. Where in the code are scores stored?

Scores are stored in ScoreEntry.java.

2. What data type is used to store scores?

Scores are stored using an integer data type (int). This makes sense because scores are whole numbers that increase as the player earns points.

3. Where would it make sense to implement sorting of scores?

It would make sense to implement sorting in LeaderboardPanel. 

1. In which class did you add the sorting code?

I added the insertion sort code to LeaderboardRepository.

2. Why did you choose that location?

Because it was the class that loads, stores, and manages the lost of scores. Other classes could represent one score or handle UI items, but not exactly what was needed. 

3. What data structure is being sorted?

Sorting operates on an ArrayList<ScoreEntry>. Each ScoreEntry contains the details of a single leaderboard record. The ArrayList allows dynamic resizing as new scores are added, and the insertion sort rearranges the entries in place in descending order by score.

1. Which sorting algorithm did you choose?

I chose Insertion Sort.

2. How does your algorithm work in your own words?

Insertion sort works like organizing a hand of playing cards: Start with the second element in the list and compare it to the elements before it. Move it left until it’s in the correct position relative to the elements before it, then repeat for each element in the list until the entire list is sorted.

3. How did you verify that your sort was correct?

I tested it with a small set of scores including new scores added manually.


