# QuanSolveAI

QuanSolve is an open source, AI-driven analytics platform tailored for researchers and students at all academic levels. It automates both quantitative and qualitative analyses by integrating data quality checks, statistical processing, geospatial mapping, and interactive visualizations—all within an intuitive web interface.

## Key Features

- **AI-Driven Insights:** Automatically suggests research indicators, questions, and interpretations using advanced NLP models.
- **Data Quality Checks:** Identifies duplicates, inconsistencies, and missing data to ensure robust datasets.
- **Statistical Analysis:** Provides descriptive statistics, trend analyses, and regression models.
- **GIS Mapping:** Visualizes datasets geographically to reveal spatial trends and hotspots.
- **Interactive Dashboards:** Combines graphs, charts, and maps for dynamic reporting.
- **Chatbot Assistance:** Guides users through data uploads, analysis creation, and results interpretation.

## Tech Stack

- **Frontend:**  
  - React.js (or Next.js for server-side rendering)  
  - Data visualization with Plotly.js, D3.js, and Leaflet.js for GIS mapping

- **Backend:**  
  - Python (Flask or Django) for building RESTful APIs  
  - Integration with OpenAI GPT for generating insights  
  - Data processing libraries such as Pandas, NumPy, and SciPy

- **Database:**  
  - PostgreSQL with the PostGIS extension for geospatial support

- **Cloud & Deployment:**  
  - Docker & Docker Compose for containerization  
  - AWS (EC2, RDS, S3) for scalable deployment  
  - Stripe API for subscription and payment management

## System Architecture

QuanSolve follows a modular architecture:

1. **Frontend:**  
   - A web interface for data upload, interactive dashboards, and chatbot interactions.
2. **Backend:**  
   - RESTful API endpoints handling data validation, AI insights, statistical and geospatial analysis.
3. **Database:**  
   - PostgreSQL stores user accounts, datasets, and analytics results.
4. **Middleware (Optional):**  
   - A Node.js-based API gateway can manage asynchronous tasks and request orchestration.
5. **Cloud Infrastructure:**  
   - Docker containers orchestrated on AWS with continuous integration pipelines.

## Installation

### Prerequisites

- Python 3.9+
- Node.js and npm (or yarn)
- PostgreSQL with PostGIS
- Docker & Docker Compose (for containerized deployment)

### Steps to Run Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/quansolve.git
   cd quansolve
