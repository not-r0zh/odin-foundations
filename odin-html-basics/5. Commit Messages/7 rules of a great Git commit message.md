# The seven rules of a great Git commit message
#### 1. Separate subject from body with a blank line.

Not every commit message requires a body, only one line is enough, but when there's more needed to be said the body have to be separated from the subject with one line.

Example:
```
Lorem ipsum dolor 

sit ametconsectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
```

#### 2. Limit the subject line to 50 characters
As a rule of thumb 50 characters should be limit. This makes them readable and concise. 72 characters is the hard limit.

#### 3. Capitalize the subject line
Basically begin all subject lines with a capital letter.

### 4. Do not end the subject line with a period
It is unnecessary.

#### 5. Use the imperative mood in the subject line
Git itself uses the imperative whenever it creates a commit on your behalf.
###### Simple rule to get it right every time:
* If applied, this commit will "subject line"
Example:
- If applied, this commit will _update getting started documentation
- If applied, this commit will _remove deprecated methods_
- If applied, this commit will _release version 1.0.0_
This wouldn't work for the non-imperative forms:
- If applied, this commit will _~~fixed bug with Y~~_
- If applied, this commit will _~~changing behavior of X~~_
- If applied, this commit will _~~more fixes for broken stuff~~_

#### 6. Wrap the body at 72 characters
The recommendation is to do this at 72 characters, so that Git has plenty of room to indent text while still keeping everything under 80 characters overall.

#### 7. Use the body to explain what and why vs. how
In most cases, you can leave out details about how a change has been made. Code is generally self-explanatory in this regard (and if the code is so complex that it needs to be explained in prose, that’s what source comments are for). Just focus on making clear the reasons why you made the change in the first place—the way things worked before the change (and what was wrong with that), the way they work now, and why you decided to solve it the way you did.

(This is a summary I made for myself from https://cbea.ms/git-commit/)