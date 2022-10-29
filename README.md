<img src="https://cdn-icons-png.flaticon.com/128/188/188987.png" title="Pikachu" />

# Help Wanted!!
"Take down a vicious ramsomware attack on Pokémon's community"

# The Problem
After a vicious ransomware attack to one of the most known Pokémon's community - Yellow - which relies on data to support its activities, has lost a lot of the data and approach me to help them out to get the lost data back

The PokéAPI is a RESTful API of all known Pokémon.

To get information on a single Pokémon the following GET request can be used 
`https://pokeapi.co/api/v2/pokemon/<index>`. Replace `<index>` by an integer to get the Pokémon with that index number.

The response returned from querying the PokéAPI is formatted as JSON. The structure of the JSON can be seen in the [PokéAPI Documentation](URL "https://pokeapi.co/docs/v2#pokemon"). The documentation also contains information of all the many other endpoints of PokéAPI

# The Goal
The community would like to the following information from me:

1) The _name_, _id_, _base_experience_, _weight_, _height_ and _order_ of all Pokémon that appear in any of the games _red_, _blue_, _leafgreen_ or _white_
2) The _name_ of the _slot 1_ (and if available _2_) _type_of each of Pokémon's _types_
3) The Body Mass Index of the Pokémon 
4) The first letter of names of the Pokémon should be capitalized
5) The url of the _front_defaultsprite_.
6) Prepare the data in an appropriate data format. Consider if it should be multiple of single file

# A Note from the developer
Please check the thouroughly comments inside the notebook to understand the approach taken

## Technologies used
- Python
- Databricks Community edition
- Spark
- Notebooks
<br/>
* IDE used: VS Code
