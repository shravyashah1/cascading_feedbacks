# Lab Notebook

## **Week 1**
| Session | What I Did Overall |
|---------|--------------------|
| 1.1     |GitHub + repo setup |
| 1.2     |Colab Environment   |
| 1.3     |Markdown practice   |


## 2026-08-03 · Session 1.1
- Made the GitHub repo and full folder skeleton (12 files across data/, src/, results/, notebooks/)
- Created a practice branch, added a line, merged it into main, deleted the branch. Branches feel safe
- Nothing broke. First-commit rush is real
- What's next: Session 1.2--Using Google Colab

## 2026-08-04 · Session 1.2
- Mounted Colab to Google drive
- Used a token to push new glossary term into the glossary using Colab code
- The token wasn't working at first because there was an unnecessary space in the token, so I had to use a the .strip() function to make the token valid (without the extra space)
- If you ever create a new file then you need use the following code to mount to Google Drive and push/pull something into GitHub:

**For mounting to Google Drive**
```python
from google.colab import drive
drive.mount('/content/drive')
%cd /content/drive/MyDrive/cascading_feedbacks
```
**For pushing/pulling into GitHub**
```python
from google.colab import userdata
token = userdata.get('GitHubToken').strip()
```
- What's next: Session 1.3--Practicing using Markdown features

## 2026-08-06 · Session 1.3
- Practiced using Markdown headings, bullet points, code block, tables, etc.
- Didn't type python tag after the backticks before typing in the code for the code block, so the first line got eaten
- What's next: Session 1.4--Researching for the project
