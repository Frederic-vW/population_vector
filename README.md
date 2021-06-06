# population_vector
Tutorial code (Python3 notebook) to explain the population vector approach in neuroscience.
- consider a set of neurons encoding different movement directions, equidistantly spaced around the unit circle
- define a random grasp angle 0..360 deg
- simulate single neuron activations: spike rate proportional to cosine between grasp angle and preferred neuron angle, make raster plots
- reconstruct the grasp vector as the sum of vectors defined by the preferred neuronal directions (angle) and the spike rates (amplitude)
