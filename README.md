# WareFlow: Inventory Management System

**WareFlow** is a dynamic, web-based inventory management platform developed using Python and Streamlit. Designed to simplify warehouse operations, it provides real-time insights into inventory distribution, order handling, and supply chain analytics—all in one interactive dashboard.

---

## 🔧 a) Key Features

### 1) Dashboard & Analytics
- Live inventory monitoring  
- Warehouse usage metrics  
- Fulfillment & delivery statistics  
- Supply chain KPIs  
- Interactive and visual data insights  

### 2) 🗺 Inventory Distribution
- Optimization across multiple warehouses  
- Geographic distribution visualization  
- Cost-efficient allocation logic  
- Real-time routing and mapping  

### 3) Order Management
- End-to-end order tracking  
- Prioritized fulfillment system  
- Delivery timeline alerts  
- Smart allocation recommendations  

### 4) Warehouse Management
- Monitor storage capacity & stock levels  
- Reduce storage costs with analytics  
- Identify underutilized resources  
- Location-based warehouse analysis  

### 5) Supplier Management
- Evaluate supplier performance  
- Track reliability and lead times  
- Measure quality and consistency  
- Generate supplier insights  

---

## 🚀 b) Getting Started

### Prerequisites
- Python 3.9 or newer  
- pip (Python package installer)  
- Git (optional for cloning)

### Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/WareFlow.git
   cd WareFLow
   ```

2. Set up a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install all dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the application:
   ```bash
   streamlit run src/app.py
   ```

---

## 📁 c) Project Structure

```
WareFlow/
├── src/
│   ├── app.py              # Main app entry point
│   ├── backend/
│   │   ├── __init__.py
│   │   ├── data_loader.py  # Data ingestion & preprocessing
│   │   └── optimizer.py    # Core optimization logic
│   └── utils/
│       └── helpers.py      # Shared utility functions
├── data/
│   ├── sample_warehouses.csv
│   ├── sample_sales.csv
│   └── additional sample datasets...
├── tests/
│   └── test cases and scripts...
├── docs/
│   └── documentation & assets...
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🧑‍💻 d) How to Use

1. **Login** to your account  
2. Choose your **data source**:
   - Built-in sample data  
   - Upload your CSV file  
   - Connect to a database  
3. Navigate via the sidebar to explore:
   - Overview  
   - Inventory & Order Management  
   - Supplier Management  
   - Optimization Tools  
   - Help / User Guide  

---

## 📊 e) Data Format Examples

### Warehouse CSV

```csv
warehouse_id,name,capacity,current_stock,location,storage_cost,latitude,longitude
W001,Mumbai Central,10000,7500,Mumbai,1200,19.0760,72.8777
W002,Singapore Hub,15000,12000,Singapore,1500,1.3521,103.8198
```

### Order CSV

```csv
order_id,date,product_id,quantity,delivery_deadline,status,delivery_latitude,delivery_longitude
ORD001,2025-03-24,P001,500,2025-03-26,Pending,19.0760,72.8777
ORD002,2025-03-24,P002,750,2025-03-25,Urgent,1.3521,103.8198
```

---

## ⚙️ f) Configuration Options

- Connect with MySQL, PostgreSQL, or SQLite  
- Set optimization parameters per warehouse  
- Customize dashboard preferences  
- Adjust time zone settings for delivery analytics  

---



## 📜 License

Licensed under the **MIT License**.  
See the `LICENSE` file for more details.

---

**Built with 💡 and ☕ by Kushi Varadaraj**
