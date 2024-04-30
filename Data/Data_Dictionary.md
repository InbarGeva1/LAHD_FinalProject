## Dataset
LAHD Affordable Housing Projects List (2003 to Present)

## Data Attributes

### Features and Data Types

- **APN** (`int64`): Assessor Parcel Number.
- **PROJECT NUMBER** (`object`): Unique identifier for each project.
- **NAME** (`object`): Name of the affordable housing project.
- **DEVELOPMENT STAGE** (`object`): Current stage of development for the project.
- **CONSTRUCTION TYPE** (`object`): Type of construction used for the project.
- **SITE ADDRESS** (`object`): Address of the project site.
- **SITE COUNCIL DISTRICT** (`int64`): Council district associated with the project site.
- **SITE #** (`int64`): Unique identifier for each site within the project.
- **SITE COMMUNITY** (`object`): Community where the project site is located.
- **SITE UNITS** (`int64`): Number of affordable housing units at the project site.
- **PROJECT TOTAL UNITS** (`int64`): Total number of units in the entire project.
- **HOUSING TYPE** (`object`): Type of housing provided by the project.
- **SUPPORTIVE HOUSING** (`object`): Indicates whether the housing is supportive housing or not.
- **SH UNITS PER SITE** (`int64`): Number of supportive housing units at the project site.
- **DATE FUNDED** (`object`): Date when the project was funded.
- **LEVERAGE** (`float64`): Ratio of funds leveraged for the project.
- **TAX EXEMPT CONDUIT BOND** (`int64`): Indicates if tax-exempt conduit bond was used for financing.
- **TDC** (`float64`): Total Development Cost of the project.
- **IN-SERVICE DATE** (`object`): Date when the project was completed and ready for occupancy.
- **DEVELOPER** (`object`): Entity responsible for developing the project.
- **MANAGEMENT COMPANY #** (`object`): Unique identifier for the management company.
- **CONTACT PHONE** (`object`): Contact phone number for the project.
- **PHOTO** (`object`): Link to a photo of the project.
- **JOBS** (`float64`): Number of jobs created by the project.
- **PROJECT SUMMARY URL** (`object`): URL link to the project summary.
- **CONTRACT NUMBERS** (`object`): Contract numbers associated with the project.
- **DATE STAMP** (`object`): Date when the data was last updated.
- **SITE LONGITUDE** (`float64`): Longitude coordinate of the project site.
- **SITE LATITUDE** (`float64`): Latitude coordinate of the project site.
- **GPS_COORDS ON MAP** (`object`): Coordinates of the project site on a map.


### Target Variable and Data Type
- **LAHD FUNDED #** (`float64`): Indicates whether the project is funded by the Los Angeles Housing Department (LAHD) and the corresponding funding amount.

### Other Terms
**Supportive housing** generally refers to housing that is paired with supportive services, such as mental health services, substance abuse treatment, case management, and other supportive services, to help residents maintain their housing stability and improve their overall well-being. This type of housing is often targeted towards individuals or families who are experiencing homelessness, have disabilities, or have other special needs.

## Metadata

- **Source**: Data obtained from Data.gov (Feb 2024) https://catalog.data.gov/dataset/hcidla-affordable-housing-projects-list-2003-to-present
- **Owner**: Ella Foster, Inbar Geva, Lilly Fsahaye
- **Last Updated**: May 2nd, 2024
