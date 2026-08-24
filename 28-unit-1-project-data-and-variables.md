## Project: Data & Variables

In this project, you are going to write code to display a fictional
**Launch Checklist**, which includes information about the spaceship,
astronauts, and fuel.

### Declare and Assign Variables

Declare and assign a variable for every data point listed below.

| Variable  | Value |
| ------------- | ------------- |
| ``date``  | Thursday 2021-03-18  |
| ``time``  | 10:05:34 AM  |
|``average_astronaut_mass_kg``|80.7|
|``fuel_mass_kg``|760000|
|``ship_mass_kg``|74842.31|
|``fuel_level``|100%|

### Collect User Input

Prompt the user to enter for the following information, and store each response
in its own variable:

1. The number of astronauts in the crew (1 - 7).
1. The crew status (``Ready`` or ``Not Ready``).

### Mass Calculations

Create variables to store the following values:

1. The total mass of the crew (number of astronauts * average astronaut mass).
1. The total mass of the ship (mass of crew + mass of ship + mass of fuel).

#### Warning!

Remember to let your code do the calculations! Do NOT hard-code a number for
either mass value.

For example, if you try to use ``total_crew_mass = 242.1``, then your program
works correctly ONLY IF the user enters ``3`` for the number of astronauts.

### Generate the Checklist

Display the checklist in the console using your variables.

The generated report should look like the example below - including spaces and
symbols (``-``, ``>``, and ``*``).

#### Example Output

Note that your output will change if you assign different values to the
variables, or if the user enters different values when prompted.

The point is to AVOID coding specific values into the ``print`` statements. Use
your variable names instead!

```
-------------------
> LAUNCH CHECKLIST
-------------------
Date: Thursday 2021-03-18
Time: 10:05:34 AM

-------------------
> SHIP INFO
-------------------
* Crew: 7
* Crew Status: Ready
* Fuel Level: 100%

-------------------
> MASS DATA
-------------------
* Crew: 564.9 kg
* Fuel: 760000 kg
* Spaceship: 74842.31 kg
* Total mass: 835407.21 kg
```

### Show Off Your Code

When finished, demonstrate your program to your teacher so they can verify your
work.
