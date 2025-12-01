# 🌳 Groomed Product Backlog - Urban Tree Explorer 


| Use Case | User Story | Acceptance Criteria | Priority | Estimation (SP) | User Story Description | Dependencies | Notes |
|----------|-----------|---------------------|----------|-----------------|------------------------|--------------|-------|
| Interactive Tree Map | As a user, I want to view an interactive map showing Melbourne's tree locations, so that I can explore potential meetup spots. | **Given** I am on the main page, **When** I load the map, **Then** I should see tree markers accurately placed on the map. | Must-have | 18 | Basic map implementation with tree markers using City of Melbourne dataset. | Map API integration, Dataset integration | Focus on performance with large dataset |
| Basic Tree Information Display | As a user, I want to click on tree markers to see basic information, so that I can learn about specific trees. | **Given** I click on a tree marker, **When** the popup appears, **Then** I should see basic tree details. | Must-have | 13 | Simple popup display showing essential tree information. | Depends on map implementation | Keep initial info concise |
| Interactive Location-Based Tree Map | As a user, I want to view trees within a specific distance of my location so I can discover nearby urban trees | **Given** I am on the map page **When** the page loads **Then** I should see a map centered on Melbourne Connect with a 1km radius and tree markers.  | Must-have | 11 | Interactive map implementation centered on Melbourne Connect showing minimum 3000 trees with 1km default radius. | Map API integration, Dataset integration | Default location: Melbourne Connect, Default radius: 1km. Must use kilometer units |
| Nearby Trees List Results | As a user, I want to see a list of the 10 closest trees below the map after searching a location | **Given** I search a location **When** results are found **Then** I should see a list of the 10 nearest trees with relevant details displayed under the map | Must-have | 12 | Implementation of searchable location functionality and results list showing closest 10 trees with details | Map implementation | List must update based on search results |
| Park Rating System | As a PhD student, I want to rate parks on a 1-10 scale, so that I can share my experience and see average ratings from other users. | **Given** I am viewing a park marker, **When** I submit a rating, **Then** the system should update and display the new average rating. | Must-have | 16 | Implementation of rating system allowing users to rate parks and view average ratings. Includes database storage and real-time updates. | Map API integration, Database setup | Ensure rating system is user-friendly and prevents multiple ratings from same user |
| Walking Itinerary Tree Heatmap | As a PhD student, I want to see a heatmap of trees along the predetermined walking route, so that I can understand the amount of shade coverage during my walk. | **Given** I am viewing the walking itinerary map, **When** the map loads, **Then** I should see a heatmap visualization of trees around the walking path while maintaining clear visibility of the route markers. | Must-have | 12 | Implementation of tree heatmap visualization along predetermined walking route, integrating tree dataset with heatmap functionality. | Map API integration, Tree dataset integration, Walking route implementation | Ensure proper balance between heatmap visibility and route clarity |



## Definition of Done (DoD)
- Feature passes all acceptance criteria
- Code is reviewed and merged
- Documentation is complete
- Testing (unit, integration) passed
- 2FA security measures verified
- Performance requirements met
- User acceptance testing completed

## Additional Notes
- Total project duration: 6 weeks
- Available resources: 100-150 hours
- Platform: WordPress
- Primary data source: City of Melbourne urban tree dataset
- Each sprint is approximately 2 weeks long