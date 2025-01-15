# Instructions  

[Alternating capitalization](https://en.wikipedia.org/wiki/Alternating_caps) is a form of text notation in which the capitalization of letters varies by some pattern, or arbitrarily (often also omitting spaces between words and occasionally some letters), such as "aLtErNaTiNg cApS".

Make a function that converts any string to alternating caps.

def alternating_caps(input_string):
    result = ''
    for i, char in enumerate(input_string):
        if i % 2 == 0:
            result += char.upper()
        else:
    
            result += char.lower()
    return result
