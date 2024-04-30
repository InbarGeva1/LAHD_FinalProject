## Dataset
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
- **LEVERAGE** (`float64`): The amount of public and private funds leveraged for the project.
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


### Target Variable and Data Type
- **LAHD FUNDED #** (`float64`): The LAHD loan amount awarded for the project.

### Other Terms
**Supportive housing** generally refers to housing that is paired with supportive services, such as mental health services, substance abuse treatment, case management, and other supportive services, to help residents maintain their housing stability and improve their overall well-being. This type of housing is often targeted towards individuals or families who are experiencing homelessness, have disabilities, or have other special needs.

## Metadata

- **Source**: Data obtained from Data.gov (Feb 2024) [https://catalog.data.gov/dataset/hcidla-affordable-housing-projects-list-2003-to-present](https://data.lacity.org/Housing-and-Real-Estate/LAHD-Affordable-Housing-Projects-List-2003-to-Pres/mymu-zi3s/about_data)
- **Owner**: Ella Foster, Inbar Geva, Lilly Fsahaye
- **Last Updated**: May 2nd, 2024
