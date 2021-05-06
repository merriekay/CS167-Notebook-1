# Notebook #1: Python, Pandas, and Pokemon, Oh My!

<b>Due</b>: TBD

## The Data
For this notebook, we're going to enter the world of Pokemon.

The data is from Kaggle, and can be found in this repository, on blackboard, and online at [this link](https://www.kaggle.com/abcsds/pokemon).
The data includes the following features:
- **#**: ID for each pokemon
- **Name**: Name of each pokemon
- **Type 1**: Each pokemon has a type, this determines weakness/resistance to attacks
- **Type 2**: Some pokemon are dual type and have 2
- **Total**: sum of all stats that come after this, a general guide to how strong a pokemon is
- **HP**: hit points, or health, defines how much damage a pokemon can withstand before fainting
- **Attack**: the base modifier for normal attacks (eg. Scratch, Punch)
- **Defense**: the base damage resistance against normal attacks
- **SP Atk**: special attack, the base modifier for special attacks (e.g. fire blast, bubble beam)
- **SP Def**: the base damage resistance against special attacks
 -**Speed*and *: determines which pokemon attacks first each round
 
 The first step is to get the data loaded and ready to go, make sure the data is in your Google Drive and mount your Drive to the notebook. Start by printing out the first several lines of the dataset to get an idea of what the data looks like. 

## What you need to do :exclamation:
<b>Notebook #1 consists of the following exercises</b> [ 1 point each ]:
1. Print out all of the possible values for the primary type of pokemon.
2. Create a subset of data representing pokemon whose primary type is **Bug** :bug:, and the second type is **Poison** :skull:. Save this DataFrame to the variable name bug_poison_pokemon. Display the first 5 lines of this subset.
3. Using bug_poison_pokemon, what is the median **Attack** of Bug Poison Pokemon?
4. Which primary type of pokemon is the overall strongest? (not looking for philsophical debates here, I'm looking at the average of the 'Total' column, grouped by Type--so Fire v Water v Grass etc.). 
5. Choose a generation of pokemon, and create a subset with only pokemon with this generation. Include 5 columns, the Generation, name, type 1, type 2, and total. 
6. From the Generation that you've chosen, ouput the mean,  median, and standard deviation of the 'HP' column. 



Use a Markup cell to put your name at the top of the file. Submit this assignment through the GitHub Classroom link.

## :white_check_mark: Grading: 
I will update the following rubric with your grade after you have completed the assignment.
### Rubric:
| Exercise #  | Points Awarded (out of 1)  | Notes |
| --------- | ------------------- | --------- |
| 1      |        |    |
| 2      |        |    | 
| 3      |        |    |
| 4      |        |    | 
| 5      |        |    |
| 6      |        |    |
| <b>Total      |       /6 | </b>   |
