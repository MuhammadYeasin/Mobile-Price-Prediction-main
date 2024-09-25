# Mobile Price Prediction

This project involves analyzing the Mobile Price Data to build and evaluate classification models for predicting mobile phone price ranges based on various hardware and specification features.

## Dataset

The dataset used in this analysis contains several features related to mobile phone specifications and their corresponding price range categories. 

### Columns Description

| Column        | Description                                                           |
| ------------- | --------------------------------------------------------------------- |
| battery_power | Total energy a battery can store in one time measured in mAh          |
| blue          | Has Bluetooth or not (0: No, 1: Yes)                                  |
| clock_speed   | Speed at which the microprocessor executes instructions               |
| dual_sim      | Has dual SIM support or not (0: No, 1: Yes)                           |
| fc            | Front Camera mega pixels                                              |
| four_g        | Has 4G or not (0: No, 1: Yes)                                         |
| int_memory    | Internal Memory in Gigabytes                                          |
| m_dep         | Mobile Depth in cm                                                    |
| mobile_wt     | Weight of mobile phone in grams                                       |
| n_cores       | Number of cores of processor                                          |
| pc            | Primary Camera mega pixels                                            |
| px_height     | Pixel Resolution Height                                               |
| px_width      | Pixel Resolution Width                                                |
| ram           | Random Access Memory in Mega Bytes                                    |
| sc_h          | Screen Height of mobile in cm                                         |
| sc_w          | Screen Width of mobile in cm                                          |
| talk_time     | Longest time that a single battery charge will last when in use       |
| three_g       | Has 3G or not (0: No, 1: Yes)                                         |
| touch_screen  | Has touch screen or not (0: No, 1: Yes)                               |
| wifi          | Has wifi or not (0: No, 1: Yes)                                       |
| price_range   | Target variable: 0 (low cost), 1 (medium cost), 2 (high cost), 3 (very high cost) |

## Project Goals

The primary objective of this project is to build and evaluate predictive models to classify mobile phones into different price ranges based on their features.

### Major Steps

1. **Data Exploration and Cleaning**: Explore the dataset and clean it by removing abnormal instances and handling missing values.
2. **Feature Selection**: Study the correlation between the 'price range' and other features, and select the most relevant variables for prediction.
3. **Model Building**: Train classification models using selected features.
4. **Model Evaluation**: Evaluate the performance of the models using appropriate metrics.

## Results

The results of the analysis and model evaluations are documented in the notebook `48343110.ipynb`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

