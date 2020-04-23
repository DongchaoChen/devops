# Code Review Checklist 
Questions to ask yourself when conducting a code review. 

## Is the code clean and modular?
- Can I understand the code easily?
- Does it use meaningful names and whitespace?
- Is there duplicated code?
- Can you provide another layer of abstraction?
- Is each function and module necessary?
- Is each function or module too long?

## Is the code efficient?
- Are there loops or other steps we can vectorize? (for data usage e.g. pandas)
- Can we use better data structures to optimize any steps?
- Can we shorten the number of calculations needed for any steps?
- Can we use generators or multiprocessing to optimize any steps?

## Is documentation effective?
- Are in-line comments concise and meaningful?
- is there complex code that's missing documentation?
- Do function use effective docstrings?
- is the necessary project documentation provided?

## Is the code well tested?
- Does the code high test coverage?
- Do tests check for interesting cases? 
- Are the tests readable?
- Can the tests be made more efficient?

## Is the logging effective?
- Are log messages clear, concise, and professional?
- Do they include all relevant and useful information?
- Do they use the appropriate logging level?

## Other References
- [Code Review](https://github.com/lyst/MakingLyst/tree/master/code-reviews)
- [Code Review Best Practices](https://www.kevinlondon.com/2015/05/05/code-review-best-practices.html)
