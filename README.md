# Large-scale instances of D{0-1}KP  

This data set includes 40 instances, which
- are divided into four types: uncorrelated instances (UDKP), weakly correlated instances (WDKP), strongly correlated instances (SDKP) and inverse correlated instances (IDKP)
- each type consists of 10 instances
- the size of each type of instances is 3 \**n*=3\*1200, 3\*1400, 3\*1600, ..., 3\*3000 (*n* is the group number).
- \ast

Each instance is recorded in a .txt file called "$dkpm.txt", where
- "$" denotes letter u, w, s and i
- "m" represent is the value of n/100.

All document instances have the same format as follows (take idkp12 as an example): 

1200  
603027  

225	950	1175  
267	689	956  
641	970	1611  
148	598	746  
...  
11	611	622  
661	923	1584  
89	257	346  
  
325	1050	1316  
367	789	922  
741	1070	1188  
...  
111	711	775  
761	1023	1285  
189	357	420  
  
where:
- 1200 is the group number *n*
- 603027 is the value of knapsack capacity
- from the line of 225  950	1175 to 89	257	346 is the profit of items from the first group to the last group
- from the line of 325	1050	1316  to 189	357	420 is the weight of items from the first group to the last group

For any inquiries, please contact zhs1198528779@163.com
