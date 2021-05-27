# Coherent Extension v0.1.0

The `coherent` namespace extension defines static values extending `captures` parameters that are useful for multi-capture phase coherent datasets.

## Captures

The following names are specified in the `antenna` namespace and should be used in the `captures` object:

|name|required|type|unit|description|
|----|--------|----|----|-----------|
|`num_channels`|true|int|N/A|Defines the number of channels collected in the coherent dataset.|
|`source_azimuth`|false|float|degrees|Defines the azimuth of a source, useful for single-emitter phase calibration data.|
|`source_elevation`|false|float|degrees|Defines the elevation of a source, useful for single-emitter phase calibration data.|
|`antenna_geometry`|false|array of array of floats|meters|Defines the relative arrangement of the phase centers of the array relative to element 0.|
|`version`|true|string|N/A|The version of the `coherent` extension used to create the metadata file.|