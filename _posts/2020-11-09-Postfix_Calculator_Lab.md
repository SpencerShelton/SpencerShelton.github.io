---
layout: post
title: Postfix Calculator Lab
---
**Results**  
1. Individual Calculated Results: `[6.0, 40.0, -162.0, -692.0, 2.0, -19.0, 93.0, 95.0, -11.0, 49000.0, 38.0, 84.0, -100.0, 115.0, 3.0, 142.0, 791.0, 82.0, -192.0, -4.0, 143.0, 3060.0, 137.0, 384.0, 11.0, 48.0, 805.0, 11.0, -2700.0, 190.0, -96.0, 1715.0, 60.0, 48.0, -25.0, -4.0, -135.0, -77.0, 663.0, 40.0, 10.0, -81.0, -15.0, -311.0, 1095.0, 1076.0, 1260.0, -204.0, 91.0, 416.0, -26.0, 34.0, -19.0, -343.0, 11.0, -110.0, 192.0, -63.0, -2.0, 9.0, 13.0, -33.0, -223.0, 152.0, 75.0, 54.0, 517.0, 2110.0, 412.0, 10.0, -571.0, 3432.0, 23.0, -48.0, 1764.0, 7.0, 240.0, -2.0, -936.0, 9.0, 1.0, 5.0, 414.0, 386.0, 128.0, -115.0, 1.0, -18.0, 0.0, -16186.0, 1391.0, 29.0, 233.0, 38.0, 63.0, 1560.0, 591.0, -36.0, 917.0, -25.0]`  
2. Average Result: 529.91  

**Method**  

To complete this labI began by grabbing my code for reading in csv files to a list and creating a Stack from previous projects. I then created several methods to ensure my list was properly formated and a function to apply any function to every value stored at an index in a list. I used these methods to properly format my output from reading the csv file. I then built a method to evaluate a postfix equation stored in a list. To do this I used two Stacks, an initial Stack and a holding Stack. I would pop a value off my initial Stack and use a dictionary to check if it was an operator or a number. If it was a number I pushed it to my holding Stack. If it was an operator I used a lambda (anonynous) function to pop two values off my holding Stack, preform the required operation, and push the result back to my holding stack. At the end of the method I returned whatever value was on top of my holding Stack. I used my method that applies any function to every value stored at an index in a list with my postfix evaluation function to make a list of all of the evaluated equations. I then printed that list and then used a function to average every value in the list and print the result.
