# Tensorflow latest version was built and uploaded
The build process will take approximately **2 hours** to complete.

Feel free to test it on your own platform on its C++ label_image example by running: 
> bazel-bin/tensorflow/examples/label_image/label_image
For running with valgrind:
> valgrind --leak-check=full bazel-bin/tensorflow/examples/label_image/label_image

Expected results:
> definitely lost: 0 bytes in 0 blocks
> indirectly lost: 0 bytes in 0 blocks

Let me know if you encounter any issue. 
