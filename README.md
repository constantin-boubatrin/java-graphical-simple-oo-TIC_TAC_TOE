# TIC-TAC-TOE-Graphical-Simple-OO

In this project I rewrote the "console" version into a "graphics" version - a Java Swing application,
as illustrated. In this initial design, I don't separate the cell and board into dedicated classes,
but include them in the main class. I used an inner class GamePanel (that extends JPanel) to do
the custom drawing, and an anonymous inner class for MouseListener.

The content-pane (of the top-level container JFrame) is set to BorderLayout. The DrawCanvas (JPanel)
is placed at the CENTER; while a status-bar (a JLabel) is placed at the SOUTH (PAGE_END).