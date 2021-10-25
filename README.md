# Project-3---Sales-Data
#1
toppings = ["pepperoni", "pineapple", "cheese", "sausage", "olives", "anchovies", "mushrooms"]

#2
prices = [2, 6, 1, 3, 2, 7, 2]

#3
num_two_dollar_slices = prices.count(2)
print(num_two_dollar_slices)

#4
num_pizzas = (len(toppings))
print(num_pizzas)

#5
print("We sell " + str(num_pizzas) + " different kinds of pizza!")

#6
pizzas_n_prices = zip(prices, toppings)
pizza_and_prices = list(pizzas_n_prices)
print(pizza_and_prices)

#7
pizza_and_prices.sort()
print(pizza_and_prices)

#8
cheapest_pizza = pizza_and_prices[0]
print(cheapest_pizza)

#10
priciest_pizza = pizza_and_prices[-1]
print(priciest_pizza)

#11
pizza_and_prices.pop(-1)
print(pizza_and_prices)

pizza_and_prices.insert(4, [2.5, "peppers"])
print(pizza_and_prices)

three_cheapest = pizza_and_prices[:3]
print(three_cheapest)

