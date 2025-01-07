# NYC Noise Complaints Analysis

## Overview

This project is an analysis of New York City's noise complaints database, aimed at providing actionable insights to mitigate noise pollution. The analysis is designed for the City Council and the Department of Environmental Protection and culminates in a presentation to the Mayor of New York City.

Using data storytelling techniques, we examine over 3.3 million complaints and propose interventions to improve the quality of life for NYC residents.

## Objectives

- **Descriptive Insights**: Explore the data for trends and patterns.
- **Predictive Insights**: Anticipate future complaint trends without intervention.
- **Actionable Recommendations**: Propose solutions for major noise issues.
- **Data Storytelling**: Present findings in a digestible, non-technical format.

## Deliverables

1. **Descriptive Analysis**: Charts, maps, and visuals showing trends by borough, time, and noise type.
2. **Predictive Insights**: Scenarios of complaint trends with and without action.
3. **Recommendations**: Targeted solutions for high-complaint areas, agencies, and sources.
4. **Presentation**: A PowerPoint slide deck summarizing the findings and recommendations.

## Data Source

The project utilizes the NYC Open Data 311 Service Requests database:
[311 Service Requests from 2010 to Present](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)

## Repository Structure

```
NYC-Noise-Complaints-Analysis/
│
│
├── notebooks/
│   └── analysis_notebook.ipynb
│
├── presentation/
│   ├── NYC_Noise_Complaints_Analysis_Presentation.pptx
│   └── README.md
│
├── media/
│   ├── final_meeting_recording.mp4
│
├── README.md
└── LICENSE
```

### Folders

- **`data/`**: Link to the source database and relevant documentation.
- **`notebooks/`**: Includes the Jupyter notebook used for analysis.
- **`presentation/`**: The final presentation delivered to the Mayor.
- **`media/`**: Supporting media such as meeting recordings.
- **Root**: Contains this README and an optional license.

## Key Insights

- Noise complaints are concentrated in specific boroughs and during peak hours.
- Major sources of noise complaints include construction, loud neighbors, and car horns.
- Predictive analysis indicates complaint levels will rise without intervention.

## Tools and Technologies

- **Data Analysis**: Python, Pandas, Matplotlib, Seaborn
- **Visualization**: PowerPoint, QGIS and Tableau for maps
- **Database**: NYC Open Data (311 Service Requests)

## Getting Started

### Prerequisites

- Install Python (3.7 or higher)
- Install Jupyter Notebook
- Required Python libraries: `pandas`, `matplotlib`, `seaborn`

### Running the Analysis

1. Clone the repository:
   ```bash
   git clone https://github.com/Nikhil-Doye/NYC-Noise-Complaints-Analysis.git
   ```
2. Navigate to the `notebooks/` directory.
3. Open and run the `analysis_notebook.ipynb`.

### Viewing the Presentation

The final presentation can be found in the `presentation/` folder as a `.pptx` file.

## Recommendations

Based on the analysis:

1. Target interventions in boroughs with the highest complaints.
2. Focus on peak hours for enforcement and resources.
3. Address major sources such as construction and residential noise.

## License

This project is licensed under [MIT License](LICENSE).

## Contributing

Contributions are welcome. Please create a pull request or raise an issue for any suggestions or improvements.
