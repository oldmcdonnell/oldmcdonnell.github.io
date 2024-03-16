<html lang="en">

<head>
<meta charset="utf-8">
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1> Week 2 Blog</h1>

<h3>What is something you wish you could do but currently do not have the coding skills to accomplish?</h3>

<p id="p1"> I would like to know more about float objects</p>

<h3>What are you struggling with?</h3>

<p id="p1">I want to change the blog to be more episodic like how to make it so that each entry is searchable on it's own. Has it's own time/date stamp<p>

<h3>How do you solve a problem? </h3>

<p id="p1">Usually i search for solutions or look for other code. Sometimes I will ask for help.</p>

<h3>What methods do you use to help yourself get unstuck? </h3>
<p id="p1">I will work on something else or relax and change focus. Sometimes watching a dumb show for a couple minutes can help me relax and then I sometimes come up with a better solution</p>

</body>
</html>


---


<h1>My first blog entry.</h1>

![paper image](/img/PIC.jpg)

This is my first blog entry. We should be easing in the process of getting ready for bootcamp. I expect we will be working with the publishing side of things to a greater extend than I had previously. 

Learning git through differing methods is interesting. 

I have experience building automation engines for testing hardware and maintaining databases. I still haven't built my ranked choice voting app. Currently working through a couple of different courses.

In my freetime I like running with the Hash House Harriers, which is a drinking club with a running problem and painting.

![paper image](/img/hashbasics.jpg)


<details>
<summary>My top languages</summary>
  
| Rank | Languages |
|-----:|-----------|
|     1| Python    |
|     2| SQL       |
|     3| Javascript|
|     4| PHP       |

</details>

<h6>sample code</h6> 

``` python
from flask import Flask, render_template
import pandas as pd


app = Flask(__name__)
df = pd.read_csv("data/dictionary.csv")

@app.route('/')
def home():
    return render_template("home.html")


@app.route('/api/v1/<word>/')
def api(word):
    definition = df.loc[df["word"] == word]['definition'].squeeze()
    result_dictionary = {'word': word, 'definition': definition}
    return result_dictionary


if __name__ == "__main__":
    app.run(debug=True, port=5001)
```
---
- [x] Create resposiotry
- [x] Pull request
- [x] Edit index.md
- [x] Finish Markdown lesson
- [x] Add files to assignment
- [x] Clean up assignment
- [x] Figure out how to get the nifty linkable URL
- [ ] Rank list works in preview but not in the browser


---
<h6>Arts</h6>

[Instagram](https://www.instagram.com/mcdonnell.eoin/)

[Deviantart](https://www.deviantart.com/aliramojo)

---

[linkedIN](https://www.linkedin.com/in/eoin-mcdonnell-01078923/)

