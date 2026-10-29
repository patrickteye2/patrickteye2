# Patrick Rich Teye

**Data & Research Analyst | Private Credit + Investment Analytics**

I work where data analysis meets credit and investment decisions. My focus is owning the full analytical chain, from raw data to the model to the output an investment committee can act on. The technical work and the finance context sit in the same hands, which means fewer handoffs and analysis that is built for decision-makers from the start.

I currently lead research and analysis for the Origen Private Debt Fund at Ashfield Investment Managers, one of Ghana's first private debt vehicles. My background is in Actuarial Science, which gives me a quantitative grounding that most analysts from a purely technical route do not carry.

---

## What I work on

My direction is to become an AI builder in the credit and investment space, not a generic machine learning engineer. In practice, that means credit scoring and risk models, automated reporting pipelines, and document extraction systems that turn unstructured deal material into something structured and searchable. The common thread is applying code and data to real investment problems rather than toy datasets.

---

## Technical stack

**Languages and analysis:** Python (pandas, scikit-learn, numpy), SQL, R, SPSS

**Data and BI:** Power BI, Tableau, advanced Excel

**Automation:** Power Automate, UiPath

**Web:** React.js, TypeScript

**Ways of working:** Git, Jupyter, Agile / Scrum (Certified Scrum Master)

---

## Selected projects

### Credit Score Model
**Repo:** [credit_score_model](https://github.com/patrickteye2/credit_score_model)

A credit default model built on a public credit risk dataset of around 32,500 loans. The project is designed as a portfolio piece, so notebooks are committed with outputs saved and a reader does not have to run the code to see the results.

A few deliberate decisions shape it:

- We tune and report on recall for the default class rather than accuracy. Around 22% of these loans default, so a model that predicts "no default" for everyone would score 78% accuracy and still be useless.
- We separate the lender's own risk pricing (loan grade, interest rate) from borrower characteristics, and train a borrower-only model alongside the full model so the performance gap between them can be reported honestly.
- We fix two data issues before modelling: a duplicated income ratio that would split feature importance, and target leakage in a sector risk feature derived before the train/test split. The rule we follow is simple: never derive a feature from the target before splitting.

Workflow covers EDA, feature engineering, model training with grid search, and a scorecard stage that converts probabilities into approve, review, and decline bands.

---

## Experience

**Ashfield Investment Managers** — Data & Research Analyst, Origen Private Debt Fund  
Research and credit analysis across agribusiness, healthcare, renewable energy, and infrastructure. Credit scoring, financial modelling, automated reporting in Python, SQL, and Power BI, and investment memos for the committee. I also run daily scrum as Scrum Master.

**Right to Information Commission** — Data Analyst (to August 2024)  
Built data models and interactive dashboards in Power BI and Tableau, designed and analysed national-scale surveys, and set up monitoring and evaluation frameworks in SPSS and R.

Earlier roles span government analytics (Ghana Ports Authority, Ghana Statistical Service), the food industry, and technology firms.

---

## Education and certification

- MSc, Data Analytics — Nexford University
- BSc, Actuarial Science — KNUST
- Certified Scrum Master
- Working towards CFI Financial Modeling & Valuation Analyst (FMVA)

---

## Let's connect

I am interested in work at the intersection of credit, investment, and energy, and I am open to remote opportunities.

- **GitHub:** [github.com/patrickteye2](https://github.com/patrickteye2)
- **Email:** patrick96rich@gmail.com
