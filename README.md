# UNSDG5_DiscriminationAnalysis

The global indicator framework for Sustainable Development Goals (SDGs) consists of over 230 specific indicators and targets associated with the 17 SDGs. It provides a standardized system for tracking and assessing progress toward the SDGs worldwide, promoting data collection, reporting, and global cooperation. It helps measure and monitor social, economic, and environmental aspects of sustainable development and ensures that no one is left behind. The framework is periodically reviewed and adapted to reflect evolving priorities and challenges in achieving the SDGs.

# GOAL 5: Achieve gender equality and empower all women and girls

Sustainable Development Goal 5 (SDG 5) is one of the 17 Sustainable Development Goals adopted by the United Nations in 2015. SDG 5 focuses on achieving gender equality and empowering all women and girls. Its key objectives include:

- **Ending Gender Discrimination:** SDG 5 aims to eliminate all forms of discrimination, violence, and harmful practices against women and girls, both in public and private spheres.
- **Equal Participation:** It seeks to ensure women's full and effective participation in all levels of decision-making in political, economic, and public life.
- **Equal Rights and Opportunities:** SDG 5 calls for equal rights and opportunities for women in education, employment, and leadership positions.
- **Reproductive Health:** It addresses access to sexual and reproductive health services, including family planning and maternal healthcare.
- **Unpaid Care Work:** SDG 5 recognizes and values unpaid care and domestic work and aims to reduce the burden on women.
- **Legal Frameworks:** It promotes the existence of legal frameworks and policies that promote gender equality and protect women's rights.
- **Data Collection:** SDG 5 emphasizes the need for gender-disaggregated data to monitor progress and inform policies.

SDG 5 plays a crucial role in advancing gender equality, empowering women and girls, and contributing to broader sustainable development objectives. It reflects a global commitment to creating a more equitable and inclusive world where gender-based discrimination and violence are eliminated, and all individuals have equal opportunities and rights, regardless of their gender.

# Aim of this Analysis

To analyse Target 5.1 and 5.2 using Python.
The following dependencies were sufficient for the analysis:
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from tabulate import tabulate
import matplotlib.cm as cm
import plotly.graph_objects as go
import pycountry
%matplotlib inline
```
# Datasets Used
[Refer to the Folder](datasets)

# TARGET 5.1

## End all forms of discrimination against all women and girls everywhere

5.1.1 Whether or not legal frameworks are in place to promote, enforce and monitor equality and non-discrimination on the basis of sex

- 0.c. Indicator (SDG_INDICATOR) Indicator 5.1.1: Whether or not legal frameworks are in place to promote, enforce and monitor equality and non‑discrimination on the basis of sex

- 0.d. Series (SDG_SERIES_DESCR) SG_LGL_GENEQLFP, Legal frameworks that promote, enforce and monitor gender equality (percentage of achievement, 0 - 100) -- Area 1: overarching legal frameworks and public life

- SG_LGL_GENEQVAW, Legal frameworks that promote, enforce and monitor gender equality (percentage of achievement, 0 - 100) -- Area 2: violence against women

- SG_LGL_GENEQEMP, Legal frameworks that promote, enforce and monitor gender equality (percentage of achievement, 0 - 100) -- Area 3: employment and economic benefits

- SG_LGL_GENEQMAR, Legal frameworks that promote, enforce and monitor gender equality (percentage of achievement, 0 - 100) -- Area 4: marriage and family

## Analysis
The dataset waa divided into two groups for separately analysing targets 5.1 and 5.2. 
For Target 1, the analysis was conducted using Python and was based on the following categories:
1. India's performance in the 4 areas
2. Comparison of India with her Neighbouring Countries
3. Asian subregion performance comparisons for 2 years' data
4. Continent-wise performance
5. Countries with Bdest and Worst Performances

**The analysis, graphs and inferences can be found in the ```ipynb``` file itself.**

The dataset downloaded from the official site of UNSDG was combined with the country code dataset to help display the informtation in the form of maps.

## Discussion

The results and discussion were presented with the help of an Infographic designed using *CANVA*

![5 1 final (1)_page-0001](https://github.com/AsmitaMondal/UNSDG5_DiscriminationAnalysis/assets/108891810/8174ebc0-675f-4cfe-9b8b-9e695dd8d38f)

# Target 5.2

## Eliminate all forms of violence against all women and girls in the public and private spheres, including trafficking and sexual and other types of exploitation

- 0.c. Indicator (SDG_INDICATOR) Indicator 5.2.1: Proportion of ever-partnered women and girls aged 15 years and older subjected to physical, sexual or psychological violence by a current or former intimate partner in the previous 12 months, by form of violence and by age
  
- 0.d. Series (SDG_SERIES_DESCR) Proportion of ever-partnered women and girls subjected to physical and/or sexual violence by a current or former intimate partner in the previous 12 months, by age (%) VC_VAW_MARR

## Analysis

The dataset was further divided into two to analyse the violence rates based on two different age groups:
1. 15+
2. 15-49

The analysis was conducted based on the following categorizations:
1. Violence Rates in the age groups
2. India's analysis
3. Comparison of India with her Neighbours
4. Continent-wise analysis
5. Top and Bottom Countries with respect to Violence Rates

## Discussion

The results and discussion were presented with the help of an Infographic designed using *CANVA*

![5 2 final (1)_page-0001](https://github.com/AsmitaMondal/UNSDG5_DiscriminationAnalysis/assets/108891810/b6038f94-bc09-467e-85f4-83198b17dc92)

# Important Statistical Findings that Align with the Analysis

- The lack of a common definition of technology-facilitated violence against women and girls impacts on the lack of comparable data at a global level. One in 10 women in the European Union has experienced cyber-harassment since the age of 15, including having received unwanted and/or offensive sexually explicit emails or SMS messages, or offensive and/or inappropriate advances on social networking sites. In the Arab States, a regional study found that 60 per cent of women internet users in the region had been exposed to online violence in the past year. In Uganda, in 2021, about half of women (49 per cent) reported being involved in online harassment at some point in their lifetime. According to a 2016 survey by the Korean National Human Rights Commission, 85 per cent of women experienced hate speech online.

- Climate change and slow environmental degradation exacerbate the risks of violence. Nepal witnessed an increase in trafficking from an estimated 3,000–5,000 annually in 1990 to 12,000–20,000 per year after the 2015 earthquake.Following Hurricane Katrina in 2005, the rate of rape among women displaced to trailer parks rose 53.6 times the baseline rate in Mississippi, USA, for that year.

- Most violence against women is perpetrated by current or former husbands or intimate partners. More than 640 million or 26 per cent of women aged 15 and older have been subjected to intimate partner violence. Of those who have been in a relationship, almost one in four adolescent girls aged 15–19 (24 per cent) has experienced physical and/or sexual violence from an intimate partner or husband. Sixteen per cent of young women aged 15 to 24 experienced this violence in the past 12 months.

- The COVID-19 pandemic has intensified violence against women and girls. In 2021, since the pandemic began, 45 per cent of women reported that they or a woman they know has experienced a form of VAWG. Seven in 10 women said they think that verbal or physical abuse by a partner has become more common. And six in 10 felt that sexual harassment in public spaces has worsened.

- At least 162 countries have passed laws on domestic violence, and 147 have laws on sexual harassment in the workplace. However, even when laws exist, this does not mean they are always compliant with international standards and recommendations or are implemented and enforced.

# CONCLUSION

It is disappointing to see that something that ought to have been obvious now needs laws to safeguard it. The core values of the United Nations are gender equality. The United Nations Charter, which was adopted by world leaders in 1945, states that "equal rights of men and women" is a fundamental principle and that it is the responsibility of all States to protect and advance women's human rights. Equality between men and women has historically been one of the most fundamental human rights guarantees. Women would not have been able to exercise something as fundamental as the right to vote if there were no women's rights. Additionally, it is a game-changer for female victims of gender discrimination. Women's rights are crucial because they provide them the chance to survive.

Through this analysis, I was able to pinpoint the social, cultural, and legal flaws that contribute to gender inequality and violence. It also focuses on instances of development and achievement in countries that have enacted extensive legal reforms, awareness campaigns, and gender equality programmes.
