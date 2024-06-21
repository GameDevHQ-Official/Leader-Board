# Leader Board 

## Objective

Develop a program to manage a high score display. The program will allow users to enter their names and scores, and replace one of the existing scores if their score is high enough. Use static arrays to store names and scores. Implement functionality to update the high score list and display it.

## Requirements

### Data Storage

The program should use:
- A 1D array to store player names
- A 1D array to store corresponding scores

### Functionalities

The program should implement the following functionalities:
- Allow the user to enter their name and score.
- Check if the entered score is higher than any of the existing scores.
- Replace the lowest score if the entered score is higher.
- Display the updated high score list.

### Display

The program should display:
- Instructions for entering a name and score.
- The updated high score list after each entry.

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`, `<string>`, `<algorithm>`).

### 2. Define Variables

- Define a 1D array to store player names.
- Define a 1D array to store scores.

### 3. Initialize Arrays

- Initialize the arrays with a fixed number of high scores (e.g., top 5 scores).

| Player Name | Score |
| :---------: | :---: |
| Alice       |  950  |
| Bob         |  850  |
| Charlie     |  800  |
| David       |  750  |
| Eve         |  700  |

### 4. Enter Name and Score

- Prompt the user to enter their name and score.
- Validate the input to ensure it is a valid score.

### 5. Update High Score List

- Check if the entered score is higher than any of the existing scores.
- Replace the lowest score if the entered score is higher.
- Sort the high score list to maintain order.

### 6. Display Results

- Display the updated high score list after each entry.

## Example User Interaction

```plaintext
*******************************
*     High Score Display      *
*******************************

Current High Scores:
| Player Name | Score |
| :---------: | :---: |
| Alice       |  950  |
| Bob         |  850  |
| Charlie     |  800  |
| David       |  750  |
| Eve         |  700  |

Enter your name: Frank
Enter your score: 900

Updated High Scores:
| Player Name | Score |
| :---------: | :---: |
| Alice       |  950  |
| Frank       |  900  |
| Bob         |  850  |
| Charlie     |  800  |
| David       |  750  |
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
