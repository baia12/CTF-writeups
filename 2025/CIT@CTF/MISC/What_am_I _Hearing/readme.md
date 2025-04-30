## What am I Hearing

>Bro what am I hearing rn

>Flag Format: CIT{example_flag}




## Solution
In this Challenge we are give audio file
Listening to the given audio file, it sounds like morse code. (10 minute HUHUHUH)

Using a morse code [decoder](https://morsefm.com/) this decoder is faster in decode the morse code so i recommend it to use👻

so we get this string after decode:

```bash
....................!?.?...?.......?...............?....................?.?.?.?.!!?!.?.?.?!!!!!!!.............!.......................!..?..............................................!.!!!.?.!!!!!!!!!!!!!!!!!!!!!!!!!!!.!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!.........!..?!!!!!!!!!!!!!!!!!.?.!!!!!!!!!!!!!.........................................!.!!!!!!!!!.................................!.?.................................................!..?..........!..?!!!!!!!!!...............................!.
```

Using a cipher identifier like [this one](https://www.dcode.fr/cipher-identifier), it says that the string is most likely encrypted using `Ook!`. 

Using the Ook! decoder, you get the flag. 

## FLAG:
>`CIT{zG48r2FBR6Wn}`
