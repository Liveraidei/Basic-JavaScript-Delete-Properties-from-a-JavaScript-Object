# Basic-JavaScript-Delete-Properties-from-a-JavaScript-Object
Delete the "tails" property from myDog. You may use either dot or bracket notation.

We can also delete properties from objects like this:

delete ourDog.bark;

Example:

var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"],
  "bark": "bow-wow"
};

delete ourDog.bark;
After the last line shown above, ourDog looks like:

{
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
}
