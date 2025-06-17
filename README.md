# 👹 Design-of-Experiments-in-Manufacturing-using-Excel
This repository demonstrates key DoE concepts - applied to real-world manufacturing scenarios using Microsoft Excel. It includes:
1. Full factorial experimental design
2. Randomization
3. Blocking
4. Interaction analysis

---

## 🥱 Design of Experiments (DoE)
- DoE is a one-stop method for analyzing all influencing factors simultaneously
- It is used when known sources of variation have been eliminated but process is still not capable, if process is capable then DoE may not be required
- It identifies which variable individually effect key measures
- It determines variable combinations or interactions that impact capability
- It provides mathematical model to predict and optimize the response or process output under recommended settings
- It is preferred on One Factor At a Time (OFAT) experiments because it allows for accelerated learning and is less-time consulting

|*DoE* | *Regression*|
|--------|-------------|
| 1. Determines Cause & Effect | 1. Uncovers relationships |
| 2. Tries bold (or) creative solutions | 2. Uses existing data |
| 3. Clears results on the impact variable | 3. Results left open to the interpretation |
| 4. Measures impact on variability | 4. Cannot measure variability impact | 
| 5. Provides reliable information on interactions | 5. Provides risky information on interactions |
| 6. Requires leadership support and investment | 6. Does not require leader |

### 🤡 Terms used while conducting experiment
**Response**:

Dependent variables or outcomes of an experimental treatment that varies as changes are made to factors 
*Eg*: Product strength, average cycle time, sales, response time

**Factors**:

Independent or input variables that are changed during an experiment to validate their impact on the output. Can be qualitative and/or quantitative
*Eg*: Resource temperature, Procedural charges, Price

**Levels**:

- Settings or conditions of the factors that are treated during the experiment
- Two levels recommended per factor
      - Level 1 is normally coded as '-' and could represent status quo
      - Level 2 is normally coded as '+' and could represent the change tested
- The difference between level 1 and level 2 settings should be significant to detect impact

**Interactions**:

When the combination of two factors creates a result that is different from the result produced by the individual factors
*Eg*: Rolling time and temperature

**Treatment**:

A unique set of factors at specific levels whose effect on the response variable is of interest
*Eg*: Molding temperature at high setting and rolling time at low setting

**Trail**:

An experimental run for a special treatment

**Experimental unit**:

Quality of material to which one trail of a single treatment is applied to create a response

**DoE error**:

Error is variation in experimental units that have been exposed to the same treatment

**Repetition & Replication**:

Repetition and Replication provide an estimate of experimental error and help determine the statistical significance of the difference in readings

|*Repetition* | *Replication*|
|-------------|--------------|
|1. During the treatment setup, several samples are run without changing the setting|1. The entire experiment is repeated with change in the setting of experimental conditions between trails|
|2. This shows short-term variability|2. This shows long-term variability|

**Randomization**:

- Running the trail without any order
- The use of randomization helps with:
     - Noise factors that are completely random and uncontrollable
     - Avoid time related changes, uncontrollable variables, and tool wear
     - Eliminating bias in expert opinions

**Blocking**:

- Setting the DoE so that controllable noise factors are incorporated into the experiment or held at a constant level throughout
- Controllable noise factors are factors that may impact the response but not a focus area of interest for the experiment

**Full Factorial Experimental Design**:

- Contains all combinations of all levels of all factors
- Ensure no possible treatment combinations get omitted
- Is preferred over other designs
