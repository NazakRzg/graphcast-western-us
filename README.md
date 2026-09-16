# GraphCast for the Western United States

This project develops a small graph neural network for regional weather forecasting over the western United States. It is inspired by GraphCast, but uses a smaller dataset and architecture suitable for research experiments.

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


@article{lam2023learning,
  title={Learning skillful medium-range global weather forecasting},
  author={Lam, Remi and Sanchez-Gonzalez, Alvaro and Willson, Matthew and Wirnsberger, Peter and Fortunato, Meire and Alet, Ferran and Ravuri, Suman and Ewalds, Timo and Eaton-Rosen, Zach and Hu, Weihua and others},
  journal={Science},
  volume={382},
  number={6677},
  pages={1416--1421},
  year={2023},
  publisher={American Association for the Advancement of Science}
}
