# cs780-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS780 Assignment #1 Solved](https://www.ankitcodinghub.com/product/cs780-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131863&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS780 Assignment #1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Submission Link: https://forms.gle/87nKC1BYvxtVdGdU9

Read all the instructions below carefully before you start working on the assignment.

• The purpose of this course is that you learn RL and the best way to do that is by implementation and experimentation.

• The assignment requires your to implement some algorithms and you are required report your findings after experimenting with those algorithms.

• You are required to submit a report which would include the graphs/plots of the experiments you run and your findings.

• Solutions to the assignment need to be typeset in the LATEX. Template for the report (SolutionsAssignment-1.tex file) is provided. DO NOT change the format of the template, use it as is provided to you without modifying it. In case you need any additional latex package, you can add it. You are required to compile the tex file and submit pdf version of the report.

• In case your solution is found to have an overlap with solution by someone else (including external sources), all the parties involved will get zero in this and all future assignments plus further more penalties in the overall grade. We will check not just for lexical but also semantic overlap. Same applies for the code as well. Even an iota of cheating would NOT be tolerated. If you cheat one line or cheat one page the penalty would be same.

• Be a smart agent, think long term, if you cheat we will discover it somehow, the price you would be paying is not worth it.

• Since the assignment involves experimentation, reporting your results and observations, there is a lot of scope for creativity and innovation and presenting new perspectives. Such efforts would be highly appreciated and accordingly well rewarded. Be an exploratory agent!

• In your plots, have a clear legend and clear lines, etc. Of course you would generating the plots in your code but you must also put these plots in your report. Generate high resolution pdf/svg version of the plots so that it doesn’t pixilate on zooming.

• For implementing a new environment in Gymaniusm, we have already shared a document about the process, please refer to it. You are not required to render the environment on the screen/terminal. Do remember to set the seed, this will be useful for reproducing your experiments. And we will use the seed provided by you to verify your results. Also for each instance of the environment that you create use a different seed and save these seeds, these will be useful for reproducing the results. Do not set the seed to 42 😛

• For all experiments, report about the seed used in the code documentation and also in your report, write about the seed used.

• In your report write about all things that are not obvious from the code e.g., if you have made any assumptions, references/sources, running time, etc.

Problem 1: Multi-armed Bandits

(10+10+60+20+20+20+20+20+20=200 points)

In particular, you will be implementing 2-armed Bernoulli Bandit (Figure (a)) and 10-armed Gaussian Bandit (Figure (b)).

2-armed Bernoulli Bandit: The mathematical formulation is as follows:

R0 ∼ Bernoulli(α)

R1 ∼ Bernoulli(β)

10-armed Gaussian Bandit: The mathematical formulation is as follows:

Rq∗k(k∼N) ∼N(µ(=µ = 0q∗(k,σ),σ2 = 1)2 = 1)

Note that in 10-armed Gaussian Bandit, for each arm k, the action value q∗(k) is sampled from a standard Gaussian distribution and reward for the corresponding arm is sample from a gaussian distribution which has mean q∗(k) and unit standard deviation.

1. In Gymnasium create the environment for 2-armed Bernoulli Bandit. The environment should take α and β as input parameters and simulate 2-armed bandit accordingly. Once you have implemented the environment, run it using different values of α and β to make sure it is executing as expected. For, example, you can try with (α,β) = (0,0),(1,0),(0,1),(1,1),(0.5,0.5), etc. Report about your test cases and how they point towards the correct implementation. Also report about your general observations.

Steps

Figure 2: Plots for Multi-Armed Bandit Agents

2. Similarly, in Gymnasium create the environment for 10-armed Gaussian Bandit. Make sure it is executing as expected by creating certain test cases, e.g., by playing with σ. Report about your test cases and how they point towards the correct implementation. Also report about your general observations.

3. Bandit Agents:

4. Create 50 different 2-armed Bernoulli Bandit environments by sampling different values of α and β from a standard uniform distribution (U(0,1)). Run each of the agents above (6 in total) for 1000 time-steps (this is one run) for each instance of the environment. At each time step record the received reward. For a given agent, at each time step, average out the rewards over 50 instances of the environment. Draw a plot (e.g., using Matplotlib) of average rewards received vs. time step. Do this for all agents and plot it in the same plot. Now you can compare different agents (i.e., different strategies). Since different agents have different hyper-parameters, play with different settings and you can generate multiple different plots

so as to aid comparison. Analyze the plots, write about your key observations, e.g., what strategy works better, what settings for a strategy works better, what your findings about the agents, etc.

5. Repeat the same thing as above for 10-armed Gaussian Bandit.

7. Repeat the same thing as above for 10-armed Gaussian Bandit.

8. Plot average rewards vs episodes for each of the 6 agents in the same plot. Basically, for each agent, run 50 instances of 2-armed Bernoulli Bandit environment, run the agent for 1000 episodes; calculate the average reward at each step across all 50 instances and plot the average reward vs episodes. Just to give an example of the plot see the top plot in Figure 2.

9. Plot % Optimal Action vs episodes for each of the 6 agents in the same plot. Basically, for each agent, run 50 instances of 2-armed Bernoulli Bandit environment, run the agent for 1000 episodes; calculate on an average (across 50 instances) for each episode how often (in %) the agent selects the optimal action and plot % Optimal Action vs episodes. Just to give an example of the plot see the bottom plot in Figure

2.

10. Repeat the above two things for 10-armed Gaussian Bandit.

Problem 2: Monte Carlo Estimates and TD Learning

(10+10+40+40+20+20+20+20+20+20+10+20+20+20+10=300 points)

Monte Carlo Estimate: Ve+1(s) = Ve(s) + α(e)[Ge − Ve(s)]

TD Learning Estimate: Vt+1(St) = Vt(St) + α(t)[Rt+1 + γVt(St+1) − Vt(St)]

Figure 3: Random Walk Environment

In this problem, you are required to calculate Monte Carlo and TD estimates for the RWE. Assume γ = 0.99, policy (π) is “go left”.

1. Implement a function that would simulate and generate a trajectory for RWE for a given policy π and maximum number of steps. The function definition would be like this: def generateTrajectory(env, π, maxSteps)

The function returns a list of experience tuples. Here, maxSteps parameter is used to terminate the episode if it exceeds maxSteps count. In such a case, the partial trajectory is discarded and and empty list is returned. Test the function using suitable test cases and make sure it is working.

2. Implement a function that would decay the step size parameter (α). The function definition would be like this:

def decayAlpha(initialValue, finalValue, maxSteps, decayType)

Here decayType can be linear or exponential. maxSteps is the maximum number of steps the step parameter should decay for. initialValue and finalValue are initial and final values of the step size parameter. The function should return a list of step size parameter values. Test the function by trying out different parameter settings. Plot value of α vs time step both for linear and exponential decays.

5. Plot the MC-FVMC estimate of each non-terminal state of RWE as it progress through different episodes. In the same plot also plot the true estimate. Take maximum of 500 episodes. You can play with different settings of α, for example, the step size parameter (α) starts from 0.5 and decreases exponentially to 0.01 till 250 episodes and after that it is constant. Or else you can also try with small (&lt; 1) value of constant α. Analyze the plots for each state and report your observations, findings and possible reasons for the observed behavior.

6. Plot the MC-EVMC estimate of each non-terminal state of RWE as it progress through different episodes. In the same plot also plot the true estimate. Take maximum of 500 episodes. You can play with different settings of α, for example, the step size parameter (α) starts from 0.5 and decreases exponentially to 0.01 till 250 episodes and after that it is constant. Or else you can also try with small (&lt; 1) value of constant α. Analyze the plots for each state and report your observations, findings and possible reasons for the observed behavior. How does EVMC fair against FVMC?

7. Plot the TD estimate of each non-terminal state of RWE as it progress through different episodes. In the same plot also plot the true estimate. Take maximum of 500 episodes. You can play with different settings of α, for example, the step size parameter (α) starts from 0.5 and decreases exponentially to 0.01 till 250 episodes and after that it is constant. Or else you can also try with small (&lt; 1) value of constant α. Analyze the plots for each state and report your observations, findings and possible reasons for the observed behavior.

10. Plot the MC-EVMC estimate of each non-terminal state of RWE as it progress through different episodes. But this time, the x-axis (episodes) should be log-scale. In the same plot also plot the true estimate. Take maximum of 500 episodes. You can play with different settings of α, for example, the step size parameter (α) starts from 0.5 and decreases exponentially to 0.01 till 250 episodes and after that it is constant. Or else you can also try with small (&lt; 1) value of constant α. This plot will help to zoom in and observe the behavior of the estimates in the initial stages. Analyze the plots for each state and report your observations, findings and possible reasons for the observed behavior. How does EVMC fair against

FVMC?

12. Based on the plots, compare MC-FVMC, MC-EVMC and TD approaches and report your observations.

14. Plot the MC-EVMC Target value (Gt) for any one non-terminal state of RWE (use the same state as above) as it progress through different episodes. Use the same setting as above. In the same plot also include the optimal value of the state. What do you observe and what are the reasons for what you observe? Explain and Report.

16. Based on the plots, compare MC-FVMC, MC-EVMC and TD targets and report your observations.
