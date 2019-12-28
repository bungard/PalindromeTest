# PalindromeTest
For your submission, you are asked to implement a solution which will perform three primary functions:

1. Retrieve a JSON file from a remote URL. Your solutions should pull this from a settings file (app.config, web.config. etc). 
A sample file has been provided here: https://github.com/bungard/PalindromeTest/blob/master/string.json

2. Determine if a provided string is a palindrome. Alphanumeric chars will be considered when evaluating whether or not the string is a palindrome.

3. Parse the retrieved JSON file, and pass each element in the "strings" array, into the function in step #2. You should print out the string and result. 
Note: if your submission is web-based, feel free to display this information on the generated page. If this is a console application, printing to the console will suffice.

The JSON file will contain the string to test, and its status as a palindrome. The file will be in this format:
 ```javascript
  {
    	"strings": [{
    			"str": "mom",
    			"result": "true"
    		},
    		{
    			"str": "Taco Cat",
    			"result": "true"
    		},
    		{
    			"str": "Kent State",
    			"result": "false"
    		}]
    }
```
Your solution is expected to handle reasonable exceptions (unanavailable JSON file, improperly formatted file, etc). In the case of an exception, simply outputting the exception message, or comparable message,  will expected.
