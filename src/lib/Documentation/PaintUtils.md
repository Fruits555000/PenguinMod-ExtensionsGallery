# Paint Utils
***Please ignore the spellings in the extension and this documentation of it. I get that it is not conformed to American spelling.*** <br> 
<br>
Paint Utils is a PenguinMod extension made for colour theory. Colour theory describes the behavior of colour in the form of colour mixing among other things.

## Available Colours
**Before we get onto the blocks, we have to know what colours are available in the extension.**

Currently, the extension only supports a fairly small amount of colours with no tones. This will change in future updates. <br>
Here are the colours in question with their position in the colour hierarchy in brackets: <br>
<br>
| Shades                                                                      | Hues                                                                              | Tints |
|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------------|-------|
|![#7F1309](https://placehold.co/15x15/7F1309/7F1309.png) **Maroon (Primary)**|![#FE2712](https://placehold.co/15x15/FE2712/FE2712.png) **Red (Primary)**         |
|        |![#FE3D0D](https://placehold.co/15x15/FE3D0D/FE3D0D.png) **Scarlet (Quaternary)**  |
|        |![#FD5308](https://placehold.co/15x15/FD5308/FD5308.png) **Vermillion (Tertiary)** |
|        |![#FC7605](https://placehold.co/15x15/FC7605/FC7605.png) **Persimmon (Quaternary)**|
|        |![#FB9902](https://placehold.co/15x15/FB9902/FB9902.png) **Orange (Secondary)**    |
|        |![#FBAB02](https://placehold.co/15x15/FBAB02/FBAB02.png) **Sun (Quaternary)**
|        |![#FABC02](https://placehold.co/15x15/FABC02/FABC02.png) **Amber (Tertiary)**      |
|        |![#FCDD1B](https://placehold.co/15x15/FCDD1B/FCDD1B.png) **Gold (Quaternary)**
|        |![#FEFE33](https://placehold.co/15x15/FEFE33/FEFE33.png) **Yellow (Primary)**      |
|        |![#E7F42F](https://placehold.co/15x15/E7F42F/E7F42F.png) **Lemon (Quaternary)**
|        |![#D0EA2B](https://placehold.co/15x15/D0EA2B/D0EA2B.png) **Chartreuse (Tertiary)** |
|        |![#9BCD2F](https://placehold.co/15x15/9BCD2F/9BCD2F.png) **Lime (Quaternary)**
|        |![#66B032](https://placehold.co/15x15/66B032/66B032.png) **Green (Secondary)**     |
|        |![#34A180](https://placehold.co/15x15/34A180/34A180.png) **Viridian (Quaternary)**
|        |![#0392CE](https://placehold.co/15x15/0392CE/0392CE.png) **Teal (Tertiary)**       |
|        |![#036DE6](https://placehold.co/15x15/036DE6/036DE6.png) **Cerulean (Quaternary)**
|        |![#0247FE](https://placehold.co/15x15/0247FE/0247FE.png) **Blue (Primary)**        |
|        |![#2024D1](https://placehold.co/15x15/2024D1/2024D1.png) **Indigo (Quaternary)**
|        |![#3D01A4](https://placehold.co/15x15/3D01A4/3D01A4.png) **Violet (Tertiary)**     |
|        |![#6201AA](https://placehold.co/15x15/6201AA/6201AA.png) **Amethyst (Quaternary)**
|        |![#8601AF](https://placehold.co/15x15/8601AF/8601AF.png) **Purple (Secondary)**    |
|        |![#970D7D](https://placehold.co/15x15/970D7D/970D7D.png) **Aubergine (Quaternary)**
|        |![#A7194B](https://placehold.co/15x15/A7194B/A7194B.png) **Magenta (Tertiary)**    |
|        |![#D3202F](https://placehold.co/15x15/D3202F/D3202F.png) **Crimson (Quaternary)**

With that out of the way, we can now go through the blocks of Paint Utils
## Blocks
There are only two blocks in the entire extension at the moment. This will change in future updates.
```Scratch
(mix colours (colour1) and (colour2) and return the [colour name or colour]:: #d1d1d1)
(get colour form colour name (colour name):: #d1d1d1)
```
Let's explain them
<br>
### Mix Colours Block
The mix colours block mixes two colours together (using names) and then returns either the colour value or the colour name depending on what was selected on the dropdown. <br>
For example:
if the the two colours inputted into the block are ![#0247FE](https://placehold.co/15x15/0247FE/0247FE.png) **Blue** and ![#FEFE33](https://placehold.co/15x15/FEFE33/FEFE33.png) **Yellow** then it will return ![#66B032](https://placehold.co/15x15/66B032/66B032.png) **Green**.
<br>
### Get Colour Block 
This block is really simple. It converts a colour name into a colour value.
