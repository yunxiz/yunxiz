<img src="forest-banner.svg" alt="Aimee Zeng. A conifer forest that sharpens from a 25 km grid to fine detail." width="100%">

I build machine learning models for environmental data, from rainfall fields and satellite imagery to land use, and I want that work to help conservation. I'm finishing an M.C.S. at UIUC (May 2027) after a B.S. in Statistics & Computer Science there.

**Looking for full-time roles starting summer 2027** in machine learning, data science, and geospatial work.

[Portfolio](https://YOUR-SITE.vercel.app) · [Email](mailto:aimeezengyunxi@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yunxi-zeng-547527265/) · [Résumé](https://YOUR-SITE.vercel.app/assets/resume.pdf)

### What I'm working on

**Climate downscaling with foundation embeddings.** ERA5 precipitation comes on a 25 km grid, too coarse for a watershed or a farm. My conditional flow matching model sharpens it to about 1.5 km in four 2× steps, using AlphaEarth satellite embeddings to tell it what the land underneath looks like. It produces calibrated ensembles, evaluated with CRPS and spread-skill against 800 m PRISM. The banner above plays the same four steps.
<sub>PyTorch · Google Earth Engine · xarray/Zarr · Slurm on NCSA Delta AI</sub>

**Biodiversity-aware solar siting.** A binary integer program on a 1 km grid across Texas and Oklahoma that picks solar sites by trading energy against habitat cost for seven wildlife guilds.
<sub>Python · integer programming · Streamlit</sub>

**Cover crop biomass from space.** A team project estimating Midwest cover crop biomass from Sentinel-1 radar, Sentinel-2/HLS optical imagery, and PRISM climate data, so nobody has to clip plots by hand.

**Causal effects of phthalate mixtures.** Factorial balancing weights for estimating main and interaction effects of co-occurring exposures, extended to multi-level factors and incomplete designs.

### Where I've worked

- **GlobiFYE**, AI Engineer Intern (2026): an AI sales intelligence platform with RAG, LangChain, Supabase, and SIP telephony for live calls
- **Butterflo Inc.**, Machine Learning Intern (2026): XGBoost rent prediction, refined from metro to cluster-level geographies
- **AIA Group**, Data Science Intern (2025): lapse and claims models at ~0.81 AUC, plus an R Shiny app for cash-flow replication
- **EyeSpy.org**, Volunteer Web Developer (2026): a grant workflow site for a nonprofit serving the blind and low-vision community

Before all this, I mapped deforestation inside the core zone of Baima Snow Mountain Nature Reserve, home of the Yunnan snub-nosed monkey, and [published it as first author](https://www.atlantis-press.com/proceedings/ichess-21/125967065) in 2021.

### Tools

Python, R, SQL · PyTorch, XGBoost, scikit-learn, Optuna · Google Earth Engine, QGIS, TorchGeo, rasterio, GeoPandas, GDAL, xarray/Zarr · Spark, MySQL, Supabase, Django, LangChain
