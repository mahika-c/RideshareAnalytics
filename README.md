Rideshare Analytics - Uber/Lyft data in Boston

Introduction and Background

With the rise of rideshare companies revolutionizing transportation in today's world, and with college students being a primary target customer base, we sought to analyze the various factors impacting the costs of these services by analyzing a Kaggle dataset on rideshare data from Boston, Massachusetts. With information on rides from Uber and Lyft, the two biggest rideshare companies in America, along with weather data based on the ride’s location and time, this rich dataset allowed us to build complex models to gain business and consumer insights to see how the companies perform in comparison, and how consumers (especially students) can understand the pricing factors behind their favorite transportation services.

Goals:


1.   Derive novel insights from this comprehensive dataset on what factors, both direct (such as rideshare company, distance, and time) and indirect (such as preciptation and temperature), impact the price of a given ride (regressional analysis).
2.   Determine if we can construct a model that classifies rides as either Uber or Lyft (classification analysis)?
3.   Use our model results to paint a multi-dimensional picture of the ridesharing business landscape.


Overview of the dataset: We have 693,000 observations of rides and 57 features describing the ride along with weather data based on the location and time of the ride, such as source, destination, distance, time, precipitation, and more. Our target variables are price (regression) and cab company (classification).
