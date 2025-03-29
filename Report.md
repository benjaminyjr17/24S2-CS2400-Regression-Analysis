# Multiple and Polynomial Regression Analysis Report

## Part I: Primary Equations (Standard Equations)

### Multiple Regression Standard Equations (Part A)

**MULTIPLE REGRESSION NORMAL EQUATIONS:**

**Equation Format:**
```
60·b₀ + 658.40·b₁ + 712.40·b₂ = 56421.51
658.40·b₀ + 7267.00·b₁ + 7724.57·b₂ = 617546.72
712.40·b₀ + 7724.57·b₁ + 13152.86·b₂ = 690986.87
```

**Matrix Format:**
```
[60       658.40     712.40    ] [b₀]   [56421.51    ]
[658.40     7267.00    7724.57  ] [b₁] = [617546.72  ]
[712.40     7724.57   13152.86   ] [b₂]   [690986.87  ]
```

### Polynomial Regression Standard Equations (Part B)

**POLYNOMIAL REGRESSION NORMAL EQUATIONS:**

**Equation Format:**
```
60·b₀ + 712.40·b₁ + 13152.86·b₂ = 56421.51
712.40·b₀ + 13152.86·b₁ + 313420.82·b₂ = 690986.87
13152.86·b₀ + 313420.82·b₁ + 8718750.07·b₂ = 13061507.07
```

**Matrix Format:**
```
[60       712.40     13152.86   ] [b₀]   [56421.51     ]
[712.40     13152.86    313420.82   ] [b₁] = [690986.87   ]
[13152.86    313420.82    8718750.07   ] [b₂]   [13061507.07  ]
```

## Part II: Explanation for Variable Selection

**VARIABLE SELECTION JUSTIFICATION:**

Variables x6 (schooling) and x9 (non-white population) were selected for multiple regression based on their strong correlations with death rate (r = -0.51 and r = 0.64 respectively) and low multicollinearity between them (r = -0.21). These socioeconomic factors represent education level and demographic composition, both critical determinants of mortality. Variable x9 was chosen for polynomial regression due to its strong correlation with death rate and evidence of non-linear patterns in data visualization.

## Part III: Results of Regression Analysis

**FINAL REGRESSION EQUATIONS:**

Multiple Regression: y = 1211.8562 + (-28.9793)x₆ + (3.9165)x₉, R² = 0.5628

Polynomial Regression: y = 882.9963 + (5.2506)x₉ + (-0.0227)x₉², R² = 0.4157