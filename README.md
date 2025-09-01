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



**Device Usage**<br>
**Computer users** → More churn than phone users.<br>
**More registered devices** → **Higher** churn risk.<br>
**Interpretation:**<br>
Customers who primarily use computers to access the platform exhibit a higher churn rate compared to those using mobile devices. This may suggest that mobile-first users are more engaged or find the platform more accessible.<br>
**Buisness Implication:**<br>
Enhance the desktop experience with interactive elements, personalized recommendations, or streamlined navigation <br>
Encourage a shift to mobile by promoting app-exclusive features, smoother UX, or targeted onboarding campaigns <br>

**Tenure & Loyalty**<br>
**0–6 months** → 32% churn (highest risk).<br>
**1 year** → 10% <br>
**2 years** → 6% <br>
**Greater than 2 years** → 0% churn <br>
**Interpretation:**<br>
The churn rate decresses with increased tenure range.<br>
**Buisness Implication**<br>
Retention improves significantly with tenure → focus on onboarding.<br>

**Order Behavior**<br>
**Short reorder cycle** → Higher retention.<br>
**Long gaps between orders** → Increased churn risk.<br>
**Higher order amount hike** → Lower churn (customers willing to spend more stay longer).<br>
**Interpretation:**<br>
If the customer doesn't reorders within the last 10 days of the order the customer is like to churn.<br>
**Buisness Implication:**<br>
Target customers with long reorder gaps using personalized reactivation campaigns or timely nudges<br>
Reward high spenders with loyalty perks or exclusive offers to reinforce retention<br>
Monitor order cycles to predict churn early and intervene with tailored messaging<br>

      
**City Tier**<br>
**Churn rises** from **Tier-1 → Tier-3** cities<br>.
**Interpretation:**<br>
Indicates weaker brand trust & service issues in smaller cities.<br>
**Buisness Implication:**<br>
Strengthen brand presence in Tier-2 and Tier-3 cities through localized marketing and community engagement<br>
Improve service reliability and delivery speed in smaller cities<br>
Offer region-specific incentives or onboarding support to build trust and reduce churn<br>

       
**Product Category**<br>
**Grocery**→ Lowest churn (5%) <br>
**Electronics/High-value** items → Higher churn.<br>
**Interpretation:** <br>
Grocery purchases are frequent, habitual, and need-based, fostering consistent engagement.<br>
Electronics involve higher stakes—price sensitivity, delivery expectations, and post-purchase support—making customers more likely to churn if expectations aren’t met.<br>
**Buisness Implication**<br>
For electronics, focus on customer assurance—clear return policies, reliable delivery, and post-sale support.<br>



**Satisfaction & Support**<br>
**Churn increases** with **Satisfaction Score**  (possible gap between survey vs. actual experience).<br>
**Interpretation:**<br>
Customers give high ratings during surveys but still churn due to unresolved issues, inconsistent support, or post-survey dissatisfaction<br>
**Buisness Implication:** <br>
Re-evaluate the survey design: Are we asking the right questions at the right time?<br>
Cross-check satisfaction scores with support ticket resolution, response time, and repeat complaints.<br>
Introduce experience audits or follow-up interviews to uncover hidden pain points.<br>


**Final Insight**: <br> 
**Smaller cities (Tier-2/3)** face delivery and support challenges → **weaker brand trust** <br>
**High-value products carry higher expectations** → **churn spikes when service falters** <br>
**COD & E-wallet users show less commitment** → churn linked to **payment friction and trust** <br>
**High satisfaction scores don’t guarantee retention** → signals a gap between perceived and actual experience <br>

**To reduce churn, the business must  focus on:** <br>
**Experience consistency** across **regions** and **categories** <br>
**Trust-building** mechanisms in **payment** and **delivery** <br>
**Behavioral signals** that **reveal dissatisfaction** before surveys do <br>
**Segmented retention** strategies **tailored** to **customer profiles** and **usage patterns** <br>

