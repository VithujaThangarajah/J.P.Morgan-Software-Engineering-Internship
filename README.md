J.P.Morgan Software Engineering Internship

Overview

You work in the credit rewards department at JPMorgan Chase. Your team handles conversions from dollars to credit card points, credit card points to miles, miles to credit card points, and so on. Today, you are working on a ticket involving the RewardsConverter system, which needs a new part to function. This system is missing a crucial class, which you’ll be creating over the course of this program. The RewardsConverter system accepts a cash value and returns the corresponding value in airline miles. The system needs a RewardValue class to function, which represents the correspondence between currencies, be it cash, airline miles, or something else. It will handle the conversion between all of these scales. In this task, you will set up your local development environment for coding and implement the aforementioned class.

Task Description

Task 1: Modify an existing system Create a RewardValue class that satisfies the following requirements:

RewardValue must have two constructors: one that accepts a cash value and one that accepts a value in miles.
RewardValue must have a getCashValue() method, which returns the cash value of the RewardValue.
RewardValue must have a getMilesValue() method, which returns how many miles the RewardValue is worth.
RewardValue must convert from miles to cash at a rate of 0.0035.
Task 2: Unit testing Time to test:

Navigate to src/test/java and explore the RewardValueTests file.
Notice that two tests pass and two tests fail. Your task is to fill in the two failing unit tests. One of them must test the ability of the RewardValue class to convert from cash to miles. The other must test its ability to convert from miles to cash. Be sure to check that the conversion rate is accurate!
