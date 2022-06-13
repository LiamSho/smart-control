# Credit Card Approval Prediction

A Credit Card Dataset for Machine Learning

## Tables

### application_record.csv

| Column              | Value                                                                                                        | Remark                                                                                                                |
|---------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ID                  | str (-> int)                                                                                                 | client number                                                                                                         |
| CODE_GENDER         | `F` `M`                                                                                                      | gender, F or M                                                                                                        |
| FLAG_OWN_CAR        | `Y` `N`                                                                                                      | if user have a car                                                                                                    |
| FLAG_OWN_REALTY     | `Y` `N`                                                                                                      | is there a property                                                                                                   |
| CNT_CHILDREN        | int                                                                                                          | number of children                                                                                                    |
| AMT_INCOME_TOTAL    | float (-> int)                                                                                               | annual income                                                                                                         |
| NAME_INCOME_TYPE    | `Working` `Commercial associate` `Pensioner` `State servant` `Student  `                                     | income category                                                                                                       |
| NAME_EDUCATION_TYPE | `Academic degree` `Lower secondary` `Incomplete higher` `Higher education` `Secondary / secondary special`   | education level                                                                                                       |
| NAME_FAMILY_STATUS  | `Married` `Single / not married` `Civil marriage` `Separated` `Widow`                                        | marital status                                                                                                        |
| NAME_HOUSING_TYPE   | `House / apartment` `With parents` `Municipal apartment` `Rented apartment` `Office apartment`               | Way of living                                                                                                         |
| DAYS_BIRTH          | int                                                                                                          | Birthday. Count backwards from current day (0), -1 means yesterday                                                    |
| DAYS_EMPLOYED       | int                                                                                                          | Start date of employment. Count backwards from current day(0). If positive, it means the person currently unemployed. |
| FLAG_MOBIL          | `0` `1`                                                                                                      | Is there a mobile phone                                                                                               |
| FLAG_WORK_PHONE     | `0` `1`                                                                                                      | Is there a work phone                                                                                                 |
| FLAG_PHONE          | `0` `1`                                                                                                      | Is there a phone                                                                                                      |
| FLAG_EMAIL          | `0` `1`                                                                                                      | Is there an email                                                                                                     |
| OCCUPATION_TYPE     | `Laborers` `Core staff` `Sales staff` `Managers` `Drivers` It may be `NULL`                                  | Occupation                                                                                                            |
| CNT_FAM_MEMBERS     | int                                                                                                          | Family size                                                                                                           |

### credit_record.csv

| Column         | Value                           | Remark                                                                                                                                                                                                                                                              |
|----------------|---------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ID             | str (-> int)                    | client number                                                                                                                                                                                                                                                       |
| MONTHS_BALANCE | `0` `-1` `-2` etc.              | record month: The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on                                                                                                                         |
| STATUS         | `0` `1` `2` `3` `4` `5` `C` `X` | **0**: 1-29 days past due. **1**: 30-59 days past due. **2**: 60-89 days overdue. **3**: 90-119 days overdue. **4**: 120-149 days overdue. **5**: Overdue or bad debts, write-offs for more than 150 days. **C**: paid off that month. **X**: No loan for the month |

## Links

Data source: [Kaggle](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction)

License: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
