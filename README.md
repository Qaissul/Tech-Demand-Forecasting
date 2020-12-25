# Project Title

Demand Forecasting to improve Technical Field Service Management - Final project for the Building AI course

## Summary

Based on orders, shop floor activities and feedback from field (e.g. maintanance activities, conversion frquency, frequent failures, and so on) as well as historic data (e.g. capacity bottleneck, KPI's) the AI-system should recommend a plan how to manage existing service technicians, including when and whom to hire in future.

Recommendation system is based on Service-Technicians-workload as KPI.


## Background

Predictive maintantenance lead to difficult planing of technical customer service.
The most tasks require a specialised technician who knows the machine, the process and the conversion task.
Since predictive maintanence lead to "spontanious" requests from customer, it is often challenging to organize a technician really quick.

In addition to that is is often challenging to build an optimal technician pool and this AI-tool shall support this action.


## How is it used?

The project management for technical customer service would use that recommendation system on regular basis.

## Data sources and AI methods
Data sources: 
- orders & customer requests
- shop floor
- Machine data from field (e.g. running hours, predictive maintenance warning, ...)
- vacation planing
- Calculation of KPI: workload, wheren 1 means perfect workload of sevice technicians (customers fully served)

AI method: 
- Neural network where outcome is for example: number of electricians for machine X, number of mechanics for machine X, ...
- Network can be teached with historical data (based on condition at specific time and KPI workload)


## Challenges

- Workload not only based on internal conditions like orders and maintenance activities but also on social aspects like the current COVID-19 pandemic

## What next?

- Identification of necessary parameters
- data set from firm required
- Building of Neural Network 


## Acknowledgments

-
