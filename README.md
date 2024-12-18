# Customer Segmentation Analysis

## Overview
A comprehensive customer segmentation analysis project using multiple clustering algorithms (K-means, Hierarchical, DBSCAN, GMM) to group customers based on their behavior patterns. The project helps businesses understand their customer base and develop targeted marketing strategies.

## Features
- Multiple clustering algorithms implementation
- Automated optimal parameter selection
- Comprehensive visualization of clusters
- Detailed performance comparison of different algorithms
- Interactive visualizations
- Detailed cluster profiling

## Dataset
The project uses the Mall Customer Segmentation Data which includes the following features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Requirements
```python
numpy==1.21.0
pandas==1.3.0
scikit-learn==0.24.2
matplotlib==3.4.2
seaborn==0.11.1
scipy==1.7.0
kneed==0.7.0
```

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
1. Place your data file (Mall_Customers.csv) in the project directory
2. Run the main analysis:
```python
python customer_segmentation.py
```

## Project Structure
```
customer-segmentation/
│
├── data/
│   └── Mall_Customers.csv
│
├── src/
│   ├── customer_segmentation.py
│   ├── clustering_algorithms.py
│   └── visualization.py
│
├── notebooks/
│   └── analysis.ipynb
│
├── requirements.txt
└── README.md
```

## Algorithms Implemented
1. **K-means Clustering**
   - Optimal k selection using elbow method
   - Silhouette analysis
   
2. **Hierarchical Clustering**
   - Dendrogram visualization
   - Ward's method
   
3. **DBSCAN**
   - Automated parameter optimization
   - Noise point handling
   
4. **Gaussian Mixture Model**
   - Component optimization
   - Probabilistic clustering

## Results
The analysis provides:
- Optimal number of customer segments
- Detailed profile for each segment
- Visualization of customer groups
- Performance metrics for each algorithm
- Comparative analysis of different clustering approaches

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Mall Customer Segmentation Dataset
- Scikit-learn documentation
- Clustering algorithm research papers

## Contact
Your Name - [your.email@example.com](mailto:your.email@example.com)
Project Link: [https://github.com/yourusername/customer-segmentation](https://github.com/yourusername/customer-segmentation)
