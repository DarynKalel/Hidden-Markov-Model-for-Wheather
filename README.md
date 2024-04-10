# Hidden-Markov-Model-for-Wheather
We will model a wheather system, thst will predict the temperature on each day given the following information:
Cold days are encoded by 0, hot days encoded by 1
The first day in our sequence has 80% chance of being cold
A cold day has a 30% chance of being followed by a hot day
A hot day has 20% chance of being followed by a cold day
On each day the temperature is normmally distributed, with mean and standard deviation 0 and 5 on a cold day and mean and standard deviation 15 and 10 on a hot day
