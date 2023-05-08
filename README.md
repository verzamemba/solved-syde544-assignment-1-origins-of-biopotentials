Download Link: https://assignmentchef.com/product/solved-syde544-assignment-1-origins-of-biopotentials
<br>
Part one: Equilibrium potential and resting membrane potential

<ol>

 <li>When we were developing the equilibrium potential for specific ions during the lecture, we calculated and  using the Nerst equation:</li>

</ol>

Please use the information in the table provided on page 7 of Handout 1 to calculate

<ol start="2">

 <li>When we are developing the Resting potential, we didn’t consider Chloride ions. Based on the result of the first question, do you see a reasonable justification for ignoring Chloride? (Hint: first considering the membrane impermeable to Chloride, calculate the resting membrane potential. Then analyze the dynamics when the membrane becomes permeable to Chloride).</li>

 <li>When Chloride is considered, the Goldman equation we introduced in the lecture should be modified to:</li>

</ol>

Show that        is essentially not influenced by the membrane permeability of , <em>i.e.</em>

the value of        .

<h1> Part two: Modeling of the dynamics of single neuron</h1>

<ol start="4">

 <li>Draw the phase plane of the following ODE system, which describes the membrane dynamics of a type of theoretical neuron:</li>

</ol>




where . Identify the fix point(s) of the system,

identify the distinct regions of the phase plane in terms of the direction of the vector fields (similar to the discussion in class). Determine the type(s) of the fix point(s). What is the resting membrane potential () of this theoretical neuron?




<ol start="5">

 <li>Here, let’s define an action potential as an event of , such that a depolarization (rising phase) is followed by a repolarization (falling phase), reaching a hyperpolarization state () before returning to its resting state. Now use Matlab to simulate, in the phase plane (not with the ODE toolbox), the solution to the system when the initial</li>

</ol>

condition is at ; change the initial condition to  and

, repeat the simulation. Describe what you observe? Was there an action potential for any of these solutions? What is the threshold voltage?

<ol start="6">

 <li>Repeat the above simulation with . Describe your observation.</li>

</ol>

Note: Symbolic toolbox and Differential equation toolbox of Matlab should NOT be used