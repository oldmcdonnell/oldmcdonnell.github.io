<h1>My first blog entry.</h1>

![paper image](/img/PIC.jpg)

This is my first blog entry. We should be easing in the process of getting ready for bootcamp. I expect we will be working with the publishing side of things to a greater extend than I had previously. 

Learning git through differing methods is interesting. 


<details>
<summary>My top languages</summary>
  
| Rank | Languages |
|-----:|-----------|
|     1| Python    |
|     2| MySQL     |
|     3| PHP     |
|     4| Action Script      |
|     9| Javascript  |

</details>

<h6>code</h6> 

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
- [ ] Clean up assignment
- [ ] Figure out how to get the nifty linkable URL

## Arts
