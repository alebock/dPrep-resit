# TITLE

## 1.Purpose and Motivation


## 2.Research Question

## 3.Method
### 3.1. Included Variables

|Variable (group) |Description|
|---------|----------|
|**room_type**|Since there are 4 room types: "Entire home/apt", "Private room", "Shared room", "Hotel", three dummy variables have been coded (a hotel room being the baseline) for the purpose of including them in the regression analysis. **Entire_home_apt_room_type** (1 if listing is an entire home or apartment, 0 if the listing is of a different type); **Private_room_room_type** (1 if listing is a private room, 0 if the listing is of a different type). **Shared_room_room_type** (1 if listing is a shared room, 0 if the listing is of a different type)|
|**neighbourhood_goup**|Since in Hawaii there are 4 neighborhood groups: "Hawaii", "Kauai", "Maui", "Honolulu", three dummy variables have been coded (Honolulu being the baseline) for the purpose of including them in the regression analysis. **Hawaii_neighborhood** (1 if the listing is in the Hawaii neighbourhood, 0 if the listing is in a different neighbourhood. **Kauai_neighborhood** (1 if the listing is in the Kauai neighbourhood, 0 if the listing is in a different neighbourhood. **Maui_neighborhood** (1 if the listing is in the Maui neighborhood, 0 if the listing is in a different neighborhood.|
|**accommodates**|the maximum number of guest the property can accommodate|
|**bathrooms**|the number of bathrooms of the property|
|**bathroom_type**|dummy variable to indicate whether the bathroom(s) are private or shared|
|**bedrooms**|the number of bedrooms of the property|
|**beds**|the number of beds of the property|
|**review_score_rating**|the review score rating of the property (on a 5-point scale)|
|**instant_bookable**|dummy indicating whether the property can be booked automatically or the host's approval is needed|
|**time_diff**|the number of days left until the booking starts|
|**winter**|dummy variable indicating the season (Hawaii only has two seasons) taking the value 1 for **winter** (November-April) and 0 for **summer** (May-October)|

Overview of other variables used to merge different datasets or aggregate the data:
|Variable |Used for:|
|---------|----------|
|**id**|merging the listings and the calendar datasets|
|**date**|aggregating the dataset per season|

Data dictionary of the raw datasets can be found [here](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=1322284596).

### 3.2.Research Method

## 4.Repository overview 
```
├── README.md
├── data
├── gen
│   ├── analysis
│   ├── data-preparation
│   └── paper
└── src
|  ├── analysis
|  ├── data-preparation
|  └── paper
└── make file
```

## 5.Dependencies
Please follow this [guide](https://tilburgsciencehub.com/building-blocks/configure-your-computer/statistics-and-computation/r/) to install R.

Also, make sure you install the following packages:
```
install.packages("tidyverse")
install.packages("utils")
install.packages("stringr")
```

## 6.Running Instructions

### Cloning Repository
1. Open Git Bash
2. Change working directory to preferred location
3. Type ```git clone https://github.com/course-dprep/what-influences-AirBnB-prices.git```

### Running makefile
1. Change working directory to what-influences-AirBnB-prices
2. Type ```make```

## 7.Results, Vizualizations and Conclusion

### 7.1.Results


## 7.2.Interpretation

### 7.3. Selected Vizualizations

### 7.4. Conclusion


