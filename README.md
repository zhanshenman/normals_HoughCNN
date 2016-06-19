# normals_HoughCNN
Deep Learning for Robust Normal Estimation in Unstructured Point Clouds 

# Paper

Please acknowledge our the reference paper :

"Deep Learning for Robust Normal Estimation in Unstructured Point Clouds " by Alexandre Boulch and Renaud Marlet, Symposium of Geometry Processing 2016, Computer Graphics Forum


# Dependencies

Eigen and nanoflann (assumed to be in the source folder)

PCL: ply read only (main.cpp)

Boost: argument parsing (main.cpp)

# Usage

HoughCNN_Exec [options] -m path_to_the_torch_model -i input_file.ply -o output_file.ply

Note: the file predict.lua should be next to the executable
