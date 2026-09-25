# Java Coursework — Full-Stack Development Foundation

Java laboratory exercises and Eclipse projects created during my full-stack development coursework.

## Project layout

```text
.
├── BasicOpenLabBook1/  # Java lab-book exercises
└── Java2/              # Additional Java exercises
```

Each project contains Eclipse metadata and Java source code under its `src/` directory. This repository is coursework-oriented rather than a single deployable application.

## Requirements

- Java Development Kit (JDK)
- Eclipse IDE or another Java IDE

## Open in Eclipse

1. Clone this repository.
2. Open Eclipse and choose **File → Import → Existing Projects into Workspace**.
3. Select the repository directory.
4. Import `BasicOpenLabBook1` and/or `Java2`.
5. Run the required Java class from its `src/` directory.

## Command-line workflow

For a project with a standard Java source layout, compile and run a class from that project directory:

```bash
javac -d out src/path/to/YourClass.java
java -cp out path.to.YourClass
```

Replace the class path with the actual package and class name for the exercise.

## Testing and build status

There is currently no root Maven/Gradle build or automated test command. The exercises are run individually through Eclipse or the command line. This limitation is intentional because the repository preserves the original coursework structure.

## Scope

This repository documents my early Java and software-development foundation. It should not be interpreted as a production application.

## Author

Mohamed Ukkas
