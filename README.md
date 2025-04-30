# Classic-Chess
This project is a fully functional Player vs Player Chess Game developed in C++, leveraging the SFML (Simple and Fast Multimedia Library) for graphics and window management. It showcases my understanding of object-oriented design, game logic, and real-time rendering in a GUI-based application.

Key Features:

 - Classic chess rules implemented with full piece functionality (King, Queen, Bishop, Knight, Rook, and Pawn).
 - Modular class-based architecture for clean, scalable design (see Class Diagram).
 - Smooth and responsive 2D graphics powered by SFML.
 - Click-based piece selection and move execution.
 - Designed for two local players (PvP mode).




![pic](https://github.com/user-attachments/assets/8516dccf-3f4a-45be-a99c-55d097cd7d82)

Visuals:


Includes a rich 2D graphical chessboard and piece sprites, offering a user-friendly interface.
(See sample screenshots below.)



Architecture:


The project follows a clean and extensible object-oriented structure. Each piece type is implemented as a class derived from a common Piece base class, allowing for easy maintenance and potential feature expansion (e.g., AI opponent, online multiplayer).

Building and Running the Game (Linux):

Make sure SFML is installed:

$ sudo apt-get install libsfml-dev


Navigate to the src/ directory and compile:

$ g++ -c main.cpp Square.cpp Pieces.cpp Knight.cpp Bishop.cpp King.cpp Queen.cpp Pawn.cpp Rook.cpp Game.cpp
$ g++ main.o Square.o Pieces.o Knight.o Bishop.o King.o Queen.o Pawn.o Rook.o Game.o -lsfml-graphics -lsfml-window -lsfml-system
$ ./a.out
This project highlights my ability to build interactive graphical applications in C++, use third-party libraries effectively, and follow solid software engineering principles. It also demonstrates my attention to user experience and performance, making it a great showcase of both technical and design skills.

Would you like help creating a README file or portfolio page layout for this?

