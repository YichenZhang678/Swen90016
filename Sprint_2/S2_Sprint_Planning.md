# 🌲 Sprint Planning - Urban Tree Explorer (Sprint 1)

## Sprint Goal
Deliver a functioning MVP of an interactive map features with search/filtering capabilities for urban trees and creating a secure login system for user authentication.

## Selected User Stories

### User Story 1: Nearby Tree Search 
**As a** teaching team member, **I want to** search for trees within a specified distance of a location so I can find trees near me

### Acceptance Criteria:
- Interactive map shows at least 3000 trees
- Users can input location and distance in kilometers
- Default location is Melbourne Connect with 1km radius
- Clicking markers shows tree details
- - List of 10 nearest trees displays below map
Results update when search parameters change

### Estimation using Fibonacci Sequence
| Factor | Consideration |
|--------|--------------|
| Complexity | Medium - Built in functionality of WP Go Maps |
| Uncertainty | Medium - Integration with mapping APIs |
| Dependencies | High - Relies on accurate tree data and mapping service |
| Risk | Medium - Performance concerns with large dataset |
| **Estimated Story Points** | **7** (based on team discussion) |

### User Story 2: Tree Category Filtering

**As a** teaching team member, **I want to** filter trees by location type, genus, and age so I can find specific types of trees”

### Acceptance Criteria:
- Users can filter by Located in, Genus, and Age Description
- Filters can be used in any combination
- Trees of same genus show in same color
- Default location is Lincoln Square with 1km radius
- Default filters: Park and Ficus


### Estimation using Fibonacci Sequence
| Factor | Consideration |
|--------|--------------|
| Complexity | High - Multiple filter combinations and visual representation |
| Uncertainty | Medium - Data categorization accuracy |
| Dependencies | Medium - Relies on properly categorized tree data |
| Risk | Medium - Performance with multiple filter combinations |
| **Estimated Story Points** | **8** (based on team discussion) |

### User Story 3: Basic Authentication
**As a** platform user, **I want to**  securely log into the platform **so that** I can access the tree explorer features while ensuring unauthorized users cannot view our planning data.

### Acceptance Criteria:
- Basic WordPress authentication is configured
- Login page is customized for the application
- Successful login redirects to main site
- Non-logged in users redirected to login page

### Estimation using Fibonacci Sequence
| Factor | Consideration |
|--------|--------------|
| Complexity | Medium - Basic WordPress authentication configuration |
| Uncertainty | Low - Using standard WordPress functionality |
| Dependencies | Low - Built-in WordPress capabilities |
| Risk | Medium - Security considerations |
| **Estimated Story Points** | **3** (based on team discussion) |

## Sprint Backlog Tasks

### User Story 1: Nearby Tree Search
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Set up map interface page | Bojin Li | 4 |
| Create nearest trees list component | Saite Guo | 3 |
| Set default location/distance values | Saite Guo | 1 |
| Test search functionality | Saite Guo | 3 |

### User Story 2: Tree Category Filtering
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Implement category selection logic | Linxuan Han | 1 |
| Add color coding for genus | Saite Guo | 2 |
| Set up filter combination handling | Linxuan Han | 2 |
| Implement default filter values | Bojin Li | 1 |
| Create age description exclusion logic | Yichen Zhang | 1 |
| Test filter combinations | Yichen Zhang | 1 |
| Add legend for tree colors | Yichen Zhang | 2 |
| Implement filter reset functionality | Linxuan Han | 2 |

### User Story 3: Login System
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Implement authentication logic | Jiarui Ni | 1 |
| Set up error handling | Jiarui Ni | 1 |
| Add redirect functionality | Jiarui Ni | 2 |
| Test session management | Jiarui Ni | 1 |
| Create access restriction logic | Jiarui Ni | 1 |



## Commitment
The team commits to deliverying the MVP with all three user stories by the end of Sprint 2. 
