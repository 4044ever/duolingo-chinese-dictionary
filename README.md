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

Is the data complete?  
No, beside missing words that I still haven't found yet or simply missed I can only see data up to the lesson I am currently doing, that is Section 4, Unit 6 right now. I also started curation the data near the end of Section 3, so I presume there are many words that are missing and hard to find because going through all the previous lessons is rather tedious. But this is whre YOU can help.

Is there any data left out?  
Yes. I leave out out all single charactersthat do not have a meaning by itself. Example: 可以 is a word and we all all know, but neither 可 nor 以 is used by itself. Of course 可以, 可乐, 以前 etc are all in the list. I also left out some locations, like Berlin, New York, which I fin not that relevant. 

What can I do with that?  
Use it create Anki flashcards or any other things that can support language learning outise of Duolingo

Can I support the project?  
YES! When you do Duolingo, keep an eye on words that might be missing in the list. Missing means, they are in lessons, but somehow not in the  Duolingo Dictionary at https://www.duolingo.com/characters - or not in my data.

Why the data is called something with `pairs`?  
Because a created a Duolingo like pairs game for my personal use. But the data is ideentical to the dictionary.

If you see an error in my data, let me know!
