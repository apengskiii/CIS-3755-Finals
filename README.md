#Automation Risk
##Project Description
This project visualizes automation risk across 291 U.S. occupations using data from Frey and Osborne (2017), along with Autor and Dorn (2013) for job routineness and Caines et al. (2017) for job complexity. The combined dataset covers 96.3% of the U.S. workforce as of 2016. The project includes three visualizations. A bar chart showing the 50 highest and lowest risk occupations, a scatter plot comparing routineness and complexity, and a searchable table containing all 291 occupations.

##Installation and Setup
1. Download and extract the zipped folder
2. Ensure index.html and automation_data.csv are in the same folder
3. Run a local server using python -m http.server 8000
4. Open http://localhost:8000/ in your browser

##Lessons Learned
- Worked with CSV data in D3 and handled parsing issues
- Built multiple visualization types from one dataset
- Used scales, axes, and tooltips effectively
= Handled character encoding issues with HTML entities
- Learned how combining datasets reveals patterns not visible in a single source
