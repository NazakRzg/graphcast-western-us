# GraphCast for the Western United States

This project is inspired by [GraphCast](https://doi.org/10.1126/science.adi2336), a graph neural network developed for global medium-range weather forecasting (Lam et al., 2023).

## Objectives

- Prepare regional weather data for machine learning
- Build persistence and climatology baselines
- Construct a graph representing the weather grid
- Train a graph neural network for 6-hour forecasting
- Produce autoregressive forecasts up to 48 hours
- Evaluate precipitation and atmospheric variables

## Study area

Western United States

## Forecast variables

- Six-hour accumulated precipitation
- Two-meter temperature
- Ten-meter zonal and meridional winds
- Geopotential height

## Tools

Python, PyTorch, PyTorch Geometric, Xarray, Dask, NetCDF, Zarr, Cartopy and Slurm

## Project status

Project setup and data preparation.

  pages={1416--1421},
  year={2023},
  publisher={American Association for the Advancement of Science}
}
