# Maven

### What ia Maven?
* Maven is a Build Automation and Depenldency Management Tool used mainly for java project.
    1. Download required libraries automatically.
    2. Compile Java Code.
    3. Run tests
    4. Package applications into JAR/WAR files
    5. Manage project structure.
    6. Build projects with one command
    
    Project Management Tool
    1. Folder Structure
    2. Compile code
    3. Creates JAR code4
    4. Dependicens download(JAR)

    pom.xml (Project Object Model )
    Super pom ---> parent of all pom
    effective pom ---> maven finally use this (pom + super pom)

    Maven uses 2 Repositories
    Maven Central
    local -> .m2/repositories
    Other remote

    * Complete Flow
    1. Maven read pom.xml
    2. Check local Repo(m2/repository)
    3. Check Maven central Repo
    4. Store downloaded jar in local

## Life Cycle
```mermail
flowchart LR

    A[Developer]
    B[pom.xml]
    C[Maven]
    D[Maven Repository]
    E[Project]

    A --> B
    B --> C
    C --> D
    D --> E
```