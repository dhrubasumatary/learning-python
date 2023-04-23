## Identifiers in Python

  

Identifiers are a fundamental concept in Python, so it's important to understand them thoroughly.

_*An identifier is a name given to a variable, function, class or any other user-defined object in Python. It is a sequence of characters that consists of letters, digits and underscores, but it cannot begin with a digit.*_

## WTF is it ?
let's say we are building an AI program to analyze images from space. We may have identifiers such as 
- `image_data  `,  = [some_tokenized_pixel_data]
- `object_detection_model `,  
- `feature_extraction_algorithm `, 

These identifiers help us to refer to specific variables, functions, or objects in our code. However, we cannot use keywords such as  : 
- `if`, 
- `else `, 
- `lambda`, 
- `True` etc. 
   
 as identifiers as they have predefined meanings in Python.
 
``` 
Yes ! keywords are identifiers too but they are fixed/reserved
```


### Rules for Naming an Identifier

Here are some rules to follow when naming an identifier:

- Identifiers cannot be a keyword.
- Identifiers are case-sensitive.
- It can have a sequence of letters and digits. However, it must begin with a letter or underscore (`_`). The first letter of an identifier cannot be a digit.
- It's a convention to start an identifier with a letter rather than an underscore.
- Whitespaces are not allowed.
- We cannot use special symbols like `!`, `@`, `#`, `$`, and so on.

### Examples of Valid and Invalid Identifiers in Python

| Valid Identifiers   | Invalid Identifiers |
|---------------------|---------------------|
| score               | @core               |
| return_value        | return              |
| highest_score       | highest score       |
| name1               | 1name               |
| convert_to_string   | convert to_string   |

### Things to Remember

- Python is a case-sensitive language. This means that `Variable` and `variable` are not the same.
- Always give identifiers a name that makes sense. While `c = 10` is a valid name, writing `count = 10` would make more sense and would be easier to understand when you look at your code after a long time.
- Multiple words in an identifier can be separated using an underscore, like `this_is_a_long_variable`.


### Scary codes we will try to understand

```python
if len(customer_question) > 0:
    bot_response = generate_bot_response(customer_question)
    response_confidence = calculate_response_confidence(bot_response)
    if response_confidence >= 0.8:
        send_response(bot_response)
    else:
        send_response("I'm not sure, could you please rephrase your question?")
else:
    send_response("Please enter a question.")

```
```Let's take a look at this amazing AI chatbot code! ```

We've got some really clever identifiers here, folks. `customer_question` is used to hold the text of the customer's question - I mean, who would have thought of that?! And don't even get me started on `bot_response` - it's almost as if we're talking to a real bot, not just some lines of code!

And as for those Python keywords - `if`, `else`, `len`, and `>=` - they're the real heroes of this code. I mean, without them, who knows what kind of chaos would ensue? We've got the flow of the code under control thanks to these little guys.

And let's not forget about `response_confidence` - because the bot needs to be confident in its responses, just like a real human. It's a numerical value that gives us an indication of how sure the bot is about its response, which is just plain brilliant.

So there you have it, folks - a shining example of how Python and identifiers can work together to create an AI chatbot that's almost indistinguishable from a real human. Just try not to get too caught up in the chatbot's responses - we don't want to start thinking it's smarter than us!