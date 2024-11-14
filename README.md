![alt quicktext](https://www.quicktext.im/themes/quicktext/assets/dist/images/logo.svg 'Quicktext console project')

![npm type definitions](https://img.shields.io/npm/types/typescript)

## Project: **Minimalistic Room Browsing Demo with Testing**

#### Objective

Create a simple room browsing application where users can view a list of rooms. This test is focused on setting up the front-end and back-end, connecting them, displaying data, and implementing unit tests to confirm your familiarity with TypeScript, React, Next.js, NestJS, and Git.

#### Requirements

1. **Tech Stack**:
    - **TypeScript** for all code
    - **Back-end**: NestJS (with utils of your choice if needed).
    - **Front-end**: Next.js and React (with a UI package of your choice if needed).
    - **Git**: Use Git for version control, commit each step separately, and push the code to a GitHub repository to share.

2. **Main Feature**:
    - **Room Browsing**:
        - Display a list of rooms with basic details (e.g., room type, price, and availability status).
        - Seed the back-end with dummy room data from file [rooms.json](./rooms.json) that the front-end can retrieve and display.
        - Show the rooms on a single page with simple, clean layout styling.

   Here’s an example JSON object for a room, covering essential details:

   ```json
   {
     "id": 1,
     "name": "Deluxe Suite",
     "type": "Suite",
     "price": 150,
     "currency": "USD",
     "availability": true,
     "description": "A spacious suite with a king-size bed, private balcony, and sea view.",
     "features": {
       "bedType": "King",
       "maxOccupancy": 3,
       "wifi": true,
       "airConditioning": true,
       "tv": true,
       "minibar": true
     },
     "images": [
       "https://example.com/images/room1-1.jpg",
       "https://example.com/images/room1-2.jpg"
     ]
   }
   ```

   #### Explanation of Fields
    - **id**: Unique identifier for the room.
    - **name**: Name or title of the room type.
    - **type**: Category of room (e.g., Suite, Deluxe, Standard).
    - **price**: Nightly rate for the room.
    - **currency**: Currency code for the price.
    - **availability**: Boolean indicating if the room is available.
    - **description**: Brief description of the room.
    - **features**: Object listing specific room features.
        - **bedType**: Type of bed.
        - **maxOccupancy**: Maximum number of occupants allowed.
        - **wifi**, **airConditioning**, **tv**, **minibar**: Boolean fields indicating amenities.
    - **images**: Array of image URLs for the room.

3. **Testing Requirements**:
    - Implement unit tests for both front-end and back-end.
    - Aim for acceptable coverage (50% is okay, 80% is good).
    - **Back-end tests** (NestJS): Test the services, controllers, and API endpoint for fetching room data.
    - **Front-end tests** (Next.js/React): Test the components responsible for displaying the room list.

4. **Technical Requirements**:
    - **API**: Use NestJS to create an endpoint that retrieves room data.
    - **Frontend**: Use Next.js to build a page that fetches and displays room data from the back-end.
    - **TypeScript**: Ensure all code is written in TypeScript.
    - **Git**: Commit each small step separately to clearly document your approach.

5. **Bonus**:
    - Add basic CSS styling for a user-friendly layout.
    - Add a pagination feature to allow users to go through rooms 5 by 5.
    - Add a search and/or filter feature to allow users to narrow down the room list by type or price.
    - **Monorepo**: Structure the project as a monorepo to manage both front-end and back-end code in a single repository.
    - **Docker/Kubernetes Compatibility**: Make the project Docker-compatible, with Dockerfiles for both the front-end and back-end, and provide a basic setup for Kubernetes if possible.

#### Important Notes

- **Simplicity**: A solution with minimal code that meets requirements in a faster timeframe is preferred over a complex solution. Focus on delivering a clean, functional example.
- **Committing**: Commit frequently with clear, descriptive messages for each step, from setup to testing. This will provide insight into your approach and problem-solving process.
- **Documentation**: This task will also help us prepare any onboarding resources or training that may be useful to you once hired. Please note any areas in which additional support might be helpful.

#### Deliverables

1. **GitHub Repository**: Push the project to a GitHub repository and provide a link for review, or use a fork from this repo and PR us.
2. **ReadMe Documentation**: Include setup instructions, a description of the project, and a note on your testing approach and coverage.

#### Evaluation Criteria

- **Code Quality**: Assess TypeScript usage, code organization, and adherence to best practices (naming, linting, etc.).
- **Correctness**: Verify that the room browsing feature works as expected.
- **Testing**: Confirm that unit tests are implemented with acceptable coverage and cover critical functionality.
- **UI/UX**: Ensure the UI is simple, clear, and user-friendly.
- **Git Usage**: Review commit history for clear, incremental development and descriptive messages.
- **Bonus**: Evaluate Docker/Kubernetes compatibility, monorepo structure, and additional features if implemented.
