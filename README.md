# DBLP Author Publications Analysis

## Project Overview
This project utilizes the DBLP API to retrieve and analyze publication data for Computer Science authors. It involves querying the API for specific authors and visualizing their publication data using various plots such as bar plots, scatter plots, line plots, and pie charts. The application also handles pagination and does not use any third-party packages.

## Data Retrieval
Data is retrieved from the DBLP API for the specified authors using pagination to handle large datasets. The publications are extracted and stored in a pandas DataFrame.

## Data Analysis and Visualization
The analysis includes grouping and plotting publication data by year, type, and access type, as well as calculating and visualizing average page counts.

- **Publications by Year**: A bar plot is created to show the number of publications per year for each author. The data is grouped by year and sorted in ascending order.

- **Publication Types Distribution**: A pie chart is used to show the distribution of publication types. The data is grouped by type to calculate the number of publications for each type.

- **Open vs Closed Access Publications by Year**: A scatter plot is generated to display the number of open vs closed access publications per year. The data is filtered to exclude entries with unavailable access information and grouped by year and access type.

- **Average Page Count by Type**: A bar plot is created to show the average page count per publication type. The page counts are calculated from the pages data, and the average is computed for each type.

- **Comparative Analysis for Multiple Authors**: Bar plots are used to compare the number of publications and publication types for two authors. The data for each author is grouped by year and type and plotted side by side for comparison.

- **Publications by Venue**: A bubble chart is created to show the number of publications per venue for each author. The data is grouped by venue, and the size of the bubbles represents the number of publications.

- **Publications by Type, Year, and Author**: A line plot is used to show the number of publications by type, year, and author. The data is grouped by year, type, and author, and a combined column for author and type is created for color differentiation in the plot.

- **Open vs Closed Access Publications by Year and Author**: A line plot is generated to compare open vs closed access publications for multiple authors. The data is grouped by author, year, and access type and plotted with different line dash patterns for access types.

- **Average Page Counts by Type and Author**: A bar plot is created to compare the average page counts by publication type for multiple authors. The average page counts are calculated and grouped by type and author, and the results are plotted side by side for comparison.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Feedback
Your thoughts and feedback are welcome! Please feel free to open an issue or contact me directly at jimiatro@hotmail.com.
