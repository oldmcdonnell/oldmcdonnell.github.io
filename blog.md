# Index
- [First Week](mMy-first-blog-enry)
- [Second Week](#second-week)
- [Third Week](#third-week)
- [Fourth Week](#fourth-Week)
- [Fifth Week](#fifth-Week)


# My First Blog Enry

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

#### sample code

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

###Second Week

### What is something you wish you could do but currently do not have the coding skills to accomplish?

I already used things like dreamweaver and photoshop to create websites. I'm having to start all over and it's infuriating because I know there are applications that can do 10^10 what I can in code

### What are you struggling with?

I'm having to commit and push multiple times for it to register on the blog. I'm not sure why. My links work in github but not .io. 

### How do you solve a problem?

Usually i search for solutions or look for other code. Sometimes I will ask for help

### What methods do you use to help yourself get unstuck?

I will work on something else or relax and change focus. Sometimes watching a dumb show for a couple minutes can help me relax and then I sometimes come up with a better solution



---

###Fourth Week

### What was helpful during Onboarding working remotely?

Setting my own schedule and just making time to eat in general. 

### What hindered your progress during Onboarding?

I was confused by some of the prompts or assignments. We had just created a blog and then we told to update the blog but which blog? Stuff like that. 

### How did you overcome challenges during Onboarding?

Asking questions in slack. 

###Fifth Week

### What is the number one thing that held you back this week? Why?

CSS was difficult to implement alongside botstrap. I got stuck with ome of the code and maybe should have abondoned it and started over. I should have gotten the asssest and layout sorted out first

### What is one thing you would like to learn more about regarding JavaScript (JSON, Data Structures), Bootstrap, or Atomic Design?
### What is your “Why”?

JSON sounds interesting, I want ot know more about memory for webbrowsers and how to use it for web design. As far as Atomic I definietly need to spend more time in pseudocode. My why is to get to a point where I can develop things that are complex but made simply. 

---
<h6>Arts</h6>

[Instagram](https://www.instagram.com/mcdonnell.eoin/)

[Deviantart](https://www.deviantart.com/aliramojo)

---

[linkedIN](https://www.linkedin.com/in/eoin-mcdonnell-01078923/)