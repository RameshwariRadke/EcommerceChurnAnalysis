# EcommerceChurnAnalysis

# Objective:
The objective of this project is to analyze the customer behavior and identify patterns that lead to churn in an ecommerce setting. The goal is to uncover actionable insights that help improve retention, personalize engagement, and reduce attrition.

## Tools:
**Python(numpy,pandas,matplotlib,seaborn):** for EDA and visual story telling
**Power BI:** for Dashboard showing churn analysis trends by citytiers,payment modes,shopping category,numberOfDevices Registered, customer behaviour insights etc.

# EDA (Exploratory Data Analysis)
Read the dataset using python(pandas) dealed with the null values,outliers and  created new coulmns of tenure range,churn_status ,deliverydistance etc for analysis.
Performed EDA and took out important insights from the data using Univariate,Bivariate analysis.

**Key Questions Explored**

1. What is the churn rate distribution among different payment methods used by Customers
2. How does the churn rate vary based on the preferred login device of customer
3. Is there Correlation between Churn and Tenure
4. What is the churn rate pattern across different city tiers
5. How does the number of devices used by customers relate to their churn rate
6. What is the impact of the warehouse-to-home delivery option on the churn rate
7. Is there a relationship between customer satisfaction scores and churn rates
8. How does the churn rate differ for customers based on their preferred order categories

# Insights from the Data

**Payment Mode**<br>
**COD & E-wallet** users → **Highest** churn (trust & delivery concerns).
**Debit/Credit** cards → **Lower** churn (more reliable segment).
**Interpretation:**
Customers using Cash on Delivery showed a slightly higher churn rate compared to those using UPI or Credit Cards, possibly due to lower engagement or trust in the platform.
**Buisness Implication:**
Build trust around COD: Offer real-time delivery tracking, proactive communication, and easy return options.
For E-wallet users, ensure seamless refund workflows and visible transaction histories.
Encourage a shift toward card-based payments through targeted incentives (e.g., cashback, loyalty points).



**Device Usage**
**Computer users** → More churn than phone users.
**More registered devices** → **Higher** churn risk.
**Interpretation:**
Customers who primarily use computers to access the platform exhibit a higher churn rate compared to those using mobile devices. This may suggest that mobile-first users are more engaged or find the platform more accessible.
**Buisness Implication:**
Enhance the desktop experience with interactive elements, personalized recommendations, or streamlined navigation
Encourage a shift to mobile by promoting app-exclusive features, smoother UX, or targeted onboarding campaigns

**Tenure & Loyalty**
**0–6 months** → 32% churn (highest risk).
**1 year** → 10% 
**2 years** → 6% 
**Greater than 2 years** → 0% churn 
**Interpretation:**
The churn rate decresses with increased tenure range.
**Buisness Implication**
Retention improves significantly with tenure → focus on onboarding.

**Order Behavior**
**Short reorder cycle** → Higher retention.
**Long gaps between orders** → Increased churn risk.
**Higher order amount hike** → Lower churn (customers willing to spend more stay longer).
**Interpretation:**
If the customer doesn't reorders within the last 10 days of the order the customer is like to churn.
**Buisness Implication:**
Target customers with long reorder gaps using personalized reactivation campaigns or timely nudges
Reward high spenders with loyalty perks or exclusive offers to reinforce retention
Monitor order cycles to predict churn early and intervene with tailored messaging

      
**City Tier**
**Churn rises** from **Tier-1 → Tier-3** cities.
**Interpretation:**
Indicates weaker brand trust & service issues in smaller cities.
**Buisness Implication:**
Strengthen brand presence in Tier-2 and Tier-3 cities through localized marketing and community engagement
Improve service reliability and delivery speed in smaller cities
Offer region-specific incentives or onboarding support to build trust and reduce churn

       
**Product Category**
**Grocery**→ Lowest churn (5%) 
**Electronics/High-value** items → Higher churn.
**Interpretation:** 
Grocery purchases are frequent, habitual, and need-based, fostering consistent engagement.
Electronics involve higher stakes—price sensitivity, delivery expectations, and post-purchase support—making customers more likely to churn if expectations aren’t met.
**Buisness Implication**
For electronics, focus on customer assurance—clear return policies, reliable delivery, and post-sale support.



**Satisfaction & Support**
**Churn increases** with **Satisfaction Score**  (possible gap between survey vs. actual experience).
**Interpretation:**
Customers give high ratings during surveys but still churn due to unresolved issues, inconsistent support, or post-survey dissatisfaction
**Buisness Implication:**
Re-evaluate the survey design: Are we asking the right questions at the right time?
Cross-check satisfaction scores with support ticket resolution, response time, and repeat complaints.
Introduce experience audits or follow-up interviews to uncover hidden pain points.


**Final Insight**: 
**Smaller cities (Tier-2/3)** face delivery and support challenges → **weaker brand trust**
**High-value products carry higher expectations** → **churn spikes when service falters**
**COD & E-wallet users show less commitment** → churn linked to **payment friction and trust**
**High satisfaction scores don’t guarantee retention** → signals a gap between perceived and actual experience

**To reduce churn, the business must  focus on:**
**Experience consistency** across **regions** and **categories**
**Trust-building** mechanisms in **payment** and **delivery**
**Behavioral signals** that **reveal dissatisfaction** before surveys do
**Segmented retention** strategies **tailored** to **customer profiles** and **usage patterns**

