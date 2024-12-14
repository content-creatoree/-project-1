# Mad Libs Game

# Prompt the user for input
adjective1 = input("Enter an adjective: ")
noun1 = input("Enter a noun: ")
verb1 = input("Enter a verb: ")
adjective2 = input("Enter another adjective: ")
noun2 = input("Enter another noun: ")

# The Mad Lib story
story = f"""
Once upon a time, there was a {adjective1} {noun1}.
Every day, it loved to {verb1}.
One day, it met a {adjective2} {noun2},
and they became the best of friends forever.
"""

# Print the completed story
print("\nHere is your Mad Libs story:")
print(story)
Enter an adjective: Funny
Enter a noun: Tree
Enter a verb: Dance
Enter another adjective: brave
Enter another noun: knight

Here is your Mad Libs story:

Once upon a time, there was a Funny Tree.
Every day, it loved to Dance.
One day, it met a brave knight,
and they became the best of friends forever.
