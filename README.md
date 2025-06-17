# mini-api
A mini repo for demonstrating FastAPI


## Prerequisites

### Starting from zero on MacOS 

Feel free to skip this if you already have `git`, `python` and `uv` installed.

1. Install Mac Developer Tools:
   ```bash
   xcode-select --install
   ```
2. Install [Homebrew](https://brew.sh/).
3. Install `git`:
   ```bash
   brew install git
   ```
4. Install `uv`:
    ```bash
    brew install uv
    ```


### Clone the repo and set up a virtual environment

1. Open a terminal and move to the directory where you want to clone the repo (e.g., `cd ~/projects`).
2. Clone the repository locally:
   ```bash
   git clone git@github.com:SdgJlbl/mini-api.git
   ```
3. Change to the repository directory:
   ```bash
   cd mini-api
   ```
4. Create a virtual environment:
   ```bash
    uv sync
    ```

## A minimal example

The goal is to use FastAPI to create a simple web API (and test it).

FastAPI documentation is providing a [minimal skeleton](https://fastapi.tiangolo.com/#create-it) that we will modify to suit our needs.

The ultimate goal is to have two endpoints:
- a POST endpoint that posts a user query to the server;
- a GET endpoint that returns the answer.

The server will choose the right tool amongst 3 based on a very simple heuristic.
