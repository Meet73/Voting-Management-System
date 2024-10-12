# Voting-Management-System

## Objective

The goal of this database is to store comprehensive details about voters, political parties, and candidates who compete in district-level elections within a given state of the country. It allows easy access to:
- Candidate and political party information.
- Voter details and their voting status.
- Volunteer and voting center details.

Additionally, the database will help:
- Calculate the total votes won by each political party.
- Determine the winning party in a given district based on area-wise vote counts.
- Identify which citizens voted in the election and those who did not.

## Description

The elections are conducted at the **district level** within the **state** of a country. Multiple political parties compete in these elections, each with a unique name, ID, symbol, and year of formation. Candidates can only participate if they are members of one of these political parties—independent participation is not allowed.

### Key Details:

- **Candidates**: Each political party can field one candidate per district. The candidate with the maximum votes wins the election in that district.
- **Areas**: Each district comprises various areas identified by an area code (such as a pin code). An area is part of a district located within a state and country. Each area has its own voting center where eligible citizens vote.
  
- **Voters**: Citizens aged 18 or older with a valid voter ID are eligible to vote. They are registered with their respective voting centers based on their area code. Voters are identified by their **Aadhar card** or **voter ID**, and the system tracks whether or not they have voted.
  
- **Volunteers**: Each voting center is managed by a team of citizen volunteers. Each volunteer has a unique volunteer ID, name, and salary.

### Election Outcome:

- The candidate with the maximum votes in a district wins the election for that district.
- The political party with the most elected candidates in a state becomes the ruling party of that state.
- The political party ruling the maximum number of states becomes the ruling party of the country.
