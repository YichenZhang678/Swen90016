# 🚀 Quality Assurance Strategy  

This document outlines the **Quality Assurance (QA) Strategy** for the **Urban Tree Explorer** project, ensuring that testing activities are planned, executed, and documented as part of every sprint.  


## 🌲 **Urban Tree Explorer QA Documentation**  

### 📌 Acceptance Criteria for User Stories

✅ **Location-Based Search:**
1. Users can input a location and specify a search radius
2. System displays trees within the specified distance
3. Results are shown both on map and in list format

✅ **Tree Filtering:**
1. Users can filter trees by location type
2. Users can filter trees by genus
3. Users can filter trees by age
4. Multiple filters can be applied simultaneously

✅ **Secure Login:**
1. Users can log in with valid credentials
2. Invalid credentials are rejected
3. Unauthorized users cannot access tree data

### 📌 Test Cases

| **Test ID** | **User Story** | **Scenario (BDD Syntax)** | **Test Result** | **Tested By** | **Test Date** | **Comments** |
|------------|---------------|--------------------------|--------------|------------|------------|------------|
| TEST-201 | Location Search | **Given** a user inputs a location and 5km radius, **When** they execute the search, **Then** the system should display all trees within 5km of that location | ✅ Pass | Linxuan Han | 2024-03-15 | Map markers accurately displayed |
| TEST-202 | Tree Filtering | **Given** a user selects "Eucalyptus" genus and "Park" location type, **When** they apply the filters, **Then** only Eucalyptus trees in parks should be displayed | ✅ Pass | Linxuan Han | 2024-03-16 | Filter combination working correctly |
| TEST-203 | Secure Login | **Given** an unauthorized user attempts to access the platform, **When** they enter incorrect credentials, **Then** access should be denied with an appropriate error message | ✅ Pass | Jiarui Ni | 2024-03-14 | Security measures functioning as expected |
| TEST-204 | Location Search | **Given** a user searches within 1km of an empty area, **When** they execute the search, **Then** the system should return "No trees found" message | ✅ Pass | Saite Guo | 2024-03-15 | Edge case handled properly |
| TEST-206 | Secure Login | **Given** a logged-in user is inactive for 30 minutes, **When** they try to access protected features, **Then** they should be automatically logged out | ✅ Pass | Jiarui Ni | 2024-03-14 | Session timeout working correctly |

