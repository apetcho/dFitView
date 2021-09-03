# FitView
A Simple Application for fitting data and reporting fit result.

# Architecture of FitView
## Core
- lmfit
- pandas
- scipy
- matplotlib
- seaborn
- Interface to the core dependencies
    * Load data
    * Process data
    * Select and configure model
    * Run fitting algorim
    * Report result

## Widget
- MainWindow
    * ConfigPanel
    * PlotPanel
    * ReportPanel

## Actions
- LoadData
- Select model
- Configure Model
    * Configure Parameters
    * Choose Minimization Methods
    * Apply, Reset, Close
- Save ModelResult
- Load ModelResult
- Save FitResult
- Load FitResult
- Advanced Features
- Configure Output
    * Report Setup
    * Plot Setup
- MenuBar
    * File
    * Actions
    * Fit
    * Help
        - About
        - Documentation
        - Release Notes

- Export Result
    - save figure
    - save figure as ...
    - save report
    - save report as ...