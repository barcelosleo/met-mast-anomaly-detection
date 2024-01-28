# met-mast-anomaly-detection
The intent of this repository is to gather data and information about anomaly detection in meteorological data.

The `kegnes_all_data.tsv` contains measuredments performed on a met mast located at the Kegnæs Peninsula. This data is shared publicly by [DTU](https://doi.org/10.11583/DTU.14135618).

The `kegnes_all_exclusions.tsv` contains data about the measurement failure periods, and an estimated reason for that failure. This analysis results from a Final Project of Engineering Physics work, where were conducted tests regarding anomaly detection in met mast data. The labels of anomalous periods were based on a protocol which is available in the `PMMA.pdf` file, which was proposed by this work.

A brute-force algorithm also was proposed, with the intent of automatically assign the anomaly flags for the sensors, which is available in the `brute_force_algorithm.ipynb`. This proposed algorithm didn't performed well when we calculate the *F1-Score*, as it results in a value close to 0.2. For this reason, use this with caution.
