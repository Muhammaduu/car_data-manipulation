# Car Dataset Analysis

## Dataset Overview
The dataset contains information about different car models and their specifications. It includes the following columns:
- **Make**: The manufacturer of the car.
- **Model**: The model name of the car.
- **Type**: The type of vehicle (SUV, Sedan, etc.).
- **Origin**: The region where the car was manufactured (e.g., Asia, Europe, USA).
- **DriveTrain**: The type of drivetrain (e.g., FWD, RWD, AWD).
- **MSRP**: Manufacturer's Suggested Retail Price.
- **Invoice**: The price paid by the dealer to the manufacturer.
- **EngineSize**: The size of the car's engine (in liters).
- **Cylinders**: The number of cylinders in the engine.
- **Horsepower**: The power output of the engine.
- **MPG_City**: Miles per gallon in city driving.
- **MPG_Highway**: Miles per gallon on the highway.
- **Weight**: The weight of the car in pounds.
- **Wheelbase**: The distance between the front and rear wheels.
- **Length**: The length of the car in inches.

## Questions Answered

### Q1) Find and handle null values.
- Checked for null values and filled them with the mean of their respective columns if any were present.

### Q2) Different types of 'Make' and their counts.
- Listed all unique car manufacturers (`Make`) and counted how many cars belong to each manufacturer.

### Q3) Filter records based on 'Origin' being either Asia or Europe.
- Displayed all cars that were manufactured in Asia or Europe.

### Q4) Remove cars with weight above 4000 lbs.
- Deleted all rows where the `Weight` of the car was greater than 4000 lbs.

### Q5) Increase all `MPG_City` values by 3.
- Added 3 miles per gallon to every car's city mileage (`MPG_City`).
- 
- **Q6) Average MSRP and Invoice for each origin**:
- Grouped the data by `Origin` and calculated the mean of the MSRP and Invoice columns.
- **Q7) Most common drivetrain**:
- Identified the most frequent drivetrain type using `value_counts()` on the `DriveTrain` column.
- **Q8) Top 5 cars by horsepower**:
-  Sorted the data by `Horsepower` and listed the top 5 cars with the highest horsepower.
- **Q9) Average engine size by car type**: Grouped by `Type` and calculated the average `EngineSize` for each category.
- **Q10) Cars with engine size greater than 3.0 and 6 or more cylinders**:
-  Filtered the dataset to show cars that have an engine size greater than 3.0 liters and at least 6 cylinders.
## How to Use the Code
The code has been structured to:
1. **Handle missing values** by filling them with the mean of the columns.
2. **Filter and group** the data based on different conditions.
3. **Perform analysis** on various aspects like car types, origins, and engine specifications.

Feel free to explore and extend the analysis based on other attributes present in the dataset.

---

