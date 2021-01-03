# VBA of Wall Street

## Overview of Project

In this project, I refactored the Module 2 solution code to determine whether refactoring my code successfully made the VBA script run faster.

## Results

### 2017 Versus 2018 Stock Analysis

![2017 Stock Analysis](Resource/VBA_Challenge_2017.png)
![2018 Stock Analysis](Resource/VBA_Challenge_2018.png)

The most significant thing we can see from these two screenshots is that the **Return Rate** on these stocks was down dramatically after one year. In some cases, the **Total Daily Volume** was also decreased (AY, CSIQ, SPWR, etc.). The only two worthy stocks to buy are **ENPH** and **RUN** since they still maintain their positive Return Rate.

### Execution Times comparison

![Original Script](Resource/Original_Script.png)
![Refactored Script](Resource/Refactored_Script.png)

In these screenshots, I used 2018 for the analysis. As you can see, the execution time on the Refactored Script is much faster than the original script (0.04 seconds compares to 0.44 seconds) while still produces the same results. Thus, we can conclude that the Refactored Script has been working successfully.

## Summary:

- What are the advantages and disadvantages of refactoring code in general?
    - Advantages:
        - Makes the code easier to understand.
        - Has chances to add new features, hence might help the program run faster.
        - Detects bad patterns like duplicated code, long functions, misunderstood naming conventions, etc.
    - Disadvantages:
        - Cost of times and money.
        - Need to understand the meaning of the current codes before refactored them.
        - Might introduce new bugs if the new codes is not reviewed properly --> another rounds of refactoring the codes.
- How do these pros and cons apply to refactoring the original VBA script?
    - Pros:
        - The program actually ran faster with the new codes.
        - I think the ticker Index feature helps us to manage the output more efficiently.
    - Cons:
        - It took me lots of time to finish it because I was having trouble implementing these new changes to the original codes. I ended up ignoring the pre-defined hints and rewriting the codes from scratch.

