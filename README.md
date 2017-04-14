Quick code I wrote up during Paul Torren's Advanced Spatial Analysis class.
Takes a shapefile (in this case, I took a shapefile of Michigan Census Tracts), takes the centroid of each polygon, converts to a numpy array, then creates a voronoi diagram (with voronoi polygons) out of those centroids.
