# TEA_Electrolyzer
Techno-Economic Analysis for Electrolyzers

# Steam Electrolyzer Tradespace Analysis

This project analyzes the tradespace of steam electrolyzers by considering various current density and resistance values. It also compares internal architectures with competitor data.

## Project Structure

- **CoLab Inputs - Steam Electrolyzer.xlsx:** Contains input data for current density and resistance.
- **External_Data.xlsx:** Contains competitor data.
- **combined_data.csv:** Output file containing the combined internal and competitor data.
- **steam_electrolyzer_analysis.ipynb:** Jupyter Notebook containing the code for analysis and visualization.

## Functionality

1. **Import Data:** Reads input data from Excel files.
2. **Cross-Join:** Creates all combinations of current density and resistance.
3. **Calculate OPEX:** Calculates operational expenditure values, including stack energy consumption.
4. **Competitor Data:** Reads and integrates competitor data.
5. **Tradespace Plotting:** Visualizes the tradespace using Plotly, highlighting internal architectures and competitor data.

## Requirements

- Python 3.x
- pandas
- numpy
- openpyxl
- plotly

To install these requirements, run:
bash !pip install pandas numpy openpyxl plotly==6.0.0

## Usage

1. Open the `steam_electrolyzer_analysis.ipynb` notebook in Google Colab.
2. Update the input file paths if necessary.
3. Run all cells to perform the analysis and generate visualizations.
4. Customize the code and visualizations as needed.

## Notes

- The code assumes that the input data is in a specific format.
- The calculated OPEX values are based on certain assumptions and may need adjustments.
- The tradespace visualizations can be customized with different colors, markers, and filters.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
