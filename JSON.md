# JavaScript Object Notation (JSON)

### About

JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. 

JSON is built on two structures:

1. A collection of name/value pairs. In various languages, this is realized as an object, record, struct, dictionary, hash table, keyed list, or associative array.

2. An ordered list of values. In most languages, this is realized as an array, vector, list, or sequence.

These are universal data structures. Virtually all modern programming languages support them in one form or another. It makes sense that a data format that is interchangeable with programming languages also be based on these structures.

In JSON, they take on these forms:

* An object is an unordered set of name/value pairs.
* An object begins with { (left brace) and ends with } (right brace). Each name is followed by : (colon) and the name/value pairs are separated by , (comma).

### Examples

1. Me
'''{
  "me": {
    "name": {
      "first": "David",
      "last": "Hunt"
    },
    "age": 26,
    "location": {
      "house": "123 Main Street",
      "city": "Augusta",
      "state": "GA"
    },
    "favorite food": "fajitas"
  }
}'''
2. A taco
'''{
  "taco": {
    "shell": "soft",
    "meat": "beef",
    "cheese": true,
    "lettuce": true,
    "spicy": false
  }
}'''

### Tips

We find that the most common issues, or mistakes, incurred when working with JSON usually involve conversions to and from JSON, or parsing.

At times, inherent methods like 'to_json' are not effective enough to create the objects necessary for our APIs, thus items like bldr https://github.com/ajsharp/bldr and rabl https://github.com/nesquena/rabl help us out.

These additional functions require JSON parsing, something we can provide using 'oj'. https://github.com/ohler55/oj

### Notes

It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.

### Resources

1. JSON.org
  http://www.json.org/
  Straight to the horse's mouth.

2. JSON-js
  https://github.com/douglascrockford/JSON-js
  The files in this collection implement JSON encoders/decoders in JavaScript.

3. JSON Lint
  http://jsonlint.com/
  Online, json validator
  Check for errors and such.

4. W3
  http://www.w3schools.com/json/
  World Wide Standard
  Permanently there

5. Can I Use?
  Check for browser compatability in JSON parsing
  http://caniuse.com/json