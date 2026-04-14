# harris-teeter-membership-impact

## **Project Summary**

Our client, Harris Teeter, is a leading regional supermarket chain in the United States, and they are asking us to answer this one qustion : Does the VIC (Very Important Customer) membership ensure more purchases from each customer? They are trying to see if it is worth enforcing a new promotional measure of offering a one-month free VIC memberhip trial to all customers and trying to see the effectiveness of this marketing schema beforehand.

## **DAG Analysis**

From the DAG analysis, the criteria are D(Membership Status), X(Confounders - as gender, salary, age and marital status), and Y (Purchased amount). We will determine the TE through this Z, free membership trial as the X is already preassigned to each customer, and shows an imbalance of data.

## **Methods Used**

For assuring a RCT, we used Block treatment assignment with probability of treatment being 0.5. For causal inference, we used Exact Matching, Propensity Score Matching and IPTW Matching and examined the effect of each through t-tests(p-value analysis).

## **Results of Analysis**

From Exact Matching, the TE was $1,205. From Propensity Score Matching, the TE was $1,207. Finally, from Inverse Probability of Treatment Weighting, the TE was $1,204. This shows a causal effect from D(Membership Status) -> Y(Customer Spendings) were over $1.2K for every method utilized.

## **Business Implications to Clients**

Showing the effect of the membership status is $1.2K/year per customer, we can assume that compared to the former sample data, Harris Teeter will be able to obtain substantial amount of revenue more if they enforce this new trial basis to boost exposure to the membership program. For example, if the conversion rate from non-membership customers to actual subscription was 10% (of 6.5K customers), the additional value from treatment would be $7.8M.
