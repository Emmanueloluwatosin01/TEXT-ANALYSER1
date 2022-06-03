escribe: wordCounter()

Test:"It should return 1 if a passage has just one word."
Code:
const text = "Emmanuel";
wordCounter(text);
Expected Output:1

Test:"It should return 2 if a passage has two words."
Code:
const text ="Hi Emmanuel";
wordCounter(text);
Expected Output: 2;

Test:"It should return 0 for an empty string";
code:wordCounter("");
Expected Output : 0;

Test:"It should return 0 for a string that is only spaces."
code:wordCounter("          ");
Expected Output : 0;

Test:"It should not count numbers as words."
code:wordCounter("hi Emmanuel 77 19");
Expected Output : 2;


Describe:numberOfOcurrencesInText()

Test:"It should return 0 occurence of a word for an empty string."
Code:
const text = "";
const word = ""
numberOfOccurencesInText(word,text);
Expected Output:0;

Test:"It should return 1 occurence of a word when the word and the text are the same."
Code:
const text = "Emmanuel";
const word = "Emmanuel"
numberOfOccurencesInText(word,text);
Expected Output: 1;

Test:"It should return 0 occurence of a word when the word and the text are the different."
Code:
const text = "Emmnanuel";
const word = "Nuel"
numberOfOccurencesInText(word,text);
Expected Output: 0;

Test:"It should return the number of occurences of a word."
Code:
const text = "red blue red red red green";
const word = "red"
numberOfOccurencesInText(word,text);
Expected Output: 4;

Test:"It should return a word match regardless of case."
Code:
const text = "red RED Red green Green GREEN";
const word = "Red"
numberOfOccurencesInText(word,text);
Expected Output: 3;

Test: "It should return a word match regardless of punctuation."
Code:
const text = "Red! Red. I like red, green, and yellow.";
const word = "Red";
numberOfOccurrencesInText(word, text);
Expected Output: 3;

Test: "If an empty string is passed in as a word, it should return 0."
Code:
const word = "";
const text = "red RED Red!";
wordCounter(word, text);
Expected Output: 0



Describe: boldPassage()

Test: "It should return a non-matching word in a p tag."
Code:
const word = "hello";
const text = "yo";
boldPassage(word, text);
Expected Output: "<p>yo</p>"

Test: "It should return a matching word in a b tag."
Code:
const word = "hello";
const text = "hello";
boldPassage(word, text);
Expected Output: "<p><b>hello</b></p>"

Test: "It should wrap words that match in `b` tags but not words that don't."
Code:
const word = "hello";
const text = "hello there";
boldPassage(word, text);
Expected Output: "<p><b>hello</b> there</p>"

Test: Itshould mask offensive words in astericks.The offensive words are  ["biffaroni", "loopdaloop", "zoinks", "muppeteer"];
code:
const word =  "gabriel is a zoinks";
Expected Output:"gabriel is a *****";






# SITE NAME
TEXT ANALYSER
# NAME OF CONTRIBUTORS
EMMANUEL ENYAH AMOS
## BRIEF DESCRIPTION OF THE PROJECT
It's a Text Analyser website and it helps in testing if our code would pass or fail.
## TECHNOLOGIES USED
* HTML
* CSS
* BOOTSTRAP
* jAVASCRIPT
* README.md
## LONGER DESCRIPTION OF THE PROJECT
The site contains information about TESTING  website. How it really looks like. The website 
### KNOWN BUGS
1. some difficulties putting my javascripts together
2. Some function were hard to fit in cos it was used wrongly
3. It was hard testing if it would fail or pass
## WEBPAGE LINK
https://
## CONTACT INFORMATION
* 08141856186
* oluwatosinmanny01@gmail.com