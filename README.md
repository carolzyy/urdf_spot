# urdf_spot
urdf of whole spot
spot.urdf.xacro and accessories.urdf.xacro are the original files
spot.xacro is edited and can be convert to urdf
need to replace package to ..
if has arm, need to set arm env to 1 in accessories file
# link to convert xacro to urdf
https://answers.ros.org/question/10401/how-to-convert-xacro-file-to-urdf-file/
command:
rosrun xacro xacro model.xacro > model.urdf
