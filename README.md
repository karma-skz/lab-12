### Fixing the Buggy Code

- This code has 30 issues out of which 1 is no code in style.css . 
- The total marks for the entire codebase is 40, some issues have more marks than the other one. Style.css is of 5 marks. It will get scaled down to 20. All team members will get equal marks.
- You are suppose to work in teams of 4 or 5
- Each team member has to identify atleast 4 issues and fix atleast 4 issue. If someone doesn't do this, their marks get deducted.
- You are suppose to work on a git repository as collaborators

### What kind of bugs are there

- Bugs which will break your code
- Bugs might be a single word
- Bugs might be section of removed code
- Bugs might be section of unnecessary code
- Bugs might be useless files
- Bugs might be in the UI/UX of the pages
- Bugs might be in the api calls
- Bugs might be in the dependencies  

### submission format

- Make submissions on moodle
- Do not remove .git folder 
- Only 1 submission per team
- Submit it as Corrected_Code.zip

### Add the names of the members and roll numbers of your team below

- Name : Roll Number
- Hemang Joshi : 2024114012
- Aryan Bharania :2024115011
- Shardul Joshi : 2024101077
- Mohammed Raza Ur Rehman : 2024111005

### Table to keep track

| ID  | Issue Description                        | Identified By | Fixed By     |
|-----|------------------------------------------|---------------|--------------|
| 1   |character encoding not set to UTF-8                  | Aryan  |  Aryan |
| 2   |<nav > element doesn't have aria label in items.html                                     |  Aryan            |   Aryan       |
| 3   | <nav > element doesn't have  aria label in news.html                                          | Aryan              |       Aryan       |
| 4   | div container was missing in items.html                                         |   Aryan            |    Aryan          |
| 5   | Wrong method used in users.py (@router.post("/") used in place of @router.post("/"))                                         |   Shardul            |    Shardul          |
| 6   | Use delete_one in place of delete_all in users.py                                         |   Shardul            |  Shardul            |
| 7   | Wrong method used in quiz.py (@router.get("/answer") used in place of @router.post("/answer"))                                         | Shardul              |    Shardul          |
| 8   |get_question() function is wrong in quiz.py as it always gets Id=1 but we wanted random Id                                          | Shardul              |    Shardul          |
| 9   |router = APIRouter() should be implemented in place of router={}                                          | Shardul              |  Shardul            |
| 10  |items.py has duplicate method calling with same route where post("/") is used twice in different ways                                          | Shardul              |  Shardul            |
| 11  |wrong key names in analytics.py we want name and username be to used but cod
| 12  | Style.css is not filled                  |     Narain    |  Whole Team  |
| 13  | The `<script>` tag references styles/profile.js,but the correct path is scripts/profile.js.(profile.html) | Mohammed Raza Ur Rehman | Mohammed Raza Ur Rehman |
| 14  |       The `<form id="answerForm"></form>` is empty, which will break functionality unless dynamically populated by JavaScript. Ensure the scripts/quiz.js file correctly populates this form with answer options.                                   |  Mohammed Raza Ur Rehman              |  Mohammed Raza Ur Rehman             |
| 15  | The `<img id="plot" src="" alt="Analytics Plot" style="max-width: 100%;" />` has an empty src attribute, which will result in a broken image. Ensure the scripts/analytics.js file dynamically sets the src or provide a default placeholder image.                                         |  Mohammed Raza Ur Rehman               |  Mohammed Raza Ur Rehman              |
| 16  | Added class="active" to the `<a>` tag for the current page (profile.html) for better UI/UX.                                         |  Mohammed Raza Ur Rehman               |   Mohammed Raza Ur Rehman                                          |               |              |                                         |               |              |
| 17   | Style.css is not filled (styles.css) | Hemang | Hemang  |
| 18   | Missing import for users router (main.py) | Hemang | Hemang |
| 19   | Users router is not included despite being defined in the codebase (main.py) | Hemang | Hemang |
| 20   | Changed the name field type from int to str | Hemang               | Hemang              |
| 21   | Added BaseModel inheritance to the Item class           | Hemang | Hemang |
| 22  |                                          |               |              |
| 23  |                                          |               |              |
| 24  |                                          |               |              |
| 25  |                                          |               |              |
| 26  |                                          |               |              |
| 27  |                                          |               |              |
| 28  |                                          |               |              |
| 29  |                                          |               |              |
| 30  |                                          |               |              |
