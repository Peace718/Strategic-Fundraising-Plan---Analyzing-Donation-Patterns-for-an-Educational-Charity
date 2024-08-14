# Strategic Fundraising Plan - Analyzing Donation Patterns for an Educational Charity

![](intro_image.jpg)
---

## Introduction

Charity is about building a better world, and there's no better way to do that than by equipping the younger generation with essential skills and resources. Educational charities play a vital role in ensuring a brighter future for children, even amidst global challenges. The Education For All Foundation is one such organization, offering free English education to underprivileged children worldwide. By connecting bilingual volunteers from North America and beyond with children in rural developing nations, the Foundation provides not only language skills but also emotional support, mentorship, and financial aid. Through its multi-cultural community of dedicated volunteers, the Foundation aims to empower these children, giving them the confidence to shape their own futures.

## Project Overview

This project focuses on analysing the donation patterns for the Education For All Charity Foundation, with the goal of developing a fundraising strategy to increase donations in the coming year. The foundation provides free English education to underprivileged children globally, aiming to empower them with the skills needed for a brighter future. The analysis involves studying donation and donor data to identify key trends and opportunities for increasing the number of donors, donation frequency, and donation amounts. Insights from this analysis will inform the creation of a targeted fundraising strategy to be presented at an upcoming fundraising strategy meeting. Data analysis was performed using SQL and visualized with Tableau, highlighting trends such as regional donation patterns, donor demographics, and donation behaviours.

## Tools

- SQLite
- Tableau

## Data Design

The dataset used for this analysis was stored as an SQL file. Two sources of data were collected: Donation data and Donor data. The Donation data includes Donor ID, First name, Last name, Email address, Gender, Job field, Donation amount, State of residence (US), and Donor shirt size. The Donor data contains Donor ID, Donation frequency, University attended, Car make, Second language, Favourite colour, and Favourite movie genre.

## Exploratory Data Analysis

EDA involves exploring the data to answer the following questions:
1.	Which state has the highest amount of donations?
2.	Which state has the highest number of donors?
3.	How frequently do donations come in (at once, yearly, monthly, and weekly)?
4.	Which gender has the highest amount of donations?
5.	Which job field has the highest amount of donations?

## Insights

I began by joining the two datasets—the Donation data and the Donor data—in SQLite, using the query below:



