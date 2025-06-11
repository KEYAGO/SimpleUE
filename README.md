# SimpleUE
Simple Practices of User Equilibrium Traffic Assignment

This tool has been developed as a simple interface for practising User Equilibrium Traffic Assignment. The ‘Algorithms’ page contains several traffic assignment algorithms, their parameters and performance indicators. These algorithms are run on a simple test network with 2 nodes, 2 zones and 2 links (below image) to perform the tasks. Since there are only two links, there was no need to integrate a ‘Shortest Path’ algorithm. Instead, it operates with a simple rule logic. For the two zones defined as A and B, the flow is only from A to B. The BPR formulation is used for the volume-delay relationship. All parameters in the application are as follows; total demand, BPR function coefficients, link capacities, free flow travel times of links, total iteration, and demand coefficient for the decremental algorithm. On the ‘Algorithms’ page, you can change the parameter values and compare the algorithm responses and their performances. 

I hope you enjoy using the application :)


![SimpleUETestNetwork](https://github.com/user-attachments/assets/4c838c3f-79d3-4070-9001-4ce02996fa54)


![2-Algorithms_Page](https://github.com/user-attachments/assets/fff270dc-07ad-4642-96ce-498d31ba5efc)


