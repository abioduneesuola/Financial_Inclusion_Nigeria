# Financial_Inclusion_Nigeria
Understanding financial inclusion metrics and potentials through data exploration.

### In this project, the main work will be about consolidating the columns in the dataset into a more compact structure. We will then feed this compact structure into the function that'll give us different visualizations to explore the data and extract the stories hidden in the data. I have defined a list of columns that we need to create based on the data at hand. The list is as follows:

#### **1. Distribution of Bank Account Ownership**
**Question**:  
What is the distribution of bank account ownership (`bank_account_ownership`) across different states/territories? Are there any significant correlations with demographic factors (`demographic_factors`) or access to infrastructure (e.g., `access_to_electricity`, `internet_access`)?

---

#### **2. Infrastructure and Financial Inclusion**
**Question**:  
How does access to infrastructure (e.g., `access_to_electricity`, `internet_access`, `mobile_phone_usage`) correlate with financial inclusion metrics such as bank account ownership, digital payment adoption, and credit access?

---

#### **3. Barriers to Financial Inclusion**
**Question**:  
What are the primary barriers to financial inclusion for individuals who do not own a bank account (`bank_account_ownership = No`)? Are these barriers related to lack of infrastructure (e.g., `access_to_electricity`, `internet_access`) or other factors?

---

#### **4. Savings Behavior Across Groups**
**Question**:  
How do savings behaviors (`savings_behavior`) vary across demographic groups (`demographic_factors`) and geographic regions (`state`, `region`)? Are there observable patterns among different income levels or education levels?

---

#### **5. Borrowing Behavior and Credit Access**
**Question**:  
What is the relationship between borrowing behavior (`borrowing_behavior`) and access to credit (`credit_access`)? Do individuals with limited credit access rely on informal borrowing methods (e.g., family/friends, moneylenders)?

---

#### **6. Digital Payment Adoption Trends**
**Question**:  
What trends can be observed in digital payment adoption (`digital_payment_adoption`) across different demographic groups and geographic regions? Are there specific factors (e.g., `internet_access`, `mobile_phone_usage`) that drive or hinder adoption?

---

#### **7. Entrepreneurship and Small Business Ownership**
**Question**:  
How does entrepreneurship (`entrepreneurship`) correlate with small business ownership (`small_business_ownership`) and access to credit (`credit_access`)? Are there disparities based on demographic factors or geographic location?

---

#### **8. Financial Resilience and Economic Opportunities**
**Question**:  
How do financial resilience metrics (e.g., `finhealth_resilience`, `finneeds_resilience`) relate to broader economic opportunities, such as entrepreneurship (`entrepreneurship`) and small business ownership (`small_business_ownership`)?

---

#### **9. Correlations Between Financial Inclusion Metrics**
**Question**:  
What relationships exist between various financial inclusion metrics, such as bank account ownership (`bank_account_ownership`), savings behavior (`savings_behavior`), borrowing behavior (`borrowing_behavior`), and digital payment adoption (`digital_payment_adoption`)?

---

#### **10. Role of Demographic Factors**
**Question**:  
Which demographic factors (`demographic_factors`) are the strongest predictors of financial inclusion, as measured by `bank_account_ownership` and `financial_inclusion_metrics`? How do age, gender, education level, and employment status influence financial inclusion?

---






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
