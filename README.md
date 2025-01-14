# Network Science and Graph Learning - Final Project

## Project Overview
This project explores complex network analysis using the Facebook100 dataset, which consists of social network data from 100 U.S. universities captured in 2005. The objective is to understand the structural properties of these networks and analyze how different social attributes influence network formation and dynamics.

## Key Analyses Conducted
1. **Social Network Analysis:** Examined network properties such as degree distribution, clustering coefficients, and edge density across different university networks.
   
2. **Assortativity Analysis:** Analyzed assortative mixing patterns based on attributes like student/faculty status, major, dorm, and gender to understand how these factors influence social connections.
   
3. **Link Prediction:** Implemented algorithms such as Common Neighbors, Jaccard, and Adamic/Adar to predict missing links within the networks, evaluating their performance through precision and recall metrics.
   
4. **Label Propagation:** Applied label propagation algorithms to infer missing labels for attributes like major, dorm, year, and gender, assessing accuracy and effectiveness.
   
5. **Community Detection:** Investigated how shared academic interests and year of study contribute to the formation of cohesive communities within university networks using modularity and homogeneity metrics.

## Dataset
- **Facebook100 Dataset:** A snapshot of Facebook friendship connections in 2005 from 100 U.S. universities. It includes anonymized user data with attributes such as status, dorm, major, gender, and graduation year.

## Tools and Libraries Used
- Python 3.x
- NetworkX
- NumPy
- Matplotlib
- Scikit-learn
- PyTorch (for label propagation algorithms)

## How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```

2. **Run the Analysis:**
   Execute the main Python scripts in the following order:
   - `social_network_analysis.py`
   - `assortativity_analysis.py`
   - `link_prediction.py`
   - `label_propagation.py`
   - `community_detection.py`

4. **View Results:**
   Output files and visualizations will be saved in the `results/` directory.

## Project Structure
```
project-directory/
├── fb100/data/          # Contains the Facebook100 dataset
├── fb100.ipynb          # Python notebook for various analyses
└── README.md            # Project overview
```

## Results Summary
- **Degree Distribution:** Most users have a few connections, while a few nodes serve as hubs with high connectivity.
- **Assortativity:** Positive assortativity was observed for attributes like major and dorm, indicating homophily.
- **Link Prediction:** Adamic/Adar consistently outperformed other algorithms in link prediction tasks.
- **Label Propagation:** High accuracy in predicting binary attributes like gender but lower accuracy for multi-category attributes like major.
- **Community Detection:** Academic majors and study years strongly influence community structures in some universities.

## Conclusion
This project demonstrates how network analysis methods can uncover meaningful patterns in social networks. Insights gained from studying the Facebook100 dataset enhance our understanding of social behavior and network evolution, with potential applications in designing more effective social media platforms and recommendation systems.

## Acknowledgments
- Course: Network Science and Graph Learning
- Instructor: Vincent Gauthier
- Dataset: Facebook100 Dataset

---

*This project was completed as part of the Network Science and Graph Learning course at Telecom SudParis.*

