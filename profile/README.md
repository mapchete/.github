# Welcome to the mapchete Organization!
  
**Scalable and efficient geospatial processing in Python.**


## About mapchete

The **mapchete** ecosystem provides tools and libraries to process massive amounts of geospatial data. By breaking down large datasets into smaller, manageable tiles, `mapchete` allows you to run complex algorithms on commodity hardware without running into memory limitations. The processing is parallelized out of the box, ensuring fast and efficient workflows.

Our tools are designed to be modular, user-friendly, and highly extensible, making them suitable for both interactive analysis and large-scale operational pipelines.


## Core Packages

### 🗺️ [mapchete](https://github.com/mapchete/mapchete)

The core library and command-line tool. It provides the foundation for tile-based processing of raster and vector data.

* **Process Large Datasets**: Work with massive raster and vector data without memory issues.
* **Parallel Processing**: Automatically run computations on multiple CPU cores.
* **Simple Configuration**: Use easy-to-read `.mapchete` files to separate your processing logic from your data configuration.
* **Pythonic API**: Use `mapchete` directly from the command line or as a library in your own Python applications.
* **Interactive Inspection**: Instantly visualize your results on a browser map with the built-in `serve` command.
* **Cloud-Optimized**: Designed to work with Cloud-Optimized GeoTIFFs (COGs) and other cloud-native formats.

### 🛰️ [mapchete-eo](https://github.com/mapchete/mapchete-eo)

An extension for Earth Observation (EO) applications. It provides drivers and tools to work with cloud-based EO data sources like SpatioTemporal Asset Catalogs (STAC).

* **STAC Integration**: Directly process data from STAC Items or STAC API search results.
* **Common EO Workflows**: Simplifies tasks like creating mosaics and time-series analysis.
* **Advanced Sentinel-2 Handling**: Built in capabilities like BRDF correction, and reading from various data archives.

### ☁️ [mapchete-hub](https://github.com/mapchete/mapchete-hub)

A service to discover, manage, and execute `mapchete` processes via a REST API. It allows you to build web services and workflows around your `mapchete` processes.

* **REST API**: Expose your `mapchete` processes as web services using an [OGC API Processes](https://ogcapi.ogc.org/processes/)-like interface.
* **Job Management**: Asynchronously execute and monitor long-running processing jobs.
* **Scalable Architecture**: Designed to be deployed in containerized environments like Docker and Kubernetes.


## Our Community

`mapchete` is an open-source project driven by its community. We welcome contributions of all kinds, from bug reports and feature ideas to documentation improvements and pull requests. Check out our **[CONTRIBUTING.md](https://github.com/mapchete/mapchete/blob/main/CONTRIBUTING.md)** guide in the main repository to get started.

## Acknowledgements

The `mapchete` ecosystem is developed and maintained as an open-source community effort. The initial development and many of the core features were made possible with the resources and support of **[EOX IT Services GmbH](https://eox.at/)**.
