# fullstack-ml-app
Playing around with full stack machine learning development with:
* FastAPI
* React
* PyTorch

### Environment setup
##### 1. Create a Python virtual environment and activate it
`python3 -m venv /path/to/new/virtual/environment` [^1]

`source /path/to/new/virtual/environment/bin/activate` [^2]
##### 2. Install the required packages
###### FastAPI [^3]
`pip3 install fastapi`

`pip3 install "uvicorn[standard]"`
###### PyTorch
`pip3 install torch torchvision` [^4]
###### React [^5]
Run `npm i` in `fullstack-ml-app/client/`

[^1]: https://docs.python.org/3/library/venv.html#creating-virtual-environments
[^2]: https://docs.python.org/3/library/venv.html#how-venvs-work
[^3]: https://fastapi.tiangolo.com/#installation
[^4]: https://pytorch.org/get-started/locally/
[^5]: https://reactjs.org/docs/getting-started.html