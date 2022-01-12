# Process Appendix 5a data

## Implementation steps

- Create and activate a virtual environment, e.g.

  `python3 -m venv venv/`
  `source venv/bin/activate`

- Install necessary Python modules via `pip3 install -r requirements.txt`


## Usage

### To download Taric files:
`python3 download.py`

### To retrieve useful information from Taric files for validation purposes:
`python3 parse.py`

### To build an updated code tree:
`python3 codes.py`
- Parameters = date and scope
- e.g. python3 codes.py 2022-01-01 uk
- or   python3 codes.py 2022-01-01 eu

### To build current quota position:
`python3 export_quotas.py uk`
`python3 export_quotas.py xi`
