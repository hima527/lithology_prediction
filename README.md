# lithology_prediction

# Lithology Identification Using Well-Log Data

## Overview

Lithology identification is an important part of formation evaluation in the petroleum industry. Understanding the types of rocks present in subsurface formations helps in evaluating reservoir characteristics and interpreting geological conditions.

This project uses well-log measurements and Python-based data analysis to identify lithology patterns and classify subsurface formations based on their logging responses.

## Objectives

- Analyze well-log measurements to understand variations in subsurface formations.
- Identify relationships between logging responses and lithological characteristics.
- Develop a data-driven approach for lithology identification.
- Visualize well-log data to support formation evaluation.

## Tools and Technologies

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib
- **Environment:** Google Colab

## Well-Log Data

The project uses measurements commonly associated with subsurface formation evaluation, including:

- **Gamma Ray (GR):** Helps distinguish shale-rich formations from cleaner formations.
- **Bulk Density (RHOB):** Provides information about formation density and supports porosity estimation.
- **Neutron Porosity (NPHI):** Provides an indication of formation porosity.
- **Resistivity (RDEP):** Helps evaluate formation electrical properties and fluid-bearing characteristics.
- **Photoelectric Factor (PEF):** Provides additional information useful for distinguishing mineral composition.
- **Sonic Travel Time (DTC):** Provides information about acoustic properties of the formation.
- **Caliper (CALI):** Indicates borehole diameter and helps assess borehole conditions.

The exact features used depend on the columns available in the input dataset.

## Methodology

1. **Data Preparation:** Load the well-log dataset and examine its structure, available measurements and missing values.
2. **Data Exploration:** Analyze logging measurements to understand their variations and relationships with lithology.
3. **Lithology Identification:** Use the available well-log features to develop a data-driven lithology classification workflow.
4. **Model Evaluation:** Examine the classification results to understand how well the approach distinguishes between lithology categories.
5. **Visualization:** Present relevant data patterns and results to support interpretation of subsurface formations.

## Applications

- Preliminary lithology identification from well-log measurements.
- Supporting formation evaluation workflows.
- Understanding relationships between petrophysical measurements and rock types.
- Demonstrating the application of Python and data analysis to petroleum engineering problems.

## Limitations

- The results depend on the quality, completeness and representativeness of the available well-log data.
- Similar lithologies may exhibit overlapping logging responses.
- The results should be interpreted alongside geological knowledge and other available formation-evaluation data.
- Predictions from a data-driven approach should not be treated as a substitute for expert geological interpretation.

## Future Scope

- Extend the analysis to additional wells and formations.
- Compare predicted lithology with independently verified geological information.
- Incorporate additional well-log measurements where available.
- Improve visualization and interpretation of depth-wise lithology variations.

## Conclusion

This project demonstrates how well-log measurements and Python-based data analysis can be applied to lithology identification. It connects computational techniques with petroleum engineering concepts and provides a foundation for further work in formation evaluation and subsurface characterization.
