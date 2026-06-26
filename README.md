# Flask DevOps Lab - Version B

## Usage

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

The application includes the following routes:

* `/api/health` returns a JSON health check showing the app is running.
* `/api/config` returns the configuration data from `config.json`.
* `/api/report` returns diagnostic information such as hostname, Python version, and uptime.
