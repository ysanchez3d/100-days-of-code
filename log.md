# 100 Days Of Code - Log

## Copy/Paste Template Sample

### Day 8: February 9, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 1: January 31, 2024

**Today's Progress**: Started [Boot.Dev](https://boot.dev) back-end development program. I finished chapters 1-4 of the "Learn Python" course. I covered some basic concepts: `variables`, `strings`, `functions declarations`, and 'scope'.

**Key Python Notes**

- Python uses **snake_case** convetion
- **Spaces** MUST be correct for functions, loops, statement, etc... to work properly
- Functions that don't have a `return` keyword automatically return the `None` data type
- Floored Division operator "//" >>> `7 // 3 == 2`
- Valid operators like in JS `+=, -=, *=, /=`
- Exponent operator "**" >>> `3**2 == 9`

**Thoughts:** So far I'm very happy with the course, it is very intuitive and every lesson has hands-on coding. Looking forward to be done with the basic chapters.

**Link to work:** [NONE](#)

### Day 2: February 1, 2024

**Today's Progress**: Continued [Boot.Dev](https://boot.dev) course. Completed chapters 5-9 of the "Learn Python" course. Covered `Scientific Notation`, `Binary numbers`, `Logical Operators`, `Bitwise Operator`, `Comparison Operators`, `Conditional Logic`, `For Loop`, `Lists`, and `Tuples`. Also set up [This repo](https://github.com/ysanchez3d/DataStructures-and-Algorithms-Daily) to practice Test Driven Development(TDD), Algorithms, and Data Structures. Lastly I revisited `Mocha`, `Chai`, and how to properly write this `Markdown` syntax`.

**Key Python Notes**

- Scientific Notation: `print(16e3) #16000.0`, `print(7.1e-2) #0.071`
- Use underscores for readability: `num = 16_000`, `other_num = 71_234_000_000_000`
- Normal school math is a "Base 10" system. Binary uses a "Base 2" system
- Python uses `and` and 'or' instead of `& and ||` for expression evaluation
- Comparison operators: `<, >, <=, >=, ==, !=`
- Conditional Logic: `if:, elif:, else:`
- For Loop: `for i in range(0, 10):` . The range function takes an optional third parameter specifying negative or positive increments.
- Arrays are called "Lists". Use `len(list)` to get the length.
- No index loop syntax: `for tree in trees:`. Use when index is irrelevant.
- Negative Infinity: `Float('-inf')`. Positive Infinity: `Float('inf')`
- Slicing List Syntax: `my_list[start:stop:step]`. stop is exclusive.
- List Contains an item? `item in items_list` >> return True or False
- List Delete items: `del list_items[3] #deletes 4th item`, `del list_items[1:3] #deletes from index 1 to 3(exclusive)`, `del list_items[:] #deletes all items`
- Tuples: Fixed collection size. Usually used to store small groups of related data.
  - Example: `person_touple = ("Yandri", "Sanchez", 30)`

**Thoughts:** Very long day. I was only able to cover so much because of my familiarity with JavaScript. Really enjoying Python so far. Also had a refresher on `Mocha` and `Chai` in order to be able to setup the repo mentioned above.

**Link to work:**[Dynamic Array](https://github.com/ysanchez3d/DataStructures-and-Algorithms-Daily/blob/main/data_structures/dynamicArray.js), [Specs](https://github.com/ysanchez3d/DataStructures-and-Algorithms-Daily/blob/main/test/dynamicArray-spec.js)

### Day 3: February 2, 2024

**Today's Progress**: Practiced TDD by writing specs and then writing the methods. Today I implemented `push()`, `pop()`, `unshift()`, `shift()` on a custom Dynamic Array data structure. Then I practice CSS by doing todays challenge on (https://icodethis.com). Links to todays work below.

**Link to work:**[iCodeThis CSS Challenge](https://iCodeThis.com/submissions/66991), [Dynamic Array](https://github.com/ysanchez3d/DataStructures-and-Algorithms-Daily/blob/main/data_structures/dynamicArray.js), [Specs](https://github.com/ysanchez3d/DataStructures-and-Algorithms-Daily/blob/main/test/dynamicArray-spec.js)

### Day 4: February 3, 2024

**Today's Progress**: Today I completed chapter 10 of the Python course on Boot.Dev. I learned about Dictionaries. I then worked iCodeThis.com daily challenge and practiced CSS positioning. Links to work below..

**Link to work:**[iCodeThis CSS Challenge](https://iCodeThis.com/submissions/67215)

### Day 5: February 4, 2024

**Today's Progress**: Did some of iCodeThis.com daily challenge. Link to work below.

**Link to work:**[iCodeThis CSS Challenge](https://icodethis.com/submissions/67381)

### Day 6: February 5, 2024

**Today's Progress**: Completed Chapters 11 and 12 of the Python course on Boot.dev. Learned about Sets and Error/raising exceptions in Python. Afterwards I built a project that allows users to click a region of the planet(Americas, Europe, Africa, etc...) and then all countries that belong to that region will display with their corresponding flag. Countries Api used from (https://restcountries.com).

**Key Notes**

- Create set: `fruits = {'apple', 'banana', 'mango'}`, `empty_set = Set()`
- Sets are unordered, and guarantee uniqueness
- Add to set: `my_set.add(value)`
- Remove from set: `my_set.remove(value)`
- Convert a List to a Set: #use "set" function `set(list)`
- Convert a Set to a List: #use "list" function `list(set)`
- Two sets may be subtracted using the '-' minus operator.
- Exception errors happen during program execution.
- use `try-except` pattern to handle Exceptions
- Raise Exception: `raise Exception("something bad happening..")`
- Whenever you think something bad could happen in the code always try to raise errors yourself.

**Link to work:**[World Countries Project](https://github.com/ysanchez3d/world-countries)

### Day 7: February 6, 2024

**Today's Progress**: Today I completed the "Learn Python" course on Boot.dev. I then started the "Terminals and Shells" course and completed chapter 1 and 2. Ended the day by building a payment form with html/css. Links below.

**Link to work:**[Payment Form on iCodeThis](https://icodethis.com/submissions/67731)

### Day 8: February 7, 2024

**Today's Progress**: Today I made a chrome extension that lets you pick any color from a webpage and copies the HEX value to the clipboard for easy copy/paste access.

**Link to work:**[Color Detective Extension](https://github.com/ysanchez3d/color-detective)

### Day 9: Thursday, February 8, 2024

**Today's Progress**: Finished chapters 3 and 4 of the terminals and shells course on boot.dev. Build a profile card using html and css.

**Key Notes**

- Every folder and file have assigned permissions (read, write or execute)
- Permissions example: (rwxrwxrwx)(3 for owner, 3 for group, 3 for everyone else)
- Show permissions with `ls -l`
- Change permissions with chmod command (e.g. `chmod -R u=rwx, g=, o= .`)(this says: change mode recursively set user, group and other on current directory ".")
- .sh are shell scripts
- Remove executing priviledges from a file: `chmod -x Filename`
- Add executable privileges: `chmod +x Filename`
- The root user can do anything in the system. Gain access through `sudo`
- There are two types of executables: Compiled and interpreted
  - Compiled programs: Go, C, Rust.
  - Interpreted programs: Ruby, Python, JavaScript
- `SH, Bash and ZSH` are all shells. The latter two are supersets of SH
- Go to home directory: `cd ~`
- When installed programs don't execute from the terminal, its because the path to the executable is not set in the $Path variable.
- Add new path to $Path var: `export Path=$Path: absolute_path_here`
  - Add the export statement to the shells config file(.zshrc) to persist it.
- Manual command: `man ls` -> shows documentation for ls command, man grep, etc..
- Show hidden files: `ls -a`
- Single char flags use one "-". multi-char flags use two "--" dashes (e.g. -h, --help)
- All programs exit with a 0 code. Anythign above 0 means there was an error.
  - Use echo $? to check the code of your last executed terminal line
- Redirecting stream output(STDOUT) to a file: `echo "Hello world" > hello.txt`
- Redirecting error output(STDERR) to a file: `cat doesnotexist.txt 2> error.txt`
- The pipe "|" can be used to send STDOUT of one program into STDIN of another
  -(e.g `echo "hello there" | wc -w`) -> after echo pipe it to word count command.
- Interrupt a program: Ctr+C
- Kill a program: kill PID
  - Displays all running processess: `ps aux`
  - Filter node processes: `ps aux | grep node` -> get the PID and then run the kill command.
- **REMEMBER** `grep` searches for text, `less` shows text

**Thoughts:**
This was a long day with lots of information to take in. Will need to recap at the end of the week. Maybe write a blog post on what I learned.

**Link to work:**[CSS Profile Card](https://www.frontendpro.dev/frontend-coding-challenges/profile-card-component-8LSC0uk1FvdLPAEUXiaY/solutions/co7LG95xO6toKa4G0WbG)

### Day 10: Friday, February 9, 2024

**Today's Progress**: Practiced CSS with daily iCodeThis challenge.

**Link to work:**[iCodeThis work](https://icodethis.com/submissions/68215)

### Day 11: Saturday, February 10, 2024

**Today's Progress**: Complete chapters 1-3 of Boot.Dev pyhton course. I learned about `Classes`, `Encapsulation`, and `Abstraction` in Python.
**Key Notes**

- Methods always take a "self" parameter as first argument which refers to the object itself.
- Constructor method is called `__init__`
- Instance Variables vary from object to object
- Class variables remain the same across all instances of a class and are declared at the top of the class
- Encapsulation: A technique for organizing the code (what should and should not be hidden)
  - Use double underscores "\_\_" to prefix method and properties in order to make them private
- Abstraction: A technique for designing an easy to use interface for complex behavior or data

**Link to work:**[NONE]

### Day 12: Sunday, February 11, 2024

**Today's Progress**: Worked on a TODO app using vanilla javascript(lord help me god and bless me with extra patience lol). Functionality implemented: `add items`, `check and uncheck completed items`
**Thoughts:**  
 Having to do double the work by updating the code and then updating the UI is no fun. Need to start using react soon.
**Link to work:** [TODO list](https://iCodeThis.com/submissions/68747)

### Day 13: Monday, February 12, 2024

**Today's Progress**: Today I only practiced CSS. I'm starting to get much faster and having to use google less since I'm starting to become familiar with the property names and available values.

**Thoughts:**
Starting to enjoy CSS much more.
**Link to work:** [Profile Card](https://iCodeThis.com/submissions/68779)

### Day 14: Tuesday, February 13, 2024

**Today's Progress**: Today I worked on iCodeThis Challenge. I set up the repo to upload css challenges to github.

**Link to work:**[iCodeThis Daily Challenge](https://iCodeThis.com/submissions/68840), [CSS Challenges Repo](https://github.com/ysanchez3d/css-practice)

### Day 15: Wednesday, February 14, 2024

**Today's Progress**: Today I kept improving my CSS. Link below

**Link to work:**[iCode This Challenge](https://icodethis.com/submissions/69182)

### Day 16: Thursday, February 15, 2024

**Today's Progress**: Worked on the Weather app project. I ended up using weatherapi.com. I setup a node server to serve the files and had to do lots of api research to get the data I wanted.

**Thoughts:** God i'm so sick of vanilla Javascript I felt like i was constantly doing stupid google searches for the smallest of things.

**Link to work:**[Weather App Repo](https://github.com/ysanchez3d/weather-app)

### Day 17: Friday, February 16, 2024

**Today's Progress**: Today I finish the Weather app. It took wayyyyy longer than I wanted to, but I learned quite a bit.

**Link to work:**[Weather App Repo](https://github.com/ysanchez3d/weather-app)

### Day 18: Saturday, February 17, 2024

**Today's Progress**: Today I made a profile panel card

**Link to work:**[Profile Panel Card](https://github.com/ysanchez3d/css-practice/tree/main/account_panel)

### Day 19: Sunday, February 18, 2024

**Today's Progress**: Worked on the billing cards css practice

**Link to work:** [Billing Cards](https://github.com/ysanchez3d/css-practice/tree/main/billing_cards)

### Day 20: Monday, February 19, 2024

**Today's Progress**: Worked on creating the quotes app. Allowing you to pick from a range of categories. Mostly worked on setting up the project, tryin to understand handleBars library. and getting the UI made.
**Link to work:**[NONE]

### Day 21: Tuesday, February 20, 2024

**Today's Progress**: Worked on the Quotes app. Very confused with server-side vs client side rendering since I'm using handlebars in the back-end. I find it confusing as to when re-render the page vs just sending a JSON back...as far as the API everything is pretty much rdy to go...
**Link to work:**[NONE]

### Day 22: Wednesday, February 21, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 23: Thursday, February 22, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 24: Friday, February 23, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 25: Saturday, February 24, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 26: Sunday, February 25, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 27: Monday, February 26, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 28: Tuesday, February 27, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 29: Wednesday, February 28, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 30: Thursday, February 29, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**

### Day 31: Friday, March 1, 2024

**Today's Progress**:  
**Key Notes**  
**Thoughts:**  
**Link to work:**
