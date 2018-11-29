# DATA
Virus name  (Lyme and Spanish Flu)
Mortality rate ( .2, 2.5)
Reproductive rate(4.4,3)

# CLASSES
Virus(smaller component)
People(a little more complicated)
Simulation (biggest component)
Logger(build last) 

# RULES
Each step → sick person interacts with 100 random people
Rate of infection = reproductive rate
Each step →sick person dies or becomes immune
If Stays Alive→ is_vaccinated = True
(chance of death = mortality_rate)
If Dead → .infected = False
If Infected → .infect = True

Keep track of how many people infected after each turn

-.run() method
-.time_step()


Sick can only infect Healthy (unvaccinated people)
Sick cannot infect vaccinated
Sick cannot infect sick


Population Size: 100,000
Vaccination Percentage: 90%
Virus Name: Ebola
Mortality Rate: 70%
Reproduction Rate: 25%
People Initially Infected: 10
