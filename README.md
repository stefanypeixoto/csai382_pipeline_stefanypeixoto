# csai382_pipeline_stefanypeixoto

This repository is my main data pipeline project for CSAI 382. It will store all the notebooks, SQL scripts, pipeline code, and sample data that I build throughout the course so everything is organized in one place.

## Project Purpose

The goal of this repo is to keep my data pipeline work structured and easy to understand. As I go through the class, I will add ETL notebooks, SQL transformations, and simple automated workflows here. Keeping everything together in one pipeline repository will make it easier to rerun work, review my progress, and build on previous assignments.

## Repository Structure

The repository is organized into the following folders:

- `notebooks/`  
  Databricks or Jupyter notebooks used for data loading, cleaning, transformation, and other ETL tasks.

- `sql/`  
  Standalone SQL scripts that perform transformations, aggregations, or queries as part of the pipeline.

- `etl_pipeline/`  
  Python scripts, workflow definitions, or other automation files that will later be used to schedule and orchestrate ETL jobs.

- `data_samples/`  
  Small example datasets used for testing and development, so I can try changes without needing full production data.

- `README.md`  
  This document. It explains the purpose of the project and what each folder is used for.

## How This Repo Will Be Used

As I move through the course, I will:

- Add new notebooks into the `notebooks/` folder when I create ETL steps in Databricks or Jupyter.
- Save any reusable SQL code into the `sql/` folder.
- Store automation or pipeline code (for example, scripts or workflow configs) in the `etl_pipeline/` folder.
- Place small CSVs or other sample data files in `data_samples/` for testing.

This structure is meant to be a foundation for a simple but organized data pipeline that can grow over time.
