# Real-Time Anomaly Detection in Dynamic Data Streams

## Problem Statement
In today's fast-paced world, the ability to detect anomalies in real-time data streams is crucial across various domains such as finance, cybersecurity, and system monitoring. Anomalies in continuous data streams may indicate fraudulent activities, system failures, or other critical issues that demand immediate attention. This project addresses the challenge of detecting anomalies in dynamic data streams by implementing the Isolation Forest algorithm.

## Methodology Used
The Isolation Forest algorithm is a powerful tool for anomaly detection in dynamic data streams. It operates by isolating anomalies in the feature space, making it particularly suitable for real-time detection where anomalies are rare and distinct. The contamination level is set to 0.02 to establish a threshold for anomaly detection. Additionally, functions are designed to simulate dynamic floating-point data streams with realistic seasonal variations and random noise, enhancing the complexity and realism of the data.

## Architecture Implementation
The architecture consists of several key components:
- **Data Stream Simulation:** Functions are developed to generate synthetic data streams with seasonal variations and random noise, mimicking real-world scenarios.
- **Isolation Forest Algorithm:** The Isolation Forest algorithm is implemented for real-time anomaly detection. It is trained on the simulated data stream with a contamination level of 0.02.
- **Anomaly Detection:** Anomaly scores are computed for each data point using the decision_function method. Data points with negative anomaly scores are identified as anomalies, indicating isolation from the majority of data points in the feature space.
- **Visualization:** Results are visualized using matplotlib, providing insights into the detected anomalies and their correlation with the data stream.

## Usage
To run the code:
1. Clone the repository.
2. Ensure you have Python installed along with the required libraries mentioned in the requirements.txt file.
3. Run the Anamoly_Detection_for_a_Floating_Point_Data_Stream_Documented.ipynb file.

## Future Improvements
- Integration of additional anomaly detection algorithms for comparison.
- Enhancements in data stream simulation for increased realism.
- Deployment of the solution in real-world applications with live data streams.


## License
This project is licensed under the [MIT License](link-to-license-file).
