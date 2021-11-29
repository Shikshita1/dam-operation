# dam-operation
This code was made for modeling the operating policy of Three gorges dam located in China. It was written as a part of final project for the course named 'Water resources systems analysis' at Stanford University.

There are basically seven different scenarios for the dam operation. These seven scenarios have been included in seven functions inside the code. For the certain inflows in the dam, we can operate the dam based on those 7 functions. Then, we can calculate hydropower generated based on the inflows, upstream elevation and maximum hydropower capacity of the reservoir. 

Firstly, understanding the operating rule of the dam was a bit challenging. After understanding, we had to implement the rule using various if-else statements. Operating rule was adapted from P. Qin et al.(2020). 

Flows based on different climate change scenarios have been generated in the 'Inflows final'. Then, using the module based on operating policy, different stroage, outflows and hydropower output values were obtained.

In project, those values were compared and analysed using various plots and statistical parameters using pandas and matplotlib.pyplot libraries.


Bibliography:
Qin, P., Xu, H., Liu, M., Du, L., Xiao, C., Liu, L., & Tarroja, B. (2020). Climate change impacts on Three Gorges Reservoir impoundment and hydropower generation. Journal of Hydrology, 580, 123922.
