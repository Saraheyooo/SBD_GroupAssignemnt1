# Social-Behaviour-Dynamics

# Causal Relation Analysis
20211129


## Part 1

In Part 1 of your group assignment you will use your domain knowledge to create and simulate data from your own SCM.
Working in your discussion groups, you will describe this process in a brief Rmarkdown report. This report should include a brief substantive justification and description of your causal system, as well as the necessary code to reproduce your causal system and data- generation.
To complete Part 1 of the assignment, you need to complete the following steps.

* Draw a DAG representing a simple and somewhat plausible causal system from your domain of expertise. It should contain somewhere between 5  and 9 variables. Feel free to use the DAGs discussed in Rohrer (2018) and Elwert and Winship (2014) for inspiration or as a starting point. Describe briefly the substantive motivation behind your DAG.  
* Construct an SCM for this causal system. Pick any kind of relationships and variable types you like: It can be linear and nonlinear in parts, and the variables can have any type of distribution.  
* Generate and save data from the observational distribution (i.e., observational data)
using a sample size of 𝑛 = 500.  
* Generate and save data after a very simple 𝑑𝑜() intervention on this system, again using a sample size of 𝑛 = 500. Briefly describe why this intervention would be of interest substantively.



## Part 2

In part 2 of the group assignment you will be using causal discovery methods –which we cover in Week 4– to try and recover this causal system from the data you simulated in part 1.

In this second part of your assignment I want you to:

* Choose a causal discovery method that is most appropriate for your particular setting, and say why you chose that method: do the variables share linear relationships? Gaussian or non-Gaussian noise? I want to see a (brief) reflection on the different methods you learned about this week, at least in identifying which method is most appropriate for your specific case.
* Apply the causal discovery method to your data, and discuss the results. What do you find? Do you recover some features of the true causal system? Why do you think this is the case? Think about the fundamental limitations of different approaches, and the appropriateness of the assumptions you make.


