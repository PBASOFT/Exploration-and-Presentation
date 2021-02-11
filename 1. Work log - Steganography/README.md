

## 1 .4 .3 Exercise C - Brainstorm on homework assignment
We read through the homework assignment and noted the words we weren’t sure about the meaning of, to fully understand the problem given to us.


We researched the following words

- **Steganography:**

  “the practice of concealing a message within another message or a physical object. In computing/electronic contexts, a computer file, message, image, or video is concealed within another file”.

  *Source: https://en.wikipedia.org/wiki/Steganography*
		

- **Ascii message:**

  A character encoding standard for electronic communication, that uses just 7 bits for each character.

    *Source: https://en.wikipedia.org/wiki/ASCII*


- **Little-endian** 

  Endianness is a term that describes the order in which a sequence of bytes are stored in computer memory
Little-endian is an order in which the "little end" (least significant value in the sequence) is stored first.

  *Source: https://searchnetworking.techtarget.com/definition/big-endian-and-little-endian*



##  1 .5 Homework Assignment

  #### Search queries and websites visited:
  
- 10.18: “how to get data from a png image” 
  - 10:21 https://compress-or-die.com/analyze
  

- 10.24: “steganography png” 
  - 10:25 https://0xrick.github.io/lists/stego/
  - 10:26 https://shanereilly.net/posts/basic_steganography_and_png_files/


####  Stumbling blocks
  We didn’t run into any stumbling blocks as we more or less found the solution in our first try.
  	




####  Diary:

  We only have one entry in our diary, as we had already found the hidden message in the image, when our first 30 min block ran out.


  We are surprised at how fast and unproblematic we found the solution. We didn’t experience any frustrations or dead ends and are currently finishing up wiriting the assignment.




####  What is the message?


  Early in the process of researching we came across a blogpost explaining about different ways of hiding and finding messages in an image as well as encoding and decoding messages.
  One paragraph in the post described how to save data in “the least significant bit” of the colors in each pixel. It caught our attention as it sounded a lot like how the data was encoded in our assignment. We therefore read that part closely and found a tool called zsteg that can be used to decode an image.
  We installed the tool and analysed the image with it. And it revealed the hidden message:

	


![](https://github.com/PBASOFT/Exploration-and-Presentation/blob/main/1.%20Work%20log%20-%20Steganography/42.png)
