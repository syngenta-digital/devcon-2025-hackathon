# 🚀 DevCon 2025 Hackathon

Welcome to the **DevCon 2025 Hackathon**! This repository contains setup instructions and resources for participants.



---

## 🔑 Access to Portkey

Portkey is an AI gateway that provides unified access to multiple AI models and enhanced observability.

### Setup Steps:
1. You must be included in `ws-devcon-2025-hackathon-role-member` group in Azure AD (contact our support team)
   <!-- 👤 **Admins:** @Rahul Miragi @Jacques Sa @Akshay Dharerao @Lalitkumar -->

2. **Access Portkey** via [app.portkey.ai](https://app.portkey.ai) and sign in via SSO

3. **API Keys** will be pre-configured and provided to teams

### 📚 Portkey Resources:

- 📖 [What is Portkey?](https://portkey.ai/docs/introduction/what-is-portkey)
- 🛠️ [Prompt Engineering Studio](https://portkey.ai/docs/product/prompt-engineering-studio/prompt-playground)  
- 🎥 [Getting Started Video](https://www.youtube.com/watch?v=-rAvz7a24Lk)

---

## 🔧 Access to n8n

n8n is a workflow automation platform that lets you connect different services and automate processes.

### Setup Steps:
1. **Login** to [n8n.syngenta.com](https://n8n.syngenta.com)

2. **Project Creation** (Admin only)  
   <!-- 👤 **Admins:** @Rahul Miragi @Jacques Sa @Akshay Dharerao @Lalitkumar -->

3. **Team Assignment** - Members will be assigned to respective projects

### 📚 n8n Resources:

- 📖 [Official Documentation](https://docs.n8n.io/)
- 🔄 [Flow Logic Guide](https://docs.n8n.io/flow-logic/)
- 🤖 [AI Integration](https://n8n.io/ai/)
- 🎥 [YouTube Channel](https://www.youtube.com/@n8n-io)
- 🎬 [Tutorial Video](https://youtu.be/lW5xEm7iSXk)

---

## 🏆 Hackathon Guidelines

### 📝 Submission Requirements:
- Make a 8-10 video recording showing up your solution
- The solution must use approved tools (Portkey, n8n)
- Must follow data security guidelines strictly (e.g. protect PII)
<!--- Document your solution approach
- Include demo/presentation materials-->

### ⏰ Important Dates:
- **Competition Period:** September 1-19
- **Submission Deadline:** September 19
- **Demo Presentations:** September 24

---

## 🆘 Support Team

Need help? Reach out to our support team:

👨‍💻 **Support Contacts:**  
@Rahul Miragi | @Jacques Sa | @Akshay Dharerao | @Lalitkumar | @Rahul Sachdeva

---

# 📊 Data Sources & Connection Guidelines

### ⚠️ CRITICAL: Data Security Policy

> **🔒 MANDATORY:** Only use **MOCK DATA** for this hackathon. Using real or production data, without proper masking or concealment of any personally identifiable information, is **STRICTLY PROHIBITED** and may result in disqualification.

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
<div align="center">

**Good luck with the hackathon! 🎉**

*Happy coding and building amazing solutions!* 

</div> 
