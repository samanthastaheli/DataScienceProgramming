# Project Document Title

__YOUR NAME__

_This `.md` file should be used to finalize your report. You will need to compile the report into a `.pdf` document and submit it on canvas._

_Use the [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) VS Code extension to work with Markdown files (`.md`)._

## Project Summary

_A short (3-4 sentences) paragraph that summarizes your work.._

## Technical Details

_In this section, you will:_

- _Have subheaders for each grand question, like the ones below._

#### Grand Question 1
#### Grand Question 2
#### Etc.

- _Write out the answer to each grand question, and describe your charts and tables. I highly recommend [Grammarly](https://grammarly.com/) to fix your spelling and grammar. Writing clearly takes time! Spend the time to practice._  

- _Provide charts that address the Grand Questions. The Markdown code to include images looks like this:_

```
![](path_to_image_on_your_computer.png)
```

![](path_to_image_on_your_computer.png)

- _Provide tables that address the Grand Questions. You can generate Markdown code for tables using the `to_markdown()` python command._

```
s = pd.Series(["elk", "pig", "dog", "quetzal"], name="animal")
print(s.to_markdown())
|    | animal   |
|---:|:---------|
|  0 | elk      |
|  1 | pig      |
|  2 | dog      |
|  3 | quetzal  |
```

|    | animal   |
|---:|:---------|
|  0 | elk      |
|  1 | pig      |
|  2 | dog      |
|  3 | quetzal  |

- _You might include small code snippets to highlight important calculations or decisions. You can use Markdown to format text like code using three backticks:_

````
```python
import numpy
import pandas

my variable = 5
```
````

```python
import numpy
import pandas

my variable = 5
```


## Appendix A

_This is where your python script will go. Your code should be commented and well organized._

```python
# paste your python script in here!
```