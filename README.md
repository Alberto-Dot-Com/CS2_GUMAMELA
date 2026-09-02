1. Get the coordinates (Normal text)
point_x1 = float(input("Enter the x1: "))
point_x2 = float(input("Enter the x2: "))
point_y1 = float(input("Enter the y1: "))
point_y2 = float(input("Enter the y2: "))

# 2. Square the differences using pow()
point_a = pow(point_x2 - point_x1, 2)
point_b = pow(point_y2 - point_y1, 2)

# 3. Add them together and take the square root to solve
distance = pow(point_a + point_b, 0.5)

# 4. Print the final solution
print("The distance between the points is:", distance)
