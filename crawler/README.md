
### Dependencies
* Python 3
### Python Requirements
```
python-dotenv
bs4
requests
lxml
csv
json
```
* (option) Install Python requirements from `requirements.txt`:
```
pip install -r requirements.txt
```

### Configure Settings
* Edit the file `.env.example`, save as `.env`.
```
cp .env.example .env
vim .env
```
You can choose any `PTT board` whatever you want. `PAGE_NUMBER` is max page you need. 
* Set the `IF_SEARCH = true`, if you want to search specific topic (keyword). 
For example:
```
BOARD = 'Gossiping'
PAGE_NUMBER = 100
IF_SEARCH = 'true' # 'true' or 'false'
KEYWORD = 'specific_word_from_BOARD' 
```

### How to Run
```
python app.py
```

### Results
Output `ptt.csv`@[datasets](../datasets)

