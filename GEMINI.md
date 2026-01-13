# Gemini Project: World Travel Planner

## Directory Overview

This directory is a personal travel planner for organizing a round-the-world trip. It uses Markdown files to document and track all aspects of the journey.

## Planning Process & Status Management

A structured workflow is used to develop the plan for each destination. The status of each document is tracked within the file itself.

### Status Tracking

Each file within a destination directory (e.g., `destinations/Japan/`) must begin with a status line to track its progress. The available statuses are:
*   `**状态**: 草稿` (Draft): The file has been created but planning has not seriously begun.
*   `**状态**: 编制中` (In Progress): The file is actively being researched and written.
*   `**状态**: 已完成` (Completed): The file's planning is considered complete for the current stage.

### Planning Workflow

The planning for each destination follows an 8-step process, which corresponds to the files in the destination's directory.

1.  **Step 1: Preliminary Research**: Handle administrative prep work.
    *   `0_visa_legal.md`: Research visa requirements.
    *   `0_financial_services.md`: Look into local currency, banking, and payment methods.
    *   `0_communications.md`: Check out SIM cards and local communication options.
2.  **Step 2: Transportation Research**: Research international and local transportation methods.
    *   `2_international_transportation.md`: Research international round-trip transportation methods.
    
3.  **Step 3: Exploration Research**: List all potential points of interest.
    *   `1_attractions.md`: List sights, museums, parks, etc.
    *   `1_lodging_food.md`: Research notable restaurants, local delicacies, and potential lodging options.
    *   `1_local_transportation.md`: Research local transport options within the destination.
4.  **Step 4: Provider Research**: Find companies that will be used.
    *   `3_projects_providers.md`: List potential tour operators, rental agencies, etc.
5.  **Step 5: Note Compilation**: Consolidate important tips and warnings.
    *   `4_notes.md`: Write down miscellaneous notes, cultural etiquette, and things to watch out for.
6.  **Step 6: Itinerary Formulation**: Create a day-by-day schedule.
    *   `5_itinerary.md`: Build the actual itinerary.
7.  **Step 7: Budgeting**: Estimate all costs.
    *   `6_budget.md`: Create a detailed budget based on the itinerary and other research.
8.  **Step 8: Country-level Summary**: Update the destination's main `README`.
    *   `README.md`: Write a high-level summary of the plan for the country.
9.  **Step 9: Continent-level Summary**: After all countries in a region are planned, update the main overview document.
    *   `global_plan/*_trip_overview.md`: Update the main trip overview with final dates and summaries.

## File Structure

The project is organized into two main sections:

*   **`global_plan/`**: Contains master plans for the entire trip, broken down by region.
*   **`destinations/`**: Holds detailed plans for each destination. Based on the workflow, a standardized structure for each destination (e.g., `destinations/Japan/`) is as follows:
    *   `README.md`: (Step 7) An overview of the destination.
    *   `0_visa_legal.md`: (Step 1) Destination-specific visa and legal information.
    *   `0_financial_services.md`: (Step 1) Details on money and banking.
    *   `0_communications.md`: (Step 1) Details on local telecoms.

    *   `1_attractions.md`: (Step 2) Notes on sights and activities.
    *   `1_lodging_food.md`: (Step 2) Plans for accommodation and dining.
    *   `1_local_transportation.md`: (Implicit in Step 5) Information on flights, local transport, etc.
    
    *   `3_projects_providers.md`: (Step 3) Information on service providers (tours, rentals). **(New)**

    *   `4_notes.md`: (Step 4) Miscellaneous notes and tips.
    
    *   `5_itinerary.md`: (Step 5) A detailed day-by-day itinerary.

    *   `6_budget.md`: (Step 6) A specific budget for that destination.


*   **`README.md`**: The main project README, written in Chinese, explaining the structure and also containing high-level overviews of the trip.

## Usage

This directory is a living document. The user will populate and update the Markdown files as they plan and execute their world trip, following the workflow outlined above.