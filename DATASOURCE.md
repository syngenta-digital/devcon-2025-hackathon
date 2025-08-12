# 📊 Data Sources & Connection Guidelines

## ⚠️ CRITICAL: Data Security Policy

> **🔒 MANDATORY:** Only use **MOCK DATA** for this hackathon. Using real or production data is **STRICTLY PROHIBITED** and may result in disqualification.

---

## 🎯 Recommended Data Sources

### 1. **Mock Data (Primary Recommendation)**
- ✅ **Best practice** for hackathons
- ✅ Safe and compliant
- ✅ No privacy concerns
- ✅ Can be shared publicly

### 2. **Excel Data Sources**
- ✅ Easy to create and modify
- ✅ Can be uploaded directly to n8n
- ✅ Perfect for structured data scenarios
- 🔗 Use n8n's Excel connector

### 3. **JSON Datasets**
- ✅ Lightweight and flexible
- ✅ Easy to generate programmatically
- ✅ Perfect for API-like data structures
- 🔗 Use n8n's JSON parser

### 4. **Temporary RDS Instances**
- ✅ For complex database scenarios
- ⚠️ **Must contain ONLY mock data**
- ⚠️ Teams responsible for cleanup after hackathon
- 🔗 Connect via bastion host if needed

---

## 🔧 Connection Methods

### RDS Connection (If Required)
1. **Create bastion host** for secure connection
2. **Use mock data only** - never production data
3. **Clean up resources** after hackathon completion
4. **Delete bastion hosts and keys** post-event

### Direct File Upload
1. **Excel files:** Use n8n's Excel node
2. **CSV files:** Use n8n's CSV parser
3. **JSON files:** Use n8n's JSON node

---

## 🚫 What NOT to Use

- ❌ Production databases
- ❌ Real customer information  
- ❌ Sensitive business data
- ❌ Personal identifiable information (PII)
- ❌ Financial records
- ❌ Any data marked as confidential

---

## 💡 Mock Data Resources

### Sample Data Generators:
- [Mockaroo](https://mockaroo.com/) - Generate realistic test data
- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - Fake REST API
- [Random Data API](https://random-data-api.com/) - Generate random datasets

### Sample Datasets:
- **E-commerce:** Product catalogs, orders, customers
- **HR:** Employee records, departments, salaries
- **Finance:** Transactions, accounts, budgets
- **IoT:** Sensor readings, device data, telemetry

---

## 📞 Support

Need help with data connections? Contact the support team:
👨‍💻 @Rahul Miragi | @Jacques Sa | @Akshay Dharerao | @Lalitkumar | @Rahul Sachdeva

---

**Remember: When in doubt, use mock data! 🛡️**