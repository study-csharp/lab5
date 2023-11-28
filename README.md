# Lab 5 Working with Files and Directories

## Assignment 1: Reading from a Text File

**Objective:**
Write a C# program that reads text from a given file and displays it on the console.

**Tasks:**
1. Create a new console application in C#.
2. Implement a method that takes a file path as a parameter and reads the text content from the file.
3. Use `StreamReader` to read the file content.
4. Display the read text on the console.

**Example:**
```csharp
class Program
{
    static void Main()
    {
        string filePath = "path/to/your/textfile.txt";
        ReadAndDisplayText(filePath);
    }

    static void ReadAndDisplayText(string filePath)
    {
        // Implement your code here
    }
}
```
# Assignment 2: Writing to a Text File

**Objective:**
Create a C# program that takes user input and writes it to a text file.

**Tasks:**
1. Create a new console application in C#.
2. Implement a method that takes user input and writes it to a text file.
3. Use `StreamWriter` to write to the file.
4. Allow the user to input multiple lines until they choose to stop.
5. Provide an option for the user to specify the file path.

**Example:**
```csharp
class Program
{
    static void Main()
    {
        string filePath = "path/to/your/outputfile.txt";
        WriteToFile(filePath);
    }

    static void WriteToFile(string filePath)
    {
        // Implement your code here
    }
}
```

# Assignment 3: Directory Traversal

**Objective:**
Develop a C# program that explores and displays the contents of a given directory, including subdirectories and files.

**Tasks:**
1. Create a new console application in C#.
2. Implement a method that takes a directory path as a parameter and displays the contents of that directory.
3. Use `DirectoryInfo` and `FileInfo` classes for traversing directories and working with files.
4. Recursively explore subdirectories and display their contents.
5. Provide an option for the user to specify the directory path.

**Example Output:**
```
- [Directory] RootDirectory
  - [File] File1.txt
  - [File] File2.txt
  - [Directory] Subdirectory1
    - [File] Subfile1.txt
    - [File] Subfile2.txt
  - [Directory] Subdirectory2
    - [File] Subfile3.txt
    - [Directory] Subsubdirectory
      - [File] Subsubfile1.txt



