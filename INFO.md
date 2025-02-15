## Project Info

Tools used:

[Google Web Toolkit(GWT)](https://github.com/gwtproject/gwt)

[PlayN](https://github.com/playn/playn)

[Jake2 (Java Quake 2)](https://github.com/demoth/jake2)

GWT is a development toolkit for building and optimizing complex browser-based applications. Allows devs to write client-side Java and compile it into JavaScript. GWT provides a set of tools and libraries for creating rich web applications, including support for WebGL.

PlayN is a cross-platform game development framework written in Java. Targets browsers (via GWT), desktop JVMs, Android, and iOS devices. PlayN provides a set of APIs for handling game logic, rendering, input, and other game-related tasks.

This Quake II emulation project uses GWT to compile Java into JavaScript. PlayN is used to handle the game logic, rendering, and input handling. The combination of GWT and PlayN allows the project to run Quake II in a web browser using WebGL for rendering.

## Recreating the Project with Modern Versions of GWT and PlayN

1. Set Up Your Development Environment:

    Install Java Development Kit (JDK).

    Install a modern IDE (e.g., IntelliJ IDEA, Eclipse).

    Set up Maven for dependency management.

2. Create a New PlayN Project:

    Use Maven to create a new PlayN project.

    Add dependencies for GWT and PlayN in your pom.xml file.

3. Implement Quake II Logic:

    Implement the game logic for Quake II using PlayN APIs.

    Use PlayN's rendering capabilities to handle 3D graphics.

4. Compile with GWT:

    Use GWT to compile your Java code into JavaScript.

    Ensure that your project is set up to use GWT's GwtModule and GwtApplication classes for compiling and running the application.

5. Test and Debug:

    Test your project in a modern web browser to ensure it works correctly.

    Debug any issues that arise using browser developer tools and your IDE's debugging capabilities.

6. Deploy