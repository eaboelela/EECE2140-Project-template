> **Tip:** This file is written in Markdown. The raw view in the VS Code
> editor will show symbols such as `#`, `|`, and `` ``` `` instead of
> formatted headings, tables, and code blocks. For the formatted view,
> press **Ctrl+Shift+V** (macOS: **Cmd+Shift+V**) to open the rendered
> preview.

# [Project Title]

**EECE 2140 — Computing Fundamentals for Engineers · Fall 2026 · Course Project**

> Replace every item in square brackets, and delete these instruction
> lines (the ones starting with `>`) before your final submission.
> Every heading below is required (Handout Section 3.4).

## 1. Description

[One paragraph: the problem your program solves, who would use it, and
what it produces.]

## 2. Team

| Name | Student ID | GitHub username |
| --- | --- | --- |
| [Member 1] | [ID] | [username] |
| [Member 2, or delete this row if working individually] | [ID] | [username] |

## 3. Build and Run

Build from the repository root (VS Code: **Terminal → Run Build Task**,
or **Ctrl+Shift+B** / **Cmd+Shift+B**):

```bash
g++ -std=c++11 -Wall src/*.cpp -o project
```

Run:

```bash
./project
```

[Add any command-line arguments, or the menu option to choose first,
if your program needs them.]

## 4. Input File Format

[For each input file in `data/`: its name, what each line contains,
the field order and separators, and a two- or three-line example.]

```text
[example lines from your input file]
```

## 5. Output

[What the program prints and the name and contents of any file it
writes.]

## 6. Classes

| Class | Base class (if any) | Responsibility | Written by |
| --- | --- | --- | --- |
| [ClassName] | [— or BaseName] | [one sentence] | [member name] |

## 7. Required Features (R1–R8)

| Requirement | File(s) | Function(s) or class(es) |
| --- | --- | --- |
| R1 Classes and encapsulation | | |
| R2 Inheritance and polymorphism | | |
| R3 Dynamic memory (destructor, copy constructor, assignment operator) | | |
| R4 Operator overloading | | |
| R5 Strings and vectors | | |
| R6 File input and output | | |
| R7 Separate compilation | | |
| R8 Console interface and validation | | |

## 8. Elective Features (at least two)

| Elective | File(s) | Function(s) or class(es) |
| --- | --- | --- |
| [elective name] | | |
| [elective name] | | |

## 9. Extensions

[List the optional extensions you completed, or write "None".]

## 10. Known Limitations

[Anything that does not work yet, or inputs the program does not
handle.]
