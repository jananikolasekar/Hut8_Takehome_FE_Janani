# Running Backend
### Requirements
* Must have `python3` installed 

from the root (./sampleBackend) directory run:

```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
uvicorn main:app --reload 
```

### Frontend application should app and running in http://localhost:3000/