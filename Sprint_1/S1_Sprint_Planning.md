# 🌲 Sprint Planning - Urban Tree Explorer (Sprint 1)

## Sprint Goal
Deliver a functioning MVP of the Urban Tree Explorer with basic interactive map visualization capabilities and secure access control to demonstrate core functionality to the teaching team.

## Selected User Stories

### User Story 1: Basic Tree Map Visualization
**As a** teaching team member, **I want to** see visulized tree locations on a basic map **so that** I can get an overview of potential meetup locations.

### Acceptance Criteria:
- A simple map displays showing the Melbourne area
- Basic tree locations are plotted from the City of Melbourne dataset
- The map supports fundamental navigation (zoom, pan)
- The interface loads correctly on standard web browsers

### Estimation using Fibonacci Sequence
| Factor | Consideration |
|--------|--------------|
| Complexity | Medium - Requires basic geo-visualization setup |
| Uncertainty | Medium - Initial integration with WordPress |
| Dependencies | Medium - Relies on external dataset |
| Risk | Low - Simplified implementation for MVP |
| **Estimated Story Points** | **5** (based on team discussion) |

### User Story 2: Simple Tree Information Display
**As a** teaching team member, **I want to** see basic information about trees **so that** I can understand what data is available.

### Acceptance Criteria:
- Tree information is accessible in a simple list or table format
- Basic data (species, location) is displayed
- Information is readable and organized

### Estimation using Fibonacci Sequence
| Factor | Consideration |
|--------|--------------|
| Complexity | Low - Simple data display |
| Uncertainty | Low - Straightforward implementation |
| Dependencies | Low - Basic data processing |
| Risk | Low - Standard functionality |
| **Estimated Story Points** | **2** (based on team discussion) |

### User Story 3: Basic Authentication
**As a** platform user, **I want to**  securely log into the platform **so that** I can access the tree explorer features while ensuring unauthorized users cannot view our planning data.

### Acceptance Criteria:
- Basic WordPress authentication is configured
- User roles are set up for teaching staff
- Login page is customized for the application
- Basic access control is implemented

### Estimation using Fibonacci Sequence
| Factor | Consideration |
|--------|--------------|
| Complexity | Medium - Basic WordPress authentication configuration |
| Uncertainty | Low - Using standard WordPress functionality |
| Dependencies | Low - Built-in WordPress capabilities |
| Risk | Medium - Security considerations |
| **Estimated Story Points** | **3** (based on team discussion) |

## Sprint Backlog Tasks

### User Story 1: Basic Tree Map Visualization (5 points)
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Set up WordPress environment with basic mapping plug-in | Saite Guo | 3 |
| Create simplified database schema for core tree data | Saite Guo, Bojin Li| 5|
| Draft initial UI for the map page | Linxuan Han | 5 |
| Implement basic map visualization with tree locations | Bojin Li, Linxuan Han | 5 |

### User Story 2: Simple Tree Information Display (2 points)
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Daft basic information display format | Jiarui Ni | 2 |
| Extract and process core tree data | Jiarui Ni | 3 |
| Implement tree info display component | Yichen Zhang, Jiarui Ni | 5 |
| Test data display functionality | Yichen Zhang, Jiarui Ni | 3 |

### User Story 3: Basic Authentication (3 points)
| Task | Assigned To | Estimated Hours |
|------|------------|----------------|
| Configure WordPress basic user authentication | Saite Guo, Bojin Li | 5 |
| Set up user lables for teaching staff | Linxuan Han | 2 |
| Draft basic login page UI | Linxuan Han | 3 |
| Test functionality | All members | 3 |


## Commitment
The team commits to deliverying the MVP with all three user stories by the end of Sprint 1. The total estimated effort of 10 story points is realistic for our first sprint, focusing on establishing the core functionality needed to demonstrate the concept to stakeholders.