# Dictionaries

Create a dictionary, `house_areas`, that contains the areas of the
`hallway` (`2.3`), `kitchen` (`11`), and `living room` (`35`).

- Print the `kitchen` area.
- Add the `bedroom` to the dictionary with an area of `14`.
- Print only the rooms from the `house_areas`.
- Add the `bathroom` (with an area of `5.7`) to the `house_areas` dictionary.
- Print all the rooms with their corresponding areas.


house_areas={'hallway':2.3, 'kitchen':11, 'living room':35}
print('kitchen area is :', house_areas.get('kitchen'))
#Add bedroom
house_areas['bedroom']=14
#Rooms for house areas
print(house_areas.keys())
#Add bathroom
house_areas['bathroom']=5.7

for key, value in house_areas.items():
    print(key, '=', value)
