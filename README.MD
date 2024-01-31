# Locust Intro

## Description

This is a simple project demonstrating how to use [Locust](https://github.com/locustio/locust) to run trivial load tests against Rest API

## Prerequisites

Before getting started, make sure you have the following prerequisites installed:

- [Python 3.x](https://www.python.org/downloads/)
- PIP
 ```shell
    python3 -m ensurepip
```
- venv
 ```shell
    pip3 install virtualenv
```

## Installation

1. Clone the repository:

```shell
git clone https://github.com/your-username/your-repo.git
```

2. Navigate to the project directory:

```shell
cd locust_intro
```

3. Install the dependencies and configure environment:

Create and activate isolated environment by running following commands
```shell
python3 -m venv venv
```
For Linux & Mac run 
```shell
source venv/bin/activate
```
For Windows run
```shell
venv\Scripts\activate.bat
```
Install dependencies 

```shell
pip3 install -r requirements.txt
```

## Usage

To launch Locust, run the following command:

```shell
locust
```
and then open web interface by copying address from console like `Starting web interface at http://0.0.0.0:XXXX`
