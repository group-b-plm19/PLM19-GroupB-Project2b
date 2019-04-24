## The Report

located at `./report.pdf`

## Source

located in `./src`

## Install

First install lua, luajit, pycco using your local package manager. Eg

```
brew install lua 
brew install luajit 
sudo -H pip install pycco
```

## Running

There are two files that will assist with running the project. The first is located at `./run` and this will run a test through the entire pipe. The second is located at `./run_interactive`, which will allow you to input the test case from the makefile that you would like to run.

You may need to run
`chmod +x run` and/or `chmod +x run_interactive`
