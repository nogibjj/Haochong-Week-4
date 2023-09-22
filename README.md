# Haochong-week4-mini-repo [![Matrix Build for Test Multiple Python Versions](https://github.com/nogibjj/Haochong-Week-4/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Haochong-Week-4/actions/workflows/cicd.yml)
This is a repo template for course 706_Data_Engineering Week 4 Mini Project. I edit the .yml file, change the name into "Matrix Build for Test Multiple Python Versions" and add matrix of multiple versions. Finally, I use Action to run Makefile and got a 100% pass. 

# Purpose
Build matrix for at least 3 different python versions tests in workflow.

## Preparation 
1. open codespaces 
2. wait for container to be built with requiremnts.txt installed

## Check format and test errors
1. Format code `make format`
   <img width="974" alt="截屏2023-09-10 下午3 43 18" src="https://github.com/nogibjj/Haochong-Xia-Week-2/assets/89813704/fd210688-7317-4f5e-bd81-fba58e7c2899">

2. Lint code `make lint`
3. Test code `make test`
First time I got this.
<img width="651" alt="截屏2023-09-08 下午1 51 53" src="https://github.com/nogibjj/Haochong-Xia-Week-2/assets/89813704/a222f5d3-69d8-4260-a5a5-b7ba46354f2b">

At the beginning, I thought it was because of the round up decimal. Hence, I comment the second assert but got the same test result. Then, I search "Error 5" on google and got this:https://zditect.com/blog/30980196.html , but I don't think I have this problem. After checking with all my document again, I noticed that I accidentally wrote the test_ format as Test_. After fixing this, I got all pass.
<img width="598" alt="截屏2023-09-08 下午1 57 13" src="https://github.com/nogibjj/Haochong-Xia-Week-2/assets/89813704/b46b613c-47f5-4c16-b03e-713fea05d619">
<img width="662" alt="截屏2023-09-10 下午3 49 46" src="https://github.com/nogibjj/Haochong-Xia-Week-2/assets/89813704/b588e18d-4414-487e-b85c-6a90ca4c8d67">



