## Dataset #1
LAHD Affordable Housing Projects List (2003 to Present)

## Data Attributes

### Features and Data Types

- **APN** (`int64`): Assessor Parcel Number.
- **PROJECT NUMBER** (`object`): Housing Information Management System (HIMS) Project Number.
- **NAME** (`object`): Name of the project.
- **DEVELOPMENT STAGE** (`object`): Current stage of development for the project.
- **CONSTRUCTION TYPE** (`object`): The type of construction, typically "New" or "Rehab".
- **SITE ADDRESS** (`object`): Address of the project site.
- **SITE COUNCIL DISTRICT** (`int64`): Council district associated with the project site.
- **SITE #** (`int64`): The site number of the project site. Single site project will always display 1.
- **SITE COMMUNITY** (`object`): Community where the project site is located.
- **SITE UNITS** (`int64`): Total number of units per site.
- **PROJECT TOTAL UNITS** (`int64`): Total units per project.
- **HOUSING TYPE** (`object`): The population served by the project.
- **SUPPORTIVE HOUSING** (`object`): Yes/No for total special needs if a site has at least one supportive housing unit.
- **SH UNITS PER SITE** (`int64`): Special Needs per homeless units per site.
- **DATE FUNDED** (`object`): Date when the project was funded.
- **LAHD FUNDED #** (`float64`): The LAHD loan amount awarded for the project.
- **TAX EXEMPT CONDUIT BOND** (`int64`): The amount of tax exempt conduit bond issued for the project.
- **TDC** (`float64`): Total Development Cost.
- **IN-SERVICE DATE** (`object`): The year when the project is ready for occupany.
- **DEVELOPER** (`object`): The name of the developer of the project.
- **MANAGEMENT COMPANY #** (`object`): The name of the management company.
- **CONTACT PHONE** (`object`): Contact phone number of the management company.
- **PHOTO** (`object`): Link to a photo of the project.
- **JOBS** (`float64`): The amount of jobs supported.
- **PROJECT SUMMARY URL** (`object`): Printable project summary report.
- **CONTRACT NUMBERS** (`object`): Reference to a city contract of each project in plain text format.
- **DATE STAMP** (`object`): The time and date when the information is updated.
- **SITE LONGITUDE** (`float64`): Longitude coordinate of the project site.
- **SITE LATITUDE** (`float64`): Latitude coordinate of the project site.
- **GPS_COORDS ON MAP** (`object`): GPS coordinates of the project site address.

-------------------------------------------------------------------------------------------------------

## Dataset #2
Median Household Income by Council Districts

## Data Attributes

### Features and Data Types

- **CATEGORY** (`object`): Broad classification of the data.
- **INDICATOR** (`object`): Specific metric or measure within a category.
- **SUB_INDICATOR** (`object`): Further detail within an indicator.
- **LOCALITY** (`object`): Geographical area or region.
- **GENDER** (`object`): Gender category, if applicable.
- **COUNCIL_DISTRICT** (`int64`): Administrative division within a municipality.
- **CALENDAR_YEAR** (`int64`): Year of the data.
- **AS_OF_DATE** (`object`): Date when the data was recorded.
- **UNIT_OF_MEASURE** (`object`): Standard unit for the data values.
- **2017_VALUE** (`float64`): Data value for the year 2017.
- **2024_VALUE** (`float64`): Data value for the year 2024.

-------------------------------------------------------------------------------------------------------

### Target Variable and Data Type
- **LEVERAGE** (`float64`): The amount of public and private funds leveraged for the project.

### Other Terms
**Supportive housing** generally refers to housing that is paired with supportive services, such as mental health services, substance abuse treatment, case management, and other supportive services, to help residents maintain their housing stability and improve their overall well-being. This type of housing is often targeted towards individuals or families who are experiencing homelessness, have disabilities, or have other special needs.

## Metadata

**Source**: The first dataset obtained from Data.gov (Feb 2024) [https://catalog.data.gov/dataset/hcidla-affordable-housing-projects-list-2003-to-present](https://data.lacity.org/Housing-and-Real-Estate/LAHD-Affordable-Housing-Projects-List-2003-to-Pres/mymu-zi3s/about_data)

The second dataset obtained from lacity.org [the Median Household Income by Council Districts](https://controllerdata.lacity.org/dataset/Median-Household-Income-by-Council-Districts/khbi-qsyb)

- **Owner**: Ella Foster, Inbar Geva, Lilly Fsahaye
- **Last Updated**: May 2nd, 2024
