## New Relic events exporter

Export New Relic events into CSV file (or S3 bucket)

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/dpacheconr/nr_events_exporter
cd nr_events_exporter
```

### 2️⃣ Create a Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4️⃣ Configure Environment Variables
```bash
cp .env-sample .env
```
Update the `.env` file as required for your use case.

### 5️⃣ Run the Script
```bash
python3 exporter.py
```

### 6️⃣ Deactiveate virtual environment
```bash
deactivate
```