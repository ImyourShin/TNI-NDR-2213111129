# 📈 TradingLite - Advanced Stock Analysis Platform



## ✨ ฟีเจอร์หลัก

### 📊 ข้อมูลตลาดแบบ Real-Time
- ราคาหุ้นและข้อมูลตลาดแบบสด
- หลายช่วงเวลา (1 นาที ถึงข้อมูลสูงสุดที่มี)
- การวิเคราะห์ Volume และสถิติการซื้อขาย
- ข้อมูลราคาในอดีตที่ปรับแต่งช่วงเวลาได้

### 📈 การวิเคราะห์ทางเทคนิคขั้นสูง
- **Interactive Charts**: กราฟ Candlestick และ Line chart พร้อมฟังก์ชัน zoom และ pan
- **Technical Indicators**:
  - Moving Averages (SMA/EMA) ที่ปรับแต่งช่วงเวลาได้
  - RSI (Relative Strength Index)
  - MACD (Moving Average Convergence Divergence)
  - Bollinger Bands

### 💡 Trading Recommendations
- คำแนะนำ Buy / Sell / Hold โดยวิเคราะห์จากหลายตัวชี้วัด
- การวิเคราะห์ Support และ Resistance levels

### 📋 ข้อมูลบริษัทและตลาด
- ข้อมูลพื้นฐานของบริษัท
- Business summary และข้อมูลอุตสาหกรรม
- การวิเคราะห์ Volatility และ Performance

## 🚀 การติดตั้งและใช้งาน

### 1. Clone Repository จาก GitHub

```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/TradingLite.git

# เข้าไปในโฟลเดอร์โปรเจค
cd TradingLite
```

### 2. ติดตั้ง Dependencies

```bash
# สร้าง virtual environment (แนะนำ)
python -m venv tradingLite_env

# เปิดใช้งาน virtual environment
# สำหรับ Windows:
tradingLite_env\Scripts\activate
# สำหรับ macOS/Linux:
source tradingLite_env/bin/activate

# ติดตั้ง required packages
pip install -r requirements.txt
```

### 3. เรียกใช้งานแอพพลิเคชัน

```bash
streamlit run app.py
```

แอพพลิเคชันจะเปิดขึ้นมาในเบราว์เซอร์ที่ `http://localhost:8501`

## 📦 Dependencies

pip install -r requirements.txt

```


## 📱 วิธีใช้งาน

### 1. การค้นหาหุ้น
- ป้อนสัญลักษณ์หุ้น (เช่น AAPL, GOOGL, TSLA) ในช่อง Stock Symbol
- ระบบจะตรวจสอบความถูกต้องของสัญลักษณ์อัตโนมัติ

### 2. การตั้งค่าการวิเคราะห์
- เลือกช่วงเวลาสำหรับการวิเคราะห์ (1 วัน ถึง Maximum Available)
- เลือกความถี่ของข้อมูล (1 นาที ถึง Monthly)
- เลือกประเภทกราฟ (Candlestick หรือ Line Chart)

### 3. การใช้งาน Technical Indicators
- เปิด/ปิด Volume chart
- เลือก Moving Averages และปรับแต่งช่วงเวลา
- เปิดใช้งาน RSI, MACD, และ Bollinger Bands
- ปรับแต่งความสูงของกราฟ

### 4. การดูผลการวิเคราะห์
- **Chart Analysis Tab**: ดูกราฟและ Technical indicators
- **Technical Indicators Tab**: ดูคำแนะนำการเทรดและการวิเคราะห์ขั้นสูง  
- **Market Data Tab**: ดูข้อมูลบริษัทและสถิติตลาด


### Enhanced Metrics Dashboard
- Live market dashboard พร้อมข้อมูลครบถ้วน
- การเปรียบเทียบ Performance ในหลายช่วงเวลา
- การวิเคราะห์ Volume patterns
- Key technical levels (Support/Resistance)

### Advanced Statistical Analysis
- Volatility analysis
- Risk metrics (Beta, Sharpe ratio)
- Drawdown analysis
- Performance comparison

## 🛠️ การพัฒนาและปรับแต่ง

### การเพิ่ม Technical Indicators ใหม่
1. เพิ่มฟังก์ชันคำนวณใน `app.py`
2. เพิ่ม UI controls ใน sidebar
3. เพิ่มการแสดงผลในกราฟหลัก

### การปรับแต่ง UI/UX
- แก้ไข CSS ใน `st.markdown()` sections
- ปรับ layout ด้วย `st.columns()` และ `st.container()`
- เพิ่ม theme และ color schemes

## 📊 Data Sources

- **Yahoo Finance API** ผ่าน yfinance library
- ข้อมูล Real-time และ Historical data
- รองรับตลาดหุ้นทั่วโลก
- ข้อมูลบริษัทและ Financial metrics

## ⚠️ ข้อจำกัดและการใช้งาน

- ข้อมูลจาก Yahoo Finance อาจมีความล่าช้า
- การใช้งานมากเกินไปอาจถูกจำกัดจาก API
- คำแนะนำการเทรดเป็นเพียงข้อมูลอ้างอิง ไม่ใช่คำแนะนำการลงทุน
- ควรทำการวิเคราะห์เพิ่มเติมก่อนตัดสินใจลงทุน

## 👨‍💻 Developer

**Teshin Bubpha**  
TNI-NDR-2213111129



## 📄 License

โปรเจคนี้เป็น Open Source สำหรับการศึกษาและพัฒนา

## 🆘 การแก้ไขปัญหา

### ปัญหาที่พบบ่อย

1. **ModuleNotFoundError**: ตรวจสอบการติดตั้ง dependencies
2. **Data loading errors**: ตรวจสอบการเชื่อมต่ออินเทอร์เน็ต
3. **Symbol not found**: ใช้สัญลักษณ์หุ้นที่ถูกต้อง



💡 **หมายเหตุ**: แอพพลิเคชันนี้พัฒนาขึ้นเพื่อการศึกษาและการวิเคราะห์ข้อมูลหุ้น ไม่ใช่คำแนะนำการลงทุน โปรดใช้วิจารณญาณในการตัดสินใจลงทุน