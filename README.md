# Monopoly-with-GUI
This project is a Java-based GUI Monopoly game developed using Java Swing. The game features a graphical user interface that provides an interactive and user-friendly gameplay experience.

The application starts with a welcome screen where player names are entered using a GridLayout. The game supports four players, one human-controlled player and three computer-controlled players.

The main game screen is divided into multiple sections using layout managers:

A game map panel where the board, players, and properties are rendered using custom 2D graphics (JPanel and paintComponent)

An information panel (JTextArea) that displays a log of in-game actions

Action buttons (roll, buy, sell, build, end turn) that allow the player to interact with the game

Game interactions are handled through ActionListeners, and the interface updates dynamically using repaint() calls. Buttons are enabled or disabled based on the current game state and the player’s possible actions. During computer-controlled turns, all buttons are disabled.

Players can roll dice, buy properties, sell properties, and build houses, and property cells are visually updated to reflect ownership. Additional frames are used for selecting properties to sell or build on.

This project demonstrates effective use of Java Swing, event-driven programming, layout management, and custom graphics rendering to implement a complete GUI-based Monopoly game.
