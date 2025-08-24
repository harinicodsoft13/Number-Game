
## DESCRIPTION 


The Number Game is a simple guessing game where:

The computer selects a random number within a given range (for example 1 to 100).

The user tries to guess the number.

After each guess, the program gives hints like:

“Too High” → if the guess is greater than the secret number

“Too Low” → if the guess is smaller

The user continues guessing until they find the correct number.

The program also counts the number of attempts made.

This game is often used to understand loops, conditional statements, and random number generation in programming.
## OUTCOME OF PROGRAM
When you run the program:

The system will ask the user to enter a guess.

Depending on the input, the program will either:

Guide the player with hints (high/low), OR

Congratulate them if the correct number is guessed.

It will finally show how many attempts were required
## Output 
The system continuously reads temperature and humidity from the DHT11 sensor.

If the temperature exceeds 30°C, an LED automatically turns ON as a visual alert.

All readings are sent to ThingSpeak cloud platform using Wi-Fi.

On the ThingSpeak dashboard:

Field1 shows the temperature in °C

Field2 shows the humidity percentage

Field3 shows LED status (1 = ON, 0 = OFF)

Data updates every 10 seconds, allowing for real-time monitoring from anywhere.

![1]<"https://github.com/user-attachments/assets/add65005-dc8d-46f7-a413-e3dc356f1bb1" />




## RESULT
The user successfully guesses the correct number with the help of hints, and the program displays a congratulation message along with the number of attempts taken.