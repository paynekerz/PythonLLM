# Python Package Installation

Welcome my attempt at a python LLM. To get started, you'll need to install some essential packages. Simply run the following command: 

`pip install pylzma numpy ipykernel jupyter torch --index-url https://download.pytorch.org/whl/cu118`


## Running on Different Devices

If you don't have an NVIDIA GPU. The `device` setting in the code will automatically adjust to `'cpu'` in such cases, as it's set like this: `device = 'cuda' if torch.cuda.is_available() else 'cpu'`. While using the CPU (`'cpu'`) means your programs might run a bit slower, you'll still be able to execute your tasks.
