# House Prediction Using Machine Learning

## Competition Description

![Houses Banner](https://storage.googleapis.com/kaggle-media/competitions/kaggle/5407/media/housesbanner.png)

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

### Dataset Overview
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

### Practice Skills
- Creative feature engineering 
- Advanced regression techniques like random forest and gradient boosting

### Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

### Evaluation
#### Goal
Predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable.

#### Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.

### Submission File Format
The file should contain a header and have the following format:
```
Id,SalePrice
1461,169000.1
1462,187724.1233
1463,175221
etc.
```


---

## Dataset Description

### File Descriptions

- `train.csv`: The training set
- `test.csv`: The test set
- `data_description.txt`: Full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
- `sample_submission.csv`: A benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

### Data Fields

Here's a brief version of what you'll find in the data description file:

- `SalePrice`: The property's sale price in dollars. This is the target variable that you're trying to predict.
- `MSSubClass`: The building class
- `MSZoning`: The general zoning classification
- `LotFrontage`: Linear feet of street connected to property
- `LotArea`: Lot size in square feet
- `Street`: Type of road access
- `Alley`: Type of alley access
- `LotShape`: General shape of property
- `LandContour`: Flatness of the property
- `Utilities`: Type of utilities available
- `LotConfig`: Lot configuration
- `LandSlope`: Slope of property
- `Neighborhood`: Physical locations within Ames city limits
- `Condition1`, `Condition2`: Proximity to main road or railroad
- `BldgType`: Type of dwelling
- `HouseStyle`: Style of dwelling
- `OverallQual`: Overall material and finish quality
- `OverallCond`: Overall condition rating
- `YearBuilt`: Original construction date
- `YearRemodAdd`: Remodel date
- `RoofStyle`: Type of roof
- `RoofMatl`: Roof material
- `Exterior1st`, `Exterior2nd`: Exterior covering on house
- `MasVnrType`: Masonry veneer type
- `MasVnrArea`: Masonry veneer area in square feet
- `ExterQual`: Exterior material quality
- `ExterCond`: Present condition of the material on the exterior
- `Foundation`: Type of foundation
- `BsmtQual`: Height of the basement
- `BsmtCond`: General condition of the basement
- `BsmtExposure`: Walkout or garden level basement walls
- `BsmtFinType1`: Quality of basement finished area
- `BsmtFinSF1`: Type 1 finished square feet
- `BsmtFinType2`: Quality of second finished area (if present)
- `BsmtFinSF2`: Type 2 finished square feet
- `BsmtUnfSF`: Unfinished square feet of basement area
- `TotalBsmtSF`: Total square feet of basement area
- `Heating`: Type of heating
- `HeatingQC`: Heating quality and condition
- `CentralAir`: Central air conditioning
- `Electrical`: Electrical system
- `1stFlrSF`: First Floor square feet
- `2ndFlrSF`: Second floor square feet
- `LowQualFinSF`: Low quality finished square feet (all floors)
- `GrLivArea`: Above grade (ground) living area square feet
- `BsmtFullBath`: Basement full bathrooms
- `BsmtHalfBath`: Basement half bathrooms
- `FullBath`: Full bathrooms above grade
- `HalfBath`: Half baths above grade
- `Bedroom`: Number of bedrooms above basement level
- `Kitchen`: Number of kitchens
- `KitchenQual`: Kitchen quality
- `TotRmsAbvGrd`: Total rooms above grade (does not include bathrooms)
- `Functional`: Home functionality rating
- `Fireplaces`: Number of fireplaces
- `FireplaceQu`: Fireplace quality
- `GarageType`: Garage location
- `GarageYrBlt`: Year garage was built
- `GarageFinish`: Interior finish of the garage
- `GarageCars`: Size of garage in car capacity
- `GarageArea`: Size of garage in square feet
- `GarageQual`: Garage quality
- `GarageCond`: Garage condition
- `PavedDrive`: Paved driveway
- `WoodDeckSF`: Wood deck area in square feet
- `OpenPorchSF`: Open porch area in square feet
- `EnclosedPorch`: Enclosed porch area in square feet
- `3SsnPorch`: Three season porch area in square feet
- `ScreenPorch`: Screen porch area in square feet
- `PoolArea`: Pool area in square feet
- `PoolQC`: Pool quality
- `Fence`: Fence quality
- `MiscFeature`: Miscellaneous feature not covered in other categories
- `MiscVal`: $Value of miscellaneous feature
- `MoSold`: Month Sold
- `YrSold`: Year Sold
- `SaleType`: Type of sale
- `SaleCondition`: Condition of sale

For a comprehensive description of each field, refer to `data_description.txt`.

---

