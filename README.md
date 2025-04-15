# Build an ML Pipeline for Short-Term Rental Prices in NYC
You are working for a property management company renting rooms and properties for short periods of 
time on various rental platforms. You need to estimate the typical price for a given property based 
on the price of similar properties. Your company receives new data in bulk every week. The model needs 
to be retrained with the same cadence, necessitating an end-to-end pipeline that can be reused.

In this project you will build such a pipeline.

## Table of contents

## Links for review
- [Git Hub repository Code](https://github.com/redhuskie/Project-Build-an-ML-Pipeline-Starter)
- [Git Hub Release](https://github.com/redhuskie/Project-Build-an-ML-Pipeline-Starter/releases/tag/1.0.3)
- [wandb work](https://wandb.ai/jdpickering1-western-governors-university/nyc_airbnb?nw=nwuserjdpickering1)


## Project runs and steps outlined. 
- Step 1: Exploratory Data Analysis
	Job Type: download_file (latest runs)
		Run: atomic-dream-44: sample.csv:v2
		Run: volcanic-terrain-13: sample.csv:v1
- Step 2: Data Cleaning (all)
	Job Type: basic_cleaning
		Run: faithful-terrain-50
		Run: visionary-microwave-40
		Run: dashing-haze-20
		Run: atomic-pyramid-17
		Run: sparkling-salad-45
- Step 3: Data Testing
	Job Type: Data_Tests (all)
		Run: ancient-wood-51
		Run: blooming-water-18
		Run: vibrant-wildflower-41
		Run: desert-wave-46
- Step 4: Initial Training
	Job Type: train_val_test_split (date splitting)
		Run: worthy-dust-52
		Run: sweet-leaf-42
		Run: swift-plasma-47
		Run: rose-grass-21
		Run: usual-deluge-19
- Step 4a: Train Random Forest
	Job Type: train_ramdom_forest 
		Run: cerulean-sky-37 (chosen as prod)
		Run: solar-sound-48
		Run: vibrant-sea-53
		Run: olive-fog-43
		Run: sandy-microwave-35
		Run: sunny-oath-34
		Run: worthy-haze-24
		Run: summer-eon-32
		Run: apricot-shadow-27
		Run: copper-smoke-31
		Run: fanciful-monkey-33
		Run: dutiful-plasma-28
		Run: fine-snow-30
		Run: splendid-violet-26
		Run: usual-star-22
		Run: ancient-snow-29
		Run: floral-shape-23
		Run: ancient-wave-25
- Step 5: Model Selection and Testing
	Job Type: test_model
		Run: fine-smoke-38
- Step Optimize Hyperparameters
	- hydra runs are as follows:
	1. generous-sunset-54
	2. blooming-valley-55
	3. treasured-waterfall-56
	4. curious-sunset-57

- I found the best run to be cerulean-sky-37 by just a small margin so that is listed as Prod. 
- I was really unsure what to do with all the extra runs so I left in place. 
- I was unsure about the Hydra optimization but worked with a mentor to get that to run but am unsure if I ran them in the correct location. 

