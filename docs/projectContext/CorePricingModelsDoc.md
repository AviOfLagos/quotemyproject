Perfect. What we’ll do now is create the **core documentation layer** for your site. Think of this as the **knowledge base that powers the calculator pages and SEO pages**.

This will be written in a way that you can later paste into **Markdown files for your Next.js/Nuxt/SvelteKit project**.

The models below are the **8 primary pricing models used by freelancers and agencies** in modern software consulting and product development within fields like Software Engineering and Project Management. Freelancers on platforms like Upwork and consultants at firms such as Deloitte and Accenture regularly use variations of these models.

---

# Core Documentation for Pricing Models

Below are **8 structured pricing model pages** you can directly turn into Markdown pages.

Each section contains:

* explanation
* formula
* when to use
* advantages
* disadvantages
* example calculation
* calculator inputs

---

# 1. Hourly Pricing

## Overview

Hourly pricing is the simplest and most common pricing model used by freelancers and early-stage agencies. In this model, the client pays for the **exact number of hours worked**.

This method is widely used when the **project scope is unclear** or expected to change during development.

## Formula

```
Total Cost = Hourly Rate × Total Hours Worked
```

## When to Use Hourly Pricing

* When the scope is not fully defined
* When working as a consultant
* When doing maintenance or bug fixing
* When working with startups that iterate frequently

## Advantages

* Easy to calculate
* Flexible for scope changes
* Low risk for developers

## Disadvantages

* Clients may worry about time overruns
* Difficult for clients to predict final cost
* Less incentive to work efficiently

## Example Calculation

Developer hourly rate:

```
$50/hour
```

Total hours worked:

```
120 hours
```

Total price:

```
120 × 50 = $6,000
```

## Calculator Inputs

Your calculator should ask for:

* hourly rate
* estimated hours
* optional buffer percentage
* optional margin percentage

---

# 2. Fixed Project Pricing

## Overview

Fixed project pricing involves agreeing on **one price for the entire project** before work begins.

This model is popular among agencies building MVPs, websites, and applications.

## Formula

```
Project Price =
(Estimated Hours × Hourly Rate)
+ Risk Buffer
+ Profit Margin
```

## When to Use

* when project scope is clear
* when features are defined
* when timeline is predictable

## Advantages

* clear expectations for the client
* predictable revenue for agencies
* easier sales process

## Disadvantages

* risk of underestimating work
* scope creep can destroy margins

## Example

Total estimated hours:

```
400 hours
```

Hourly rate:

```
$35/hour
```

Base cost:

```
400 × 35 = $14,000
```

Add risk buffer:

```
30% = $4,200
```

Subtotal:

```
$18,200
```

Add margin:

```
25% = $4,550
```

Final project price:

```
$22,750
```

## Calculator Inputs

* total project hours
* hourly rate
* buffer percentage
* margin percentage

---

# 3. Cost-Plus Pricing

## Overview

Cost-plus pricing calculates the **total cost of delivering the project**, then adds a profit markup.

This model ensures that the agency always covers its operational costs.

## Formula

```
Final Price =
Total Project Cost + Profit Markup
```

Where:

```
Total Project Cost =
Labor Cost + Operational Cost + Tools
```

## When to Use

* when using external contractors
* when cost structure is known
* when profit must be guaranteed

## Advantages

* predictable profit
* easy to justify to clients

## Disadvantages

* does not consider value to the client
* limits pricing upside

## Example

Developer payments:

```
$10,000
```

Operational costs:

```
$2,000
```

Total cost:

```
$12,000
```

Add markup:

```
30%
```

Final price:

```
$15,600
```

## Calculator Inputs

* labor cost
* overhead cost
* markup percentage

---

# 4. Value-Based Pricing

## Overview

Value-based pricing charges clients based on **the value the project creates for their business**, rather than the cost of development.

Consulting firms such as McKinsey & Company use variations of this model.

## Formula

```
Project Price =
Client Value × Value Percentage
```

## When to Use

* when project impacts revenue
* when project reduces operational costs
* when project provides strong business advantage

## Advantages

* highest possible profit margins
* aligns developer incentives with client success

## Disadvantages

* requires understanding client economics
* negotiation can be difficult

## Example

Expected revenue increase:

```
$500,000
```

Agency value percentage:

```
10%
```

Project price:

```
$50,000
```

## Calculator Inputs

* estimated business value
* percentage of value captured

---

# 5. Feature-Based Pricing

## Overview

Feature-based pricing estimates cost by assigning **development hours to individual features**.

The total cost is calculated based on the sum of all selected features.

## Formula

```
Total Hours = Sum of Feature Hours
Project Price =
(Total Hours × Hourly Rate)
+ Buffer
+ Margin
```

## When to Use

* SaaS MVPs
* marketplaces
* startup platforms

## Advantages

* transparent for clients
* easier estimation process
* scalable pricing system

## Disadvantages

* requires feature database
* complex systems may be hard to estimate

## Example Feature Table

| Feature             | Hours |
| ------------------- | ----- |
| User Authentication | 15    |
| Dashboard           | 40    |
| Payments            | 25    |
| Messaging           | 35    |
| Admin Panel         | 30    |

Total hours:

```
145 hours
```

Hourly rate:

```
$40/hour
```

Base cost:

```
145 × 40 = $5,800
```

## Calculator Inputs

* selected features
* feature hours
* hourly rate
* buffer
* margin

---

# 6. Retainer Pricing

## Overview

Retainer pricing involves a **recurring monthly payment** for ongoing services.

This model is common for long-term product development and support.

## Formula

```
Monthly Retainer =
Monthly Hours × Hourly Rate
```

## When to Use

* ongoing product development
* maintenance contracts
* long-term partnerships

## Advantages

* predictable monthly revenue
* stable client relationships

## Disadvantages

* client expectations can expand over time

## Example

Monthly hours:

```
40 hours
```

Hourly rate:

```
$60/hour
```

Monthly retainer:

```
$2,400
```

Annual contract:

```
$28,800
```

## Calculator Inputs

* hours per month
* hourly rate
* contract duration

---

# 7. Performance-Based Pricing

## Overview

Performance pricing ties compensation to **measurable results**, such as user growth or revenue.

This model is common in growth partnerships.

## Formula

```
Total Price =
Base Fee + Performance Bonus
```

## Example

Base fee:

```
$10,000
```

Bonus:

```
$2,000 per 10,000 users
```

Users acquired:

```
50,000
```

Bonus:

```
$10,000
```

Final payment:

```
$20,000
```

## Calculator Inputs

* base fee
* performance metric
* reward per unit

---

# 8. Equity-Based Pricing

## Overview

In equity pricing, an agency reduces its fee in exchange for **ownership in the startup**.

This model is popular when working with early-stage founders.

## Formula

```
Total Compensation =
Reduced Cash Fee + Equity Stake
```

## Example

Normal project cost:

```
$40,000
```

Startup pays:

```
$15,000
```

Equity:

```
5%
```

## Calculator Inputs

* standard project price
* cash payment
* equity percentage

---

# Example Calculation Dataset (For Your Tool)

Using the project example you gave earlier:

| Role     | Hours |
| -------- | ----- |
| Design   | 40    |
| Frontend | 120   |
| Backend  | 120   |
| PM       | 120   |

Total:

```
400 hours
```

Hourly rate:

```
$35/hour
```

Base cost:

```
$14,000
```

Buffer:

```
30%
```

Margin:

```
25%
```

Final price:

```
≈ $22,750
```

---

# Next Step (Very Important)

The next thing we should build for your tool is the **Feature Estimation Library**, which contains **50–80 common software features with estimated hours**.

Example:

| Feature             | Hours |
| ------------------- | ----- |
| Login System        | 12    |
| User Profile        | 10    |
| Search System       | 25    |
| Chat System         | 40    |
| Payment Integration | 25    |
| Notifications       | 20    |

This library will power:

* the **feature-based calculator**
* the **MVP estimator**
* SEO pages like:

```
"how much does it cost to build a SaaS MVP"
```
