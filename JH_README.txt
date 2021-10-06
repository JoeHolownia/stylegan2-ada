Errors overcome:

- Must install CUDA 10.0 with CUDnn 7.5
- Use Tensorflow 1.14

- (Need to make a requirements.txt file)

- For Windows, must install Microsoft Visual Studio 2017 with Desktop C++ Development option
and add ____ to path.

- sm_86 is not a defined option for gpu-architecture
	= need to check allowed values via nvcc --help
	= switched to sm_75

COMMANDS:



Train:
python train.py --outdir ./results --snap=5 --data=./datasets/oasis_brain --augpipe=bgcfnc --res=256