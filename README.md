# Haochong-week4-mini-repo [![Matrix Build for Test Multiple Python Versions](https://github.com/nogibjj/Haochong-Week-4/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Haochong-Week-4/actions/workflows/cicd.yml)
This is a repo template for course 706_Data_Engineering Week 4 Mini Project. I edit the .yml file, change the name into "Matrix Build for Test Multiple Python Versions" and add matrix of multiple versions. Finally, I use Action to run Makefile and got a 100% pass. 

# Purpose
Build matrix for at least 3 different python versions tests in workflow.

## Preparation 
1. open codespaces 
2. wait for container to be built with requiremnts.txt installed

## Check format and test errors
1. Format code `make format`
2. Lint code `make lint`
3. Test code `make test`
I add these lines in my cicd.yml:

<img width="414" alt="截屏2023-09-22 上午11 43 25" src="https://github.com/nogibjj/Haochong-Week-4/assets/89813704/e6fce1a1-9130-4c72-a95a-2229319ff386">

I got this result in Action:

<img width="1395" alt="截屏2023-09-22 上午11 41 43" src="https://github.com/nogibjj/Haochong-Week-4/assets/89813704/2c6753a0-929c-4067-a6c4-3a343e9fedda">




