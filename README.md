
This is fork of (https://github.com/FracturedCode/OpenCL.NetCore).
Just trying to add some OOP.

How it should work:

Init devices -> if OK, we have list of initiated devices.

Choose device and activate it -> we have context.

Load kernel source and set in/out buffers.

Run.

Wait to get result.

If we done -> clean up and close device.

