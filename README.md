# Uncertainty Propagation Calculator for Spreadsheets

This project provides an Uncertainty Propagation Calculator, a tool that allows users to input an equation formatted in Python and returns the equation for uncertainty propagation. The result is provided in two formats:

    Spreadsheet-compatible format: Ideal for use in tools like Excel or Google Sheets.
    LaTeX format: For easy integration into scientific documents and reports.

Features

    Input any mathematical equation using Python-like syntax.
    Automatically generate the corresponding uncertainty propagation formula.
    Output the result in two formats:
        Spreadsheet-friendly format: Designed for use in Excel, Google Sheets, or other spreadsheet applications.
        LaTeX format: Suitable for professional scientific documentation.

Example Usage

    Input equation: I * R
    Variables: I, R

Output:

    Spreadsheet format: SQRT(((R) * inc_I)^2 + ((I) * inc_R)^2)

LaTeX format:

<pre xml:lang="latex">\sqrt{{\left(\left( R\right)\cdot σ\_I\right)}^{2}+{\left(\left( I\right)\cdot σ\_R\right)}^{2}}</pre>

# Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open a GitHub issue or submit a pull request.

# License

This project is licensed under the MIT License. See the LICENSE file for more details.
