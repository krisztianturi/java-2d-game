# DynaBlaster 2D Game
This game is an own adaptation of Dyna Blaster, also known as Bomberman. 
It features a custom-built game engine, and intelligent opponents are controlled using the D*Lite algorithm.

## Video
- `demo_Dragon.mp4` – Demonstrates the gameplay and the game mode.

## Executables
- `DynaBlaster_Client.jar` – The client-side executable for the game.
- `DynaBlaster_Server.jar` – The server-side executable for networked gameplay.

## Technology Stack
- Java 22
- Java Swing / AWT for 2D graphics
- gRPC for networking
- Lombok for boilerplate reduction
- Log4j2 for logging
- Maven for project management and build

## Running the Game
- Java 22 is required to run the JAR files.
- **Single-player mode:** Either JAR file can be used.
- **Networked multiplayer mode:**
    1. Start the `_Server.jar` first; the server will launch through the 'Network' menu.
    2. Launch one or more `_Client.jar` instances to connect to the server.

## Connection
- With an internet connection, the server machine should be made accessible externally (e.g., using port forwarding).
- Without internet, the game works on `localhost`.

## Controls
- Enter / Esc – Log in / Exit
- Arrow keys – Movement
- Space – Place bomb
- Controls can be customized in the game menu under 'Settings'.

## Note
The demonstration video illustrates gameplay and features. The included JAR files provide playable versions based on this demo.
