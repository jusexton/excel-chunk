# Excel Chunk

Python script used to chunk or batch large excel worksheets into many smaller files.

## How It Works

Execute the script with the below:
`python main.py --file=filemame --sheet-name=sheetname --chunk-size=100`
Specify the file that should be read, the worksheet that should be chunked and a chunk size (default 1000).
The result, a chunk folder is created and your chunked files under it.

## Usage

1. Install dependencies `pip install -r requirements.txt`. (Optionally within a venv)
2. Place the file that needs to be chunked in this directly.
3. Execute the following: `python main.py --file=filemame --sheet-name=sheetname --chunk-size=100`