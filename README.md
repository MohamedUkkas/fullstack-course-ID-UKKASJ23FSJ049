# Fullstack Course — Java Assignments

A collection of Java coursework and Eclipse projects created for the full-stack course. The repository currently organizes exercises into separate Eclipse workspaces/projects, including `BasicOpenLabBook1` and `Java2`.

## Project layout

```text
.
├── BasicOpenLabBook1/  # Java lab-book exercises
└── Java2/              # Additional Java exercises
```

Each project contains Eclipse metadata such as `.project`, `.classpath`, `.settings/`, and a `src/` directory containing the Java source code.

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

If a project has a standard Java source layout, compile and run a class from its project directory with commands similar to:

```bash
javac -d out src/path/to/YourClass.java
java -cp out path.to.YourClass
```

Replace the class path with the actual package and class name for the exercise you want to run.

## Notes

This repository is coursework-oriented rather than a single deployable application. There is no root build tool or automated test command currently documented.

## Author

Mohamed Ukkas
