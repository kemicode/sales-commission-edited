# sales-commission-edited
#Write a program that solves ' Acme auto pays sales persons 3.5% commission on their sales
#assign the value to properly named constant. Sasha sold three cars. Write a program that
#prompts for the selling prices of the three cars and calculates her total sales and commission

#Pseudocode
#start Program
#
#prompt user for cost of each car, assign to variable (car_pri1, car_pri2, car_pri3).
#Calculate the total cost of the 3 cars, assign to variable total_car.
#Ehter the commission rate, assign to variable comm_rate.
#calculate pay = sales * comm_rate.
#Output the total cost of the three cars.
#output the total sales commission on the three cars.
#end of program.



#start program


#Prompt user for cost of each car
car_pri1 = float(input('Enter cost of first car'))
car_pri2 = float(input('Enter cost of second car'))
car_pri3 = float(input('Enter cost of third car'))

#Calculate the total cost of 3 cars
total_car = car_pri1 + car_pri2 + car_pri3
    
#Enter commission rate
comm_rate = 0.035

    
#calculate pay
pay = total_car * comm_rate
    
#output the pay-out on the sale of the three cars
print(f'The total cost of the three cars is:${total_car:,.2f}.')
print(f'The Sales Commission on the three cars is: ${pay:,.2f}.')

    
#End of Program 
    
