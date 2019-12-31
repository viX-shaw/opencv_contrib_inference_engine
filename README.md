# opencv_contrib_inference_engine

##This is a build of Opencv with contrib modules and inference engine for Raspberry Pi.
<p>OpenCV - 4.1.0</p>
<p>Inference Engine - Can be downloaded from here <a href=https://download.01.org/opencv/2019/openvinotoolkit/R3/>l_openvino_toolkit_runtime_raspbian_p_2019.3.334.tgz</a></p>

<p>Follow <a href=http://docs.openvinotoolkit.org/latest/_docs_install_guides_installing_openvino_raspbian.html>http://docs.openvinotoolkit.org/latest/_docs_install_guides_installing_openvino_raspbian.html</a> to setup the inference engine.</p>

<p>Assumption - Path to unzip the provided file is "/home/pi/Desktop"</p>
<p>Use the following environment variables to point to this opencv build.</p>
<p>export PYTHONPATH=/home/pi/Desktop/opencv_install/lib/python3.7/dist-packages/:$PYTHONPATH</br>
export LD_LIBRARY_PATH=/home/pi/Desktop/opencv_install/lib/:$LD_LIBRARY_PATH</br>
export OpenCV_DIR=/home/pi/Desktop/opencv_install/cmake</p>
