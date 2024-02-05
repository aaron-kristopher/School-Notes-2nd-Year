---

---
## DATA CLASSIFICATION FOR MODELING
### Modeling in the Real World
==Quantitative analysis models are used extensively by real organization to solve real problems==
- In the real world, quantitative analysis models can be complex, expensive, and difficult to sell
- Following the steps in the process is an important component of success
> Example: Analyzing patient data to know what treatments are needed

### QA / MS / OR and Decision Making

==Potential Reasons for a Quantitative Analysis Approach to Decision Making==
- The problem is Complex.
	-  There are multiple variables and relationships.
			Example: Airline Flight Schedule
				1. Destination
				2. Time / Schedule
				3. Availability of aircrafts
				4. Passengers' Demand
			 
- The problem is very important.
	- indicates the success or failure of an organization.
	
- The problem is new.

- The problem is repetitive.
	- the problem is recurring.

### Problem-Solving Process

==Goal: Solve a problem==
- Model must be valid
- Model must be tractable
- Solution must be useful

### The Situation

- The initial step of problem-solving
- Refers to circumstances within an organization
- may involve current operations or proposed expansions due to ==expected shifts==
- May become apparent through ==issues/complaints== or through ==suggestions==
- May be a conscious effort to improve efficiency or response to an unexpected crisis.

==Example: Programmers are not happy with their schedules; project using too many tools and approaches==

**FORMULATE THE PROBLEM STATEMENT**

- Describe system
- Define boundaries
- State assumptions
- Select performance measures
- Define variables
- Define constraints
- Data requirements

==Example: Maximize individual programmer's preferences subject to project requirements==

### Constructing a Model

- Involves the translation of a problem into logical or mathematical terms
- Problem must be ==translated from verbal==, qualitative terms to ==to logical==, quantitative terms
- A logical model is a series of rules, usually embodied in a computer program
- A mathematical model is a collection of functional relationships by which allowable actions are delimited and evaluated

==Example: Define relationships between individual programmer assignments and preference violations; define trade offs between the use of tools and other approaches.==

### Model Development

- ==Models== are representations of real objects or situations.
- Three ==forms of models== are iconic, analog, and mathematical.
	- ==Iconic models== are physical replicas (scalar representations) of real objects.
	- ==Analog models== are physical in form, but do not physically resemble the object being modeled.
	- ==Mathematical models== represent real world problems through a system of mathematical formulas and expressions based on key assumptions, estimates, or statistical analyses.
- **Analog Model:**
	- physical representation of the real world. Such models are always reduced in size
- **Iconic Model:**
	- does not act like the real thing (as the analog model does) but only looks like it. For example a road map or an organization chart.
- **Verbal Model:**
	- involves a verbal description of a real situation. Language, written or spoken, is employs to abstract the relevant factors or characteristics. A newspaper description of a football game is verbal model
- **Mathematical Model:**
	- employs mathematical manipulation of symbols to abstract and represent the behavior of a real-world system.

### Advantages of Models

==Generally, experimenting with models (compared to experimenting with the real situations):==

- Require ==less time==
- is ==less expensive==
- involves ==less risk==

### Mathematical Models

- Relate ==decision variables== (controllable inputs) with ==fixed or variable parameters== (uncontrollable inputs).
- Frequently seek to maximize or minimize some ==objective function== subject to constraints.
- Are said to be ==stochastic== if any of the ==uncontrollable inputs== (parameters) is subject to variation (random), otherwise are said to be ==deterministic==.
- Generally, stochastic models are more difficult to analyze.
- The values of the decision variables that provide the mathematically-best output are referred to as the ==optimal solution== for the model.
	> Optimal Solution
	> * the best possible outcome
	> * the solution chosen is the most favorable

### Transforming Model Inputs into Output

Controllable Inputs (Decision Variables) - Decisions need to be made to reach a certain objective

Uncontrollable Inputs (Environmental Factors) - Various elements and conditions of the surrounding
Mathematical Model -

Output (Projected Results) - Expected results aligned with the objective

### Solving the Mathematical Model

- Many tools are available
- Some lead to "optimal" solutions (Deterministic Models)
- Others only evaluate candidates -> trial and error to find "best" course of action

==Example: Read programmer profiles and demand requirements, apply algorithm, post-processes results to get monthly schedules.==

- Involves identifying the values of the decision variables that provide ==the "best" output== for the model
- One approach is ==trial-and-error==
	- might not provide the best solution
	- inefficient (numerous calculations required)
- Special solution procedures have been developed for specific mathematical models.
	- some small models/problems can be solved by ==hand calculations==
	- most practical applications require using a ==computer==
	
> [!Info]
> After creating a model, you should test your model

- Often, the goodness/accuracy of a model cannot be assessed until solutions are generated.
- Small test problems having known, or at least expected, solutions can be used for model testing and validation.
- If the model generates expected solutions:
	- ==use the model on the full-scale problem==
- If inaccuracies or potential shortcomings inherent in the model are identified, take corrective action such as:
	- ==collection of more -accurate input data==
	- ==modification of the model==

### Implementation

- A solution to a problem usually implies ==changes for some individuals== in the organization
- Often there is ==resistance to change==, making the implementation difficult
- ==User-friendly system== needed
- Those affected should go through training

### Implementation and Follow-Up

- Successful implementation of model results are of critical importance.
- Secure as much user involvement as possible throughout the modeling process.
- Continue to monitor the contribution of the model.
- It might be necessary to refine or expand the model.

### Report Genearion

- A managerial report, based on the results of the model, should be prepared.
- The report should be easily understood by the decision maker.
- The report should include:
	- ==the recommended decision==
	- ==other pertinent information about the results== (for example, how sensitive the model solution is to the assumptions and data used in the model)

### Components of OR-Based Decision Support System

 Data base (profiles, external resources, rules)
- Graphical User Interface (GUI); web enabled using Java or VBA
- Algorithms, pre-processor[^1] and post-processor[^2]
- What-if analysis
- Report generation

[^1]:  Preparing of data. Includes data collection, data input
[^2]:  Results obtained by the algorithm