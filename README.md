# checkstrings

# Do not modify these lines
__winc_id__ = '71dd124b4a6e4d268f5973db521394ee'
__human_name__ = 'strings'

# Add your code after this line
scorer_a='Ruud Gullit'
scorer_b='Marco van Basten'
goal_0 = 32
goal_1 = 54

scorers=scorer_a+ " " +str(goal_0)+ ", " +scorer_b + " "+str(goal_1)
print(scorers)
report=f'{scorer_a} scored in the {goal_0}nd minute\n{scorer_b} scored in the {goal_1}th minute'
print(report)

player = "Ronald Koeman"

first_name = f'{player [:player.find(" ")]}'
print(first_name)

last_name_len=len(player[7:len(player)])
print (last_name_len)

name_short=f'{player[:1]}.{player[player.find(" "):]}'
print(name_short)
first_name_len=len(player [:player.find(" ")])
print(first_name_len)

chant_one_time=f'{player [:player.find(" ")]}!'
chant_how_many_times=len(player [:player.find(" ")])

chant2=(first_name + "!" + " ")*len(first_name)
chant=(chant2[:-1])
print(chant)

good_chant = chant[-1:] != " "
print(good_chant)
