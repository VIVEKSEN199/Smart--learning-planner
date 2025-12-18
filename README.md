# Smart--learning-planner
print("=== Smart Learning Planner ===")

subjects = []
n = int(input("How many subjects? "))

for i in range(n):
    sub = input(f"Enter subject {i+1}: ")
    subjects.append(sub)

print("\nYour Daily Study Plan:")
for sub in subjects:
    print("- Study", sub, "for 1 hour")
# Smart Learning Planner
Beginner-level Python project to create a simple study plan.
Tech Stack: Python
Author: Vivek Sen
