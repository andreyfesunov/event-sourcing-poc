# Info
Python impl for Event Sourcing pattern (with Edge Cases)

## Edge Cases
1. Filtering & Sorting
2. Deleted values of fields (Enums, e.g.)
3. Deleted nested entities (& entities values)
4. Performance
5. Multiple entity changes per action/request

# Installing
1. Init venv:
```bash
python -m venv venv
```
2. Activate venv:
```bash
source venv/bin/activate
```
3. Install packages:
```bash
pip install -r requirements.txt
```
4. Install githooks:
```bash
pre-commit install
```
5. (Optional) Run pre-commit:
```bash
pre-commit run --all-files
```

# Actions
To add dependencies to requirements.txt:
```bash
pipreqs . --force
```
