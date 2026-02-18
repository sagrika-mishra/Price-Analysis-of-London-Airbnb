# London Airbnb Pricing Analysis: Marketing Analytics Case Study
London Airbnb hosts often face pricing uncertainty driven by factors such as location accessibility, accommodation type, and guest satisfaction. Incorrect pricing leads to lower occupancy, reduced revenue, and weak competitive positioning.

# Business Question:
How do metro distance and guest satisfaction ratings influence Airbnb listing prices across room types, and what pricing actions should hosts take by segment?

For Airbnb hosts and revenue teams, pricing is a direct lever for growth. Hosts need to decide whether to compete on accessibility, property type, or experience quality. Therefore, this analysis mirrors real marketing analytics work where customer behaviour informs pricing and positioning strategy and answers the following key objectives:
1. Optimize listing strategy
2. Improve revenue per listing
3. Position properties competitively
4. Prioritize experience improvements that increase willingness to pay

# Dataset:
The dataset contains London Airbnb listings with variables related to pricing and customer experience.
Key features used:
- Price
- Room_Type
- Metro_Distance
- Guest_Satisfaction_Overall
- Person_Capacity
- Host_Superhost

Data preparation steps included:
- Removal of missing values
- Standardization of room types
- Outlier treatment on price
- Feature validation for analysis readiness

# Analysis Workflow:
- Segment-level pricing patterns: Compared average and median prices across Room_Type and Metro_Distance segments.
- Interaction between accessibility and experience: Evaluated whether high Guest_Satisfaction_Overall offsets distance-driven price drops.
- Differentiated segment behaviour: Separated premium segments (Entire Home, Studio) from value segments (Private, Shared) to avoid averaging effects that hide true patterns.

# Key Insights:
1. Metro proximity drives price premiums: Listings located very close to metro stations consistently command higher prices across most room types. Accessibility remains a primary value driver.
2. Guest satisfaction acts as a price multiplier: High satisfaction scores allow hosts to sustain higher prices even when metro distance increases, especially for Private and Shared rooms.
3. Entire homes and studios behave differently: Entire Home and Studio listings maintain premium pricing across distances, suggesting these segments compete more on property value than pure accessibility.
4. Budget segments are more location sensitive: Private and Shared rooms show clearer price decline with distance, indicating stronger price sensitivity in value-focused segments.

# Business Recommendations:
Based on the analysis, it is clear that both pricing and positioning should be segment-specific. Airbnb hosts should:
1. Use proximity-based pricing tiers for Private and Shared rooms by keeping a lower price as the distance increases. And if the metro distance is high, invest in experienced drivers (cleanliness, check-in, communication) to protect satisfaction and sustain pricing
2. Maintain premium positioning for Entire Home and studio listings regardless of metro distance, but protect satisfaction because it strengthens pricing power across locations
4. Invest in guest satisfaction drivers as a trigger for pricing adjustment, raise prices cautiously when satisfaction stays high, and review pricing when satisfaction declines
5. Use segmented pricing rather than one-size-fits-all pricing
