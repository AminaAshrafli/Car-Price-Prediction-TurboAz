🚗 Car Price Prediction using Turbo.az Data

This project leverages data from Turbo.az, Azerbaijan's leading online automotive marketplace, to predict car prices accurately using machine learning techniques.

📌 Project Goals
Collect and analyze vehicle listings from Turbo.az.
Perform data preprocessing and feature engineering.
Develop machine learning models to predict vehicle prices based on their features.
Evaluate model performance using standard metrics (RMSE, R² score).

🛠️ Technologies Used

Python
Pandas: Data manipulation and cleaning
NumPy: Numerical computations
Scikit-Learn: Building and evaluating machine learning models
Matplotlib / Seaborn: Data visualization

## 📂 Dataset Description

The dataset includes approximately **50,000 car listings** collected from [Turbo.az] between January 2023 and March 2024.

| Feature                 | Description                                                |
|-------------------------|------------------------------------------------------------|
| `price_x, price_y`      | Vehicle prices in various currencies                       |
| `currency_x, currency_y`| Currency type used for prices                              |
| `attributes`            | Vehicle specs (year, engine capacity, mileage)             |
| `city`                  | City of the listing                                        |
| `day, hour`             | Date and hour when the listing was posted or updated       |
| `vip`                   | VIP or regular listing                                     |
| `featured`              | Featured or normal listing                                 |
| `barter`                | Availability of barter                                     |
| `loan`                  | Availability on loan                                       |
| `salon`                 | Whether listed by a dealership or individual               |
| `description`           | Additional vehicle details                                 |
| `owner_name`            | Owner’s name                                               |
| `shop_name`             | Name of the dealership/shop                                |
| `phone`                 | Contact phone number                                       |
| `vin`                   | Vehicle Identification Number                              |
| `Ban növü`              | Vehicle body type                                          |
| `Buraxılış ili`         | Year of manufacture                                        |
| `Marka`                 | Vehicle brand                                              |
| `Model`                 | Vehicle model                                              |
| `Mühərrik`              | Engine details                                             |
| `Qəzalı`                | Accident status                                            |
| `Rəng`                  | Color of vehicle                                           |
| `Sahiblər`              | Number of previous owners                                  |
| `Sürətlər qutusu`       | Transmission type                                          |
| `Yeni`                  | Whether vehicle is new                                     |
| `Yerlərin sayı`         | Number of seats                                            |
| `Yürüş`                 | Mileage                                                    |
| `Ötürücü`               | Drive type (front-wheel, rear-wheel, AWD)                  |
| `extra_info`            | Additional notes or remarks                                |

**Note:** Certain columns contain missing or sensitive data due to user privacy considerations.

📊 Model Evaluation

Models are evaluated using:
Root Mean Squared Error (RMSE)
R² (coefficient of determination)

🤝 Contributions

Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.


The data is gathered from Turbo.az and includes key attributes that influence the price, such as car specifications, city of listing, and seller information.

Key Features in the Dataset:
price_x, price_y: Car prices in different currencies.
currency_x, currency_y: The currencies used for the prices.
attributes: Information such as production year, engine size, mileage, etc.
city: City where the car is listed.
day, hour: Time details when the listing was posted.
vip, featured: Whether the listing is VIP or featured.
barter: Whether barter is accepted for the car.
loan: Whether the car is available for purchase via loan.
owner_name, shop_name: Names of the owner or the shop listing the car.

Model Training and Evaluation:
The data is split into training and testing sets, and different machine learning models are trained to predict car prices. The performance of the models is evaluated using common metrics like Mean Squared Error (MSE) and R-Squared (R²).
