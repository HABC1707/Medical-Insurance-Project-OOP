# Medical-Insurance-Project-OOP
Python Classes: Medical Insurance Project using Object Oriented Programming Concepts

Classes are an incredibly useful programming tool because they allow you to create a blueprint that can be used to build many objects off of. In this case, you can organize any patient’s information and apply all methods from Patient to update and arrange their data.

There are endless possibilities for extending the capabilities of this class.

You have been asked to develop a system that makes it easier to organize patient data. You will create a class that does the following:

Takes in patient parameters regarding their personal information
Contains methods that allow users to update their information
Gives patients insight into their potential medical fees.

Parameters:

sex: patient’s biological identification, 0 for male and 1 for female
bmi: patient BMI
num_of_children: number of children patient has
smoker: patient smoking status, 0 for a non-smoker and 1 for a smoker

1. Our first method will be estimated_insurance_cost(), which takes our instance’s parameters (representing our patient’s information) and returns their expected yearly medical fees.

estimated_cost= 250 ∗ age − 128 ∗ sex + 370 ∗ bmi + 425 ∗ num_of_children + 24000 ∗ smoker − 12500

Make another update method that modifies the num_of_children parameter.

2. if the patient has 1 offspring, we should see the following output:

{Patient Name} has {Patient Number of Children} child.
Otherwise, we should see this output:

{Patient Name} has {Patient Number of Children} children.

3. Create one last method that uses a dictionary to store a patient’s information in one convenient variable. We can use our parameters as the keys and their specific data as the values. This dictionary should hold all six class variables in Profile and return the patient_info dictionary at the end.
