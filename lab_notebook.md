# Lab Notebook

## 2026-08-03 · Session 1.1
- Made the GitHub repo and full folder skeleton (12 files across data/, src/, results/, notebooks/).
- Created a practice branch, added a line, merged it into main, deleted the branch. Branches feel safe.
- Nothing broke. First-commit rush is real.

## 2026-08-04 · Session 1.2
- Mounted Colab to Google drive
- Used a token to push new glossary term into the glossary using colab code
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
