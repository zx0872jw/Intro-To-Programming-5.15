# Intro-To-Programming-5.15
arrow_base_height = int(input('Enter arrow base height:\n'))

arrow_base_width = int(input('Enter arrow base width:\n'))

arrow_head_width = int(input('Enter arrow head width:\n'))

while arrow_head_width <= arrow_base_width:
    arrow_head_width = int(input('Enter arrow head width:\n'))

print('')
for i in range(arrow_base_height):
    i = arrow_base_width * '*'
    print(i)
for j in range(arrow_head_width):
    j = arrow_head_width * '*'
    print(j)
    arrow_head_width -= 1
