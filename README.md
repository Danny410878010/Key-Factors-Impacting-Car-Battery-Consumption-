# Electric Vehicle Battery Consumption Analysis

A comprehensive analysis of electric vehicle battery consumption patterns, examining the relationships between State of Charge (SOC), distance traveled, temperature, and trip duration using statistical modeling and feature importance analysis.

## Key Findings

### Distance-SOC Relationship
- Linear correlation between distance and battery consumption
- Constant SOC consumption per kilometer
- Linear model outperforms tree-based models
- Distance feature importance: 0.92

### Temperature Impact
- Significant negative correlation between SOC/km and battery temperature
- Lower temperatures require higher battery consumption
- Temperature is second most important feature after distance
- Two distinct SOC/km patterns based on temperature ranges

### Duration Analysis
- Trip duration shows limited direct impact (0.02 feature importance)
- High correlation between distance and duration
- Distance variable captures most duration-related effects

## Methodology
- Statistical analysis of SOC variations
- Linear and tree-based modeling approaches
- Feature importance analysis
- Temperature correlation studies

## Applications
- EV range prediction
- Battery efficiency optimization
- Temperature impact assessment
- Trip planning optimization

## Technical Details
- Primary metric: State of Charge (SOC)
- Key features: Distance, temperature, duration
- Model comparison: Linear vs Tree-based
- Correlation analysis between variables
