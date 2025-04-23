# Financial_Inclusion_Nigeria
Understanding financial inclusion metrics and potentials through data exploration.

### In this project, the main work will be about consolidating the columns in the dataset into a more compact structure. We will then feed this compact structure into the function that'll give us different visualizations to explore the data and extract the stories hidden in the data. I have defined a list of columns that we need to create based on the data at hand. The list is as follows:

Here is the detailed description for each column based on the provided example:

---

### **1. state**
**Description**: Indicates the state or territory where the individual resides.  
**Purpose**: This column helps analyze geographic disparities in financial inclusion and economic opportunities across different regions.

---

### **2. bank_account_ownership**
**Description**: Indicates whether an individual owns a formal bank account (e.g., savings, checking) and the type of financial institution they use (e.g., commercial bank, microfinance institution).  
**Purpose**: This column helps assess financial inclusion by identifying individuals with access to formal banking services.

---

### **3. financial_inclusion_metrics**
**Description**: A composite score or indicator that measures various aspects of financial inclusion, such as access to credit, savings, and digital payment systems.  
**Purpose**: This column provides a quantitative measure of an individual's overall financial inclusion status.

---

### **4. demographic_factors**
**Description**: Captures demographic characteristics of individuals, such as age, gender, education level, employment status, and household size.  
**Purpose**: This column helps identify demographic groups that are more or less likely to be financially included or economically empowered.

---

### **5. savings_behavior**
**Description**: Describes how individuals save money, including formal methods (e.g., bank accounts) and informal methods (e.g., savings groups, keeping cash at home).  
**Purpose**: This column helps understand saving habits and their relationship with financial inclusion and resilience.

---

### **6. borrowing_behavior**
**Description**: Indicates how individuals borrow money, including formal sources (e.g., banks, microfinance institutions) and informal sources (e.g., family, friends, moneylenders).  
**Purpose**: This column helps analyze borrowing patterns and their impact on financial inclusion and economic opportunities.

---

### **7. digital_payment_adoption**
**Description**: Indicates whether an individual uses digital payment systems (e.g., mobile money, e-wallets, online banking) for transactions.  
**Purpose**: This column helps assess the adoption of digital financial services and its role in promoting financial inclusion.

---

### **8. access_to_electricity**
**Description**: Indicates whether an individual has reliable access to electricity, which is a critical enabler for using digital financial services and other infrastructure.  
**Purpose**: This column helps identify barriers to financial inclusion caused by lack of basic infrastructure.

---

### **9. internet_access**
**Description**: Indicates whether an individual has access to the internet, which is essential for using online banking, digital payments, and other financial services.  
**Purpose**: This column helps evaluate the role of internet access in driving financial inclusion and economic opportunities.

---

### **10. mobile_phone_usage**
**Description**: Indicates whether an individual uses a mobile phone and the extent of its usage (e.g., feature phone vs. smartphone).  
**Purpose**: This column helps assess the role of mobile phones in enabling access to financial services, particularly mobile money and digital payments.

---

### **11. credit_access**
**Description**: Indicates whether an individual has access to formal credit services from banks, microfinance institutions, or other lenders.  
**Purpose**: This column helps evaluate the availability of credit as a tool for financial inclusion and economic empowerment.

---

### **12. small_business_ownership**
**Description**: Indicates whether an individual owns or operates a small business.  
**Purpose**: This column helps assess the relationship between entrepreneurship and financial inclusion, as well as the role of small businesses in economic development.

---

### **13. entrepreneurship**
**Description**: Captures indicators of entrepreneurial activity, such as starting or managing a business, involvement in income-generating activities, or participation in innovation ecosystems.  
**Purpose**: This column helps identify individuals who are engaged in entrepreneurial activities and their access to financial resources.

---

These descriptions provide a clear understanding of each column's purpose and how it contributes to analyzing financial inclusion and economic opportunities.




Questions we want to answer:

1) What is the distribution of bank account ownership like across different states / territories? Are there any correlations with education level, urbanization rates, etc.?
2) Are there any significant rural - urban divides in terms of financial inclusion?
3) Are there any interesting correlations between labor force demographics and financial inclusion across states / territories?
4) What relationship exists between financial inclusion metrics (account ownership, saving and borrowing behavior, credit access, digital payment adoption, mobile money usage, etc.)
5) Which demographic factors (e.g. age, gender, education, etc.) are the strongest predictors of financial inclusion? (TBD: not sure how much individual-level data exists to answer this.)
6) How do savings and borrowing behaviors differ across income groups, education levels, and states / territories? Across communities?
7) Are there any correlations between financial inclusion / economic opportunity and urban trends (e.g. digital payment incentives, gentrification)?
8) Are there any interesting relationships between infrastructure (e.g. access to electricity, internet access, use of mobile phones) and financial inclusion?
9) What relationships exist between access to credit, credit usage, etc. and small business ownership and entrepreneurship?
