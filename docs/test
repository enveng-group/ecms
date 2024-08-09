## 5. Use Case Analysis

### Use Case Diagram
Include a use case diagram to illustrate the interactions between users and the system.

# Use Case Diagram for Environmental Compliance Management System (ECMS)

```mermaid
%% Use Case Diagram for Environmental Compliance Management System (ECMS)
%% Define actors and use cases

%% Actors
actor EnvironmentalComplianceOfficer as ECO
actor RegulatoryBody as RB
actor CompanyManagement as CM
actor ITDepartment as ITD
actor EndUser as EU
actor ExternalAuditor as EA

%% Use Cases
usecase RTMonitoringAlerts as "Real-Time Monitoring and Alerts"
usecase GeospatialAnalysis as "Geospatial Data Visualization"
usecase ReportingDashboard as "Reporting and Dashboard Functionality"
usecase UserManagement as "User Management"
usecase DataImportExport as "Data Import and Export"

%% Relationships
ECO --> RTMonitoringAlerts
ECO --> GeospatialAnalysis
ECO --> ReportingDashboard

RB --> ReportingDashboard

CM --> ReportingDashboard

ITD --> RTMonitoringAlerts
ITD --> UserManagement
ITD --> DataImportExport

EU --> RTMonitoringAlerts
EU --> ReportingDashboard

EA --> ReportingDashboard

%% Non-Functional Requirements (as notes)
note right of RTMonitoringAlerts
    - Security
    - Scalability
    - Performance
    - Reliability
    - Usability
    - Compatibility
end note
