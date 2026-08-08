# Spatial Intelligence

## Q1 --- Gas Stations

### Client problem

-   New 100 m school rule
-   Which stations are affected?
-   Where could they relocate?

### 1 --- Represent the problem spatially

-   Municipal boundary
-   Schools
-   Gas stations
-   Roads

### 2 --- Identify affected stations

-   Measure proximity
-   Apply 100 m protected areas
-   Produce compliance list

### 3 --- Identify where relocation is possible

-   Focus on plausible roads
-   Remove protected areas
-   Remove other spatial restrictions

### 4 --- Construct the opportunity set

-   Locations surviving spatial screening
-   Possible relocation alternatives

### 5 --- Choose a relocation strategy

#### Choice A --- Satisficing

-   Select an acceptable location
-   Reserve required surrounding space
-   Update opportunity set
-   Repeat for remaining stations
-   Goal: feasible and implementable solution

#### Choice B --- Optimization

-   Define an explicit objective
-   Consider relocations jointly
-   Respect spatial constraints
-   Minimize total relocation distance
-   Goal: best feasible solution under the model

### 6 --- Expert review

-   Spatially feasible ≠ approved
-   Check zoning and parcels
-   Check engineering and costs
-   Apply municipal judgment

## Q2 --- COVID Fatality

### Client problem

-   Choropleth shows high and low fatality
-   But what is happening around each province?
-   Where might different kinds of attention be warranted?

### 1 --- Observe the geographic pattern

-   Calculate provincial fatality
-   Map current high and low values

### 2 --- Define what "nearby" means

#### Main choice --- Contiguity

-   Provinces sharing boundaries

#### Robustness choice --- K-nearest neighbors

-   Alternative neighborhood definition

### 3 --- Compare each province with its surroundings

-   Own fatality
-   Neighbors' fatality
-   Spatial lag

### 4 --- Is there a broader spatial pattern?

-   Global Moran's I
-   Evidence of spatial dependence?

### 5 --- Where are the local patterns?

-   Local Moran's I / LISA

#### High--High

-   High locally + high surroundings
-   Broad high-fatality environment
-   Priority attention

#### High--Low

-   High locally + low surroundings
-   Unusual local high
-   Local investigation

#### Insignificant

-   No significant local spatial association
-   Neutral category in the LISA map

#### Low--High

-   Low locally + high surroundings
-   Comparatively better local situation in unfavorable surroundings
-   Early-warning attention

#### Low--Low

-   Low locally + low surroundings
-   Comparatively favorable environment
-   Preserve, monitor, and learn

### 6 --- Are conclusions robust?

-   Change neighborhood definition
-   Same classification → more robust
-   Different classification → sensitive to spatial assumptions

### 7 --- Expert interpretation

-   Spatial association ≠ causation
-   LISA ≠ forecast
-   Add epidemiological evidence
-   Decide what attention, if any, is appropriate

## Common lesson

### Computational evidence

-   Makes spatial relationships reproducible
-   Reduces a complex geographic problem

### Domain judgment

-   Adds information absent from spatial data
-   Interprets the evidence
-   Makes the final decision
