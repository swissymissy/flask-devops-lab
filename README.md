# Flask DevOps Lab
## Usage
1. Activate venv
```bash
source .venv/bin/activate
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Run the app
```bash
python app.py
```
### API endpoints
- ```/api/health/```: check health status of the server
- ```/api/config```: show configuration of app and version
- ```/api/report```: show additional information such as hostname, python version, uptime
- ```/api/images```: display picture 

