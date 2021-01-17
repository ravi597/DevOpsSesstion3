# in model.py
from epicenter import Epicenter

revenue = 0
cost = 0
profit = 0

def calculate_profit():
    global revenue, cost, profit

    profit = revenue - cost

    Epicenter.record('profit', profit)

    return profit
