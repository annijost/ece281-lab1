# ECE 281 Lab 1 Prelab

## Prelab questions

### Truth Table

| A | B | C | D | Y |
|---|---|---|---|---|
| 0 | 0 | 0 | 0 | X |
| 0 | 0 | 0 | 1 | 1 |
| 0 | 0 | 1 | 0 | 0 |
| 0 | 0 | 1 | 1 | 1 |
| 0 | 1 | 0 | 0 | 0 |
| 0 | 1 | 0 | 1 | 1 |
| 0 | 1 | 1 | 0 | 0 |
| 0 | 1 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 0 | 1 | 1 | 0 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 0 | 1 | X |
| 1 | 1 | 1 | 0 | X |
| 1 | 1 | 1 | 1 | X |

### Boolean Equation

$$
Y = A'D+AD'
$$

### Digital Simulations

In this folder are also Digital templates for you to complete and simulate.  Do not change the file names or the input and output labels in Digital otherwise the autograder will not work.  The autograder will look in the prelab folder for the files.

Complete all three circuits using the various approaches (generic multiplexer symbol, 74151 multiplexer chip, and a sum of products using and/or logic gates).

You may also wish to run test cases.  The first two rows of the truth table have been added to the Digital simulation files as a test.  You may wish to edit the test to add more rows and fully cover all possible cases but this is not required.

## Submission

1. Make sure all prelab files are in this folder
2. Commit all files
3. Push to GitHub
4. Submit to Gradescope
5. Verify submission

Documentation Statement: I used 2 videos to help me understand how to make an XOR truth table with NAND gates (https://www.bing.com/videos/riverview/relatedvideo?q=SOP+logic+equation+to+NAND+gate+example&&mid=87D15DDB3787BFD2D3F387D15DDB3787BFD2D3F3&churl=https%3a%2f%2fwww.youtube.com%2fchannel%2fUCOF4cb6qV488VqYuUodrhvQ&mmscn=mtsc&aps=62&mcid=A835EAF895434F4FB180EEC86F067909&FORM=VMSOVR AND https://www.bing.com/videos/riverview/relatedvideo?q=how+to+implement+xor+using+nand+gates+only&&mid=E269B25646D4A62B5C01E269B25646D4A62B5C01&churl=https%3a%2f%2fwww.youtube.com%2fchannel%2fUCXJusRTVilx_8RaSQ0u_tXw&mmscn=mtsc&aps=75&mcid=A064A5813C9B48B185F410EA680B8A1C&FORM=VMSOVR). C3C Katherine and I checked each others work and collaborated to make the design schematics.
