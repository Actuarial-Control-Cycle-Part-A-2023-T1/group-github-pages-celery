[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/elzutNYu)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10759245)
# Actuarial Theory and Practice A @ UNSW

_"Tell me and I forget. Teach me and I remember. Involve me and I learn" - Benjamin Franklin_

---

### Congrats on completing the [2023 SOA Research Challenge](https://www.soa.org/research/opportunities/2023-student-research-case-study-challenge/)!

>Now it's time to build your own website to showcase your work.  
>To create a website on GitHub Pages to showcase your work is very easy.

This is written in markdown language. 
>
* Click [link](https://classroom.github.com/a/elzutNYu) to accept your group assignment.


#### Follow the [guide doc](Doc1.pdf) to submit your work. 
---
>Be creative! Feel free to link to embed your [data](hazard-event-data.csv), [code](sample-data-clean.ipynb), [image](unsw.png) here

More information on GitHub Pages can be found [here](https://pages.github.com/)
![](Actuarial.gif)

# Relocation Social Insurance Program - Storslysia Case Study
CELery - University of New South Wales

Lenny Han, Alan Wang, Sharon Zhou, Emily Huynh, Claudia Shen

# Executive Summary
With climate-related catastrophes increasing over time in Storslysia, its residents face the imminent threat of displacement, and the economy faces a decline due to the costs of supporting impacted individuals. The team has been tasked with alleviating the adverse financial impacts of climate change by designing and implementing a long-term social insurance program. This report will outline the program’s design and the method for pricing under two climate scenarios.

The final program to be utilised offers two solutions to minimise cost and maximise results. The first is to incentivize residents in high-risk areas to voluntarily relocate which will mitigate larger costs later, and the other is to help impacted individuals who are permanently displaced because of a catastrophe. To incentivise relocation, the program offers a 20% above-market price buy-back scheme to households considered to be high-risk; this is capped at 2000 houses per year to avoid excessive claims. For those involuntarily displaced, a lumpsum payment will be distributed, calculated based on the property damage value per household, as well as income support and accommodation expenses for those applicable. The values we have calculated are a result of strenuous testing and comparisons to obtain an optimal solution.

Our proposed program restricts the cost associated with relocation (voluntary or climate-induced) to 10% of Storslysia’s GDP every year. This is significantly lower than without the program and shields the economy from negative financial ramifications. We recommend that both streams of the program be run simultaneously as promoting voluntary relocation will greatly reduce larger costs down the line resulting from forced displacement.

# Objectives
## Key metrics

# Program Design
The proposed program provides financial support for households in high-risk areas to voluntarily relocate or to recover after being affected by a catastrophic event. Households are encouraged to voluntarily relocate through a buyback scheme which provides financial assistance to encourage residents in vulnerable areas to voluntarily relocate to a lower-risk area, therefore minimising costs from the involuntary scheme. Properties bought back will become government-owned and deemed unhabitable after the buyback.

## Voluntary Scheme
### Eligiblity to claim
Citizens over 18 years old are eligible to apply for the buyback scheme if they are an owner of a property in a high-risk region. Only one owner per property can apply. Applications are submitted every two years and reviewed on a case-by-case basis and the top 2000 properties most at risk of property damage from a catastrophic event are selected. Successful applicants must relocate to a low-risk region. The number of eligible properties is determined by ensuring that the objectives are met and adjusted according to the target voluntary relocation proportions in Table 2.

### Coverage
**Home buyback** – Claimants receive a lump sum valued at 20% above the market price of the property they currently own. The additional 20% of the lump sum above the market price serves as a financial incentive for households in high-risk areas to relocate to lower areas. Furthermore, this ensures that they can afford homes in lower-risk areas as the market prices in such areas are expected to be more costly. It also accounts for the temporary loss of income due to frictional unemployment.

**Moving costs** – Claimants can reimburse up to a maximum of Ꝕ1000 in moving costs incurred.
If a household has multiple owners, a single payment is made to the applicant and the distribution of funds is up to their discretion.

### Other features and requirements
**Application review** – Properties eligible for the buyback scheme will be selected based on factors such as whether the property had been damaged due to a catastrophic event in the past and the likelihood of a severe catastrophic event in the future. Furthermore, the applicant must have owned a home in the vulnerable region for a sufficient length of time.
**Low/High-risk regions** – Low-risk regions include regions 1 and 3. High- risk regions include regions 2, 4 and 5. These will be reviewed every year. The risk rating of regions is determined through past experience, including the frequency of catastrophic events and total property damage incurred.

### Additional incentives
**Government land acquisition** – To support the buyback scheme, Storslysia’s government will acquire land in low-risk areas and begin development. Suitable areas will be discussed in community consultations with relevant stakeholders. According to King et al., some households may be resistant to voluntarily relocating due to longevity of residence in the community, reduced incomes of retirees and lack of time available to restart elsewhere. Successful applicants can choose to move to any lower-risk region or relocate to a property on land acquired by the government. The latter option provides an opportunity for high-risk regions to maintain a sense of community after relocating and reduce the burden of searching for a home.

## Involuntary Scheme
### Eligibility to claim
Citizens over 18 years old are eligible to apply if their property was damaged or they were forced to cease work due to a catastrophic event. The address of the covered property must be the claimant’s main residence address.

### Coverage
**Home and property damage** – Affected households are entitled to small claims lower than Ꝕ500, while the reimbursement of additional costs will require manual review. Triaging claims aims to minimise costs associated with claims investigation. Home and property damage claims include the replacement of household items and housing repairs.
**Loss of income payments** – If affected residents are temporarily unable to work after the catastrophic event, they are eligible to receive 75% of their income for 8 weeks, capped at Storslysia’s median income.
**Accommodation expenses** – If the property becomes uninhabitable following the catastrophic event, residents are eligible to be compensated for accommodation expenses for 2 weeks.
If the property at risk was rented to a tenant, the landlord is entitled to home and property damage coverage while the tenant may receive loss of income and accommodation expenses if eligible.

### Implementation timeline
The timeline in Figure 1 details timeframes for the implementation of the program. There are three cycles of the scheme each being two years in length. The program aims to prioritise individuals most vulnerable to natural disasters within the community and scale to cover proportionally more households over time. Towards the second half of each cycle, there are opportunities for review both internal and external. Community members are consulted for feedback which is evaluated by the committee alongside statistical information to streamline the process. These review cycles identify points of optimisation within the program to improve both implementation efficiency and cost, allowing for the scheme to effectively help those in need in subsequent iterations.

Metrics for both voluntary and involuntary schemes detailed in Objectives will be re-evaluated and claim amounts and the number of eligible households will be adjusted accordingly.

Ultimately, the goal of the scheme is to reduce the proportion of involuntary displacement. Taking the amount of involuntary displacement before the implementation of the scheme as 100%, the scheme aims to decrease the need for displacement by 15%, 25% and 35% through three cycles respectively. These figures are summarised below in Table 2.

<img width="816" alt="Screen Shot 2023-04-05 at 8 18 42 pm" src="https://user-images.githubusercontent.com/113441885/230053206-824701b1-c51f-4828-8448-7038e0c8958b.png">

# Pricing and Costs
### Without the Program
### With the Program
# Assumptions
# Data and Data Limitations
# Risk and Risk Mitigation Considerations
# Recommendation
# References
![sbpbrui9ebb61](https://user-images.githubusercontent.com/129948833/230050536-e0c4f808-2514-486c-870a-e3779a0b9f06.jpg)


