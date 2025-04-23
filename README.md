# Financial_Inclusion_Nigeria
Understanding financial inclusion metrics and potentials through data exploration.

### In this project, the main work will be about consolidating the columns in the dataset into a more compact structure. We will then feed this compact structure into the function that'll give us different visualizations to explore the data and extract the stories hidden in the data. I have defined a list of columns that we need to create based on the data at hand. The list is as follows:


### **1. `bank_account_ownership`**
- **Description**: Indicates whether an individual owns a formal bank account (e.g., savings, checking) and the type of financial institution they use (e.g., commercial bank, microfinance institution).
- **Purpose**: This column helps assess financial inclusion by identifying individuals with access to formal banking services.

---

### **2. `urban_rural`**
- **Description**: Categorizes individuals based on whether they reside in urban or rural areas.
- **Purpose**: This column provides geographic context for understanding disparities in access to financial services, infrastructure, and opportunities between urban and rural populations.

---

### **3. `financial_inclusion_metrics`**
- **Description**: Aggregates multiple indicators of financial inclusion, such as ownership of bank accounts, mobile money usage, and access to credit.
- **Purpose**: This composite metric offers a holistic view of an individual's engagement with formal and informal financial systems.

---

### **4. `demographic_factors`**
- **Description**: Combines demographic attributes such as age, gender, education level, and marital status into a single representation.
- **Purpose**: These factors are critical for analyzing how demographic characteristics influence financial behavior and inclusion.

---

### **5. `savings_behavior`**
- **Description**: Captures how individuals save money, including methods (e.g., at home, in banks, via mobile wallets) and purposes (e.g., emergencies, education, business).
- **Purpose**: This column highlights saving habits and preferences, which are key to understanding financial resilience and planning.

---

### **6. `borrowing_behavior`**
- **Description**: Describes borrowing patterns, including sources of loans (e.g., family, banks, microfinance institutions) and reasons for borrowing (e.g., emergencies, business expansion).
- **Purpose**: This column provides insights into debt management and access to credit, which are essential for assessing financial vulnerability and entrepreneurial activities.

---

### **7. `digital_payment_adoption`**
- **Description**: Indicates the extent to which individuals use digital payment methods, such as mobile money, e-wallets, or online banking.
- **Purpose**: This column measures adoption of modern financial technologies, which is a strong indicator of financial inclusion and economic participation.

---

### **8. `access_to_electricity`**
- **Description**: Identifies whether individuals have reliable access to electricity, which is a prerequisite for using digital devices and financial services.
- **Purpose**: This column highlights infrastructure challenges that may hinder access to financial tools and services, particularly in rural areas.

---

### **9. `internet_access`**
- **Description**: Indicates whether individuals have access to the internet, either through smartphones, computers, or other devices.
- **Purpose**: Internet access is crucial for digital financial inclusion, enabling activities like online banking, mobile payments, and e-commerce.

---

### **10. `mobile_phone_usage`**
- **Description**: Describes how individuals use mobile phones, including ownership, type of phone (e.g., smartphone, feature phone), and comfort with apps.
- **Purpose**: Mobile phones are often a gateway to financial services, especially in regions where traditional banking is limited.

---

### **11. `credit_access`**
- **Description**: Assesses access to credit, including borrowing history, sources of credit, and repayment behavior.
- **Purpose**: This column highlights barriers to accessing credit and identifies opportunities to expand financial inclusion for underserved populations.

---

### **12. `small_business_ownership`**
- **Description**: Indicates whether individuals own or operate small businesses, including ownership of business equipment, control over assets, and proximity to markets.
- **Purpose**: This column evaluates entrepreneurial activity and identifies individuals who may benefit from targeted financial products and services.

---

### **13. `entrepreneurship`**
- **Description**: Provides a comprehensive view of entrepreneurial activities, including income-generating activities, sectors of operation, and employment of others.
- **Purpose**: This column helps identify individuals engaged in entrepreneurial ventures and assesses their needs for financial support and resources.

---

### Summary
These columns collectively provide a detailed understanding of financial inclusion, economic behavior, and access to resources. While `urban_rural` has been temporarily skipped, it can be revisited later to incorporate geographic insights into the analysis. Each column contributes to a broader narrative about how individuals interact with financial systems and what factors influence their economic opportunities.







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
