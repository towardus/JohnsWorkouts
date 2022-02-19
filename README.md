# JohnsWorkouts
An app where John can design and publish weight training sessions for his family and friends.

Design notes

Major classes:

Workout - A set of exercises performed in a single session.
Exercise - The use of one's body to move or lift itself or a weight.
Set - The performance of an exercise for a given number of reps.
Rep - One unit of exercise.

Workouts HAVE A 
Date
Type
Performer
Collection of Exercises

Exercises HAVE A
Name - What the exercise is called.
Description - How to perform the exercise, what sort of weights to use, etc.
Collection of Categories
Collection of Sets

Sets HAVE A
Order - Number indicating order.
RepCount - Number
Intensity - listed as a percentage to 100.
Weight - What weight was actually used.
Modified? - Whether the exercise had to be modified (use a chair for dips, e.g.).
RepsPerformed - Actual number of reps completed.
Notes - Any comments, e.g. six push ups, then six down to knees.

App  modes:

Definitions - 
Create Exercises and workouts


Performances - 
Go through exercises and mark outcomes
