# fullstack-ml-app
Playing around with full stack machine learning development with:
* FastAPI
* React
* PyTorch

### Environment setup
##### 1. Create a Python virtual environment and activate it [^1]
`python3 -m venv /path/to/new/virtual/environment` [^2]
`source /path/to/new/virtual/environment/bin/activate` [^3]
##### 2. Install the required packages
###### FastAPI [^4]
`pip3 install fastapi`
`pip3 install "uvicorn[standard]"`
###### PyTorch [^5]
`pip3 install torch torchvision` [^6]
###### React [^7]
Run `npm i` in `fullstack-ml-app/client/`

[^1]: https://docs.python.org/3/library/venv.html
[^2]: https://docs.python.org/3/library/venv.html#creating-virtual-environments
[^3]: https://docs.python.org/3/library/venv.html#how-venvs-work
[^4]: https://fastapi.tiangolo.com/#installation
[^5]: https://pytorch.org/
[^6]: https://pytorch.org/get-started/locally/
[^7]: https://reactjs.org/docs/getting-started.html