# CoordCheck for ArcGIS Pro

**CoordCheck** is an ArcGIS Pro add-in designed for coordinate quality assurance and quality control (QA/QC) in point layers, tables, and Excel files, while preserving the original data without modification.

## Coordinate Quality Checks

- Detect missing or invalid coordinates.
- Identify exact duplicate coordinates.
- Detect potentially swapped X/Y coordinate values.
- Identify points located outside the Area of Interest (AOI).
- Support DD, DDM, and DMS coordinate formats, including mixed formats.
- Process multiple Excel worksheets in a single run.
- Export QA/QC results to a Feature Class, Excel, or PDF.

## Installation and Usage

1. Go to **Releases** and download version **v2.0.15**.
2. Open `CoordCheck2.0.15` and click **Install Add-In**.
3. Launch ArcGIS Pro and navigate to **Data Quality → CoordCheck**.
4. Select the input data, configure the required settings, and run the tool.

## Compatibility and Requirements

- **Target ArcGIS Pro versions:** 3.3 to 3.7 on Windows.
- **Minimum ArcGIS Pro version:** 3.3.
- **Framework:** .NET 8.
- **Add-in version:** CoordCheck 2.0.13.

*The add-in's compatibility configuration has been verified. Full functionality has not been tested on every targeted ArcGIS Pro version.*

## Feedback and Support

To report issues or suggest improvements, please open a GitHub **Issue** and include your ArcGIS Pro version, input data type, and steps to reproduce the problem.

