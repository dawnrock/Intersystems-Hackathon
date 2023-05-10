# Intersystems-Hackathon
Detection test for cases of insomnia
This service will be in charge of analyzing user records via csv files with the following data:

age - person's age in years
weight- person's weight in kilograms
height- person's height in centimeters
sex - person's sex, female (1) and male (2)
stress - level of stress during last month (1, 2, 3 - higher values correspond to larger stress)
doctor - relative number of visits to doctor previously (1, 2, 3 - higher values correspond to greater number of visits)
sport - is person physically active or not (binary)
pernicious_1 - does person have some bad habit or not (binary)
pernicious_2 - does person have some another bad habit or not (binary)
ubp/lbp - upper/lower blood pressure in mmHg

The result will be obtained using the insomnia binary field:
Target, does person have sleep disorder (1) or not (0)
