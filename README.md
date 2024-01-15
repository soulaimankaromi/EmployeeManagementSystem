We want to create an application for employee management, we ask you to create all the classes for this application.

Required work

The IR or income tax is a global tax established on the total income (salary) available to a person during a given year. To determine the amount of IR, we use the following IR scale table

Annual salary brackets (in DH)                      IR rate in %

0 to 30 000                                              0%

30 001 to 50 000                                         10%

50 001 to 60 000                                        20%

60 001 to 80 000                                        30%

80 001 to 180 000                                       34%

Beyond 180 001                                          38%


For example if the salary of an employee is 9500 DH then:

His annual salary is salary x 12-9500 x 12-114,000 DH

Then the IR rate is = 38%

1. Create the abstract class IR with:

has. The slices attribute: An array initialized by the values of the slices above.

b. The falseIR attribute. An IR Rate table initialized by the corresponding IR values

vs. A static function getIR(salary) which returns the IR rate corresponding to the salary passed as a parameter.

2. Create the IEmploye interface with the following methods:

has. An age() method that will return the age of an employee (Integer).

b. A seniority() method that will return an employee's seniority (the number of years they have

work).

C. Unc Retirementdate (Retirementage) method to return the employee's retirement date: (2pts) Retirement date birth date retirement age

An employee is characterized by:

Personnel number (automatically incremented) mtle

Name nem

Date of birth date Birth

Hire date (recruitment date): Hire date

Base salary salaryBase

3. Create the Employee class with

has. Attributes

b. Accessors with decorators knowing that the age of the employee at the date of recruitment must not be less than 20 years.

e. An initialization constructor and a parameterized constructor which takes all the attributes of the class as parameters.

d. An abstract salaryAPayer() method to return an employee's net salary

e. Implementing the IEmploye interface with these three methods.

f. The toString() method which returns all properties separated by “>”

g. The Equals() method: 2 employees are equal if they have the same number
A trainer is an employee with the addition of:

The number of overtime hours per month: hourSup.

Remuneration per overtime hour, the value of which is shared by all trainers and by default equal to 70.00 dh: rateHsup

4. Create the Trainer class with

has. Attributes.

b. Accessors with decorators.

vs. The initialization constructor

d. The ToString() (str) method.

e. The Salaire APayer() method to calculate the net salary of a trainer knowing that:

Net salary (BaseSalary + NhrHS x tariffHsup) x (1-tauxIR)

N.B. Use the getlk method of the IR class to calculate the IR rate.

An Agent is an employee with the addition of:

• The amount of the liability premium: Responsibility premium.

5. Create the Agent class with:

has. The SalaireAPayer() method to calculate the net salary of an agnet knowing that:

Net salary (BaseSalary + Responsibility Bonus) x (1-TauxIR)
