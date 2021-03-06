# Unveiled - Use-Case Specification: Browse own media

## 1. Use-Case Name
Browse own media.

### 1.1 Brief Description
With our web interface a logged-in user is able to browse through his/her uploaded content. He can see a preview of pictures and videos.

### 1.2 Screenshot Mockup
![][screenshot]

## 2. Flow of Events

### 2.1 Basic Flow
![][basic flow]

### 2.2 Alternative Flow
(n/a)


## 3. Special Requirements
(n/a)


## 4. Preconditions
### 4.1 Logged-in user
For this use case the user has to have a valid account on the server and he has to be logged-in.

## 5. Postconditions
The following use cases require this use case to be completed:
- Delete own media
- View own media
- Download own media

## 6. Extension Points
(n/a)

## 7. Function Point calculation
This use case was estimated with 19 FPs. See the table and screenshot below for details:

| Transaction | DET's | RET's | FTR's | Complexity |
|-----------------------|:-:|:-:|:-:|:---:|
| EO Media Viewer       | 5 | - | 2 | Average |
| ILF Media             | 17 | 1 | - | Low |
| ILF User              | 12 | 0 | - | Low |
| EIF                   | - | - | - | - |

![][fp calculation]

All function point calculation tables are also located in one spreadsheet. Please take a look at this [document][fpc spreadsheet].

<!-- Link definitions: -->
[basic flow]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/UC_Diagrams/UC_Diagram_Browse_media.png "Use Case Diagram: Register"

[screenshot]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/Screenshots_website/browse_media.PNG "Screenshot media browser"
[fp calculation]: https://raw.githubusercontent.com/SAS-Systems/Unveiled-Documentation/master/Bilder/FP%20calculation/FP_browse_media.PNG "FP calculation"
[fpc spreadsheet]: https://docs.google.com/spreadsheets/d/1qaz88UHaRb7cXoiOkJ0dJ-R7JvfTxPslJvZ183o6wnU/edit?usp=sharing "Function point calculation spreadsheet"
