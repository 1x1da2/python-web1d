# Alex

## The game
The user can create a game, in with, he will search for a word.
You save each try, and the result.

For example
you search for lions

the user send lotor
you sen32d 10x0x

Where x is not good
and 1 is good
and 0 is not at the right position

The response should be like this

```javascript
{
    "word": "loto4r",
    "response": "10X0x"
    "game": {123}
}
```

## Things t2o do

- Add vérification to the route already created
- Finished the verify route to send the response to the user
- Finished the CRUD of Word
