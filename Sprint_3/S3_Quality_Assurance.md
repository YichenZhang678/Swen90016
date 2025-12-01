# 🚀 Quality Assurance Strategy  

This document outlines the **Quality Assurance (QA) Strategy** for the **Urban Tree Explorer** project, ensuring that testing activities are planned, executed, and documented as part of every sprint.  


## 🌲 **Urban Tree Explorer QA Documentation**  

### 📌 Acceptance Criteria for User Stories

✅  **Park Location Map:**
1. Interactive map shows parks near Melbourne Connect
2. Users can rate parks on 1-10 scale
3. Users can submit new location markers with photos and descriptions
4. Filter toggle for user-submitted markers
5. Detailed information for specified parks (University Square, Lincoln Square, Argyle Square, Carlton Gardens)
6. Minimum 3 photos per specified location
7. YouTube video embeddings for at least 2 locations

✅ **Walking Itinerary Map:**
1. Interactive map shows predetermined route through 11 locations
2. Direction display for complete itinerary
3. Rating system for each stop
4. Tree heatmap visualization around walking path
5. Clear distinction between itinerary markers and heatmap
6.  Accurate route display between all specified locations


### 📌 Test Cases


| **Test ID** | **User Story** | **Scenario (BDD Syntax)** | **Test Result** | **Tested By** | **Test Date** | **Comments** |
|------------|---------------|--------------------------|--------------|------------|------------|------------|
| TEST-207 | Park Rating | **Given** a user visits a park location, **When** they submit a rating from 1-10, **Then** the average rating should update accordingly | ✅ Pass | Linxuan Han | 2025-05-24 | Rating system functioning properly |
| TEST-208 | Location Submission | **Given** a user submits a new park location with photos, **When** they complete the submission form, **Then** the marker should appear with proper validation | ✅ Pass | Saite Guo | 2025-05-24 | Photo upload and marker placement working |
| TEST-209 | Walking Itinerary | **Given** a user views the walking route, **When** they click on any of the 11 locations, **Then** proper directions should display | ✅ Pass | Jiarui Ni | 2025-05-24 | Route navigation displaying correctly |
| TEST-210 | Tree Heatmap | **Given** the walking path is displayed, **When** the heatmap is toggled on, **Then** tree density should be clearly visible without obscuring route markers | ✅ Pass | Linxuan Han | 2025-05-24 | Heatmap visualization clear and accurate |
| TEST-211 | Video Integration | **Given** a user visits a park detail page, **When** they click on embedded YouTube videos, **Then** videos should play properly | ✅ Pass | Saite Guo | 2025-05-24 | Video embedding working as expected |

