# duolingo-chinese-dictionary

Just an idea for for now:  A Duolingo Chinese Dictionary

But Duolingo has a Chinese Dictionary at https://www.duolingo.com/characters  
True. But it's hard to download. It has also some trsanslation errors andmany words from lessons are missing.

How is the data stored?  
CSV and JSON. The JSON is created from the CSV. CSV can open in Excel and other spreadsheet software. The formats are:

CSV

```
chinese,pinyin,english,lesson
水,shuǐ,water,1-1
```

JSON
```
  {
    "chinese": "水",
    "pinyin": "shuǐ",
    "english": "water",
    "lesson": "1-1"
  }
```

What can I do with that?  
Use it create Anki flashcards or any other things that can support language learning outise of Duolingo

Can I support the project?  
YES! When you do Duolingo, keep an eye on words that might be missing in the list. Missing means, they are in lessons, but somehow not in the  Duolingo Dictionary at https://www.duolingo.com/characters - or not in my data.

If you see a error in my data, let me know too.
