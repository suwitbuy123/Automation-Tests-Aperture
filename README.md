# Automation-Tests-Aperture

Automation testing project covering API and UI tests for the Aperture assignment. 

## Project Overview

This repository contains two projects:

- **API Testing**: Automated API tests for endpoints provided by FakeStoreAPI.
- **UI Testing**: Automated UI tests for Sauce Demo using Selenium WebDriver with C#.

## Requirements

Ensure you have the following installed:

- .NET SDK: Version 9.0 or above.
- Google Chrome: Latest version.
- ChromeDriver: Matching the installed Google Chrome version.
- Git: For version control.
- Visual Studio: (Optional) For easier debugging and running tests.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/suwitbuy123/Automation-Tests-Aperture.git
cd Automation-Tests-Aperture
```
### 2. Install Dependencies
```bash
dotnet restore
```
### 3. Build the Project
```bash
dotnet build
```

## Running the Tests

### 1. Run API Tests
To execute the API tests, use the following command:
```bash
dotnet test API_Tests/API_Tests.csproj --no-build --verbosity normal
```
### 2. Run UI Tests
To execute the UI tests, use the following command:
```bash
dotnet test UI_Tests/UI_Tests.csproj --no-build --verbosity normal
```
## Contact

For any questions or issues, feel free to:

- Raise a GitHub issue in this repository.
- Contact the repository owner directly.


