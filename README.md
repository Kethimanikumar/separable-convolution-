A Separable Convolution is a process in which a single convolution can be divided into two or more convolutions to produce the same output. A single process is divided into two or more sub-processes to achieve the same effect. Let’s understand Separable Convolutions, their types in-depth with examples.

Mainly there are two types of Separable Convolutions

Spatially Separable Convolutions.
Depth-wise Separable Convolutions.Spatially Separable Convolutions
In images height and width are called spatial axes. The kernel that can be separated across spatial axes is called the spatially separable kernel. The kernel is broken into two smaller kernels and those kernels are multiplied sequentially with the input image to get the same effect of the full kernel.
For example
Spatially Separable Convolutions.Depthwise Separable Convolutions
When you call tf.keras.layers.SeparableConv2D you would be calling a Depthwise separable convolution layer itself. Here you can use even those kernels which can not be spatially separable. Similar to spatial convolution, here also a regular convolution is divided into two convolutions namely

Depthwise convolution
Pointwise convolution
