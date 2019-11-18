<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
<span style="color:red">This is not done. Much effort is needed to polish this out to be clear, insightful, readable, logical and self-contained.</span>
# Note on Special Relativity
## I. Introduction
### 1. What is Special Relativity?

Special relativity is basically a theory about space-time. It especially deals with 'special' spacetime, i.e., flat spacetime. Basically, mass curves spacetime. So flat means that there is no mass or mass is so small that space is almost not curved, i.e., almost flat. If we consider 'general' spacetime, i.e., spacetime with curvature, we should need a general spacetime theory, which is famously called general relativity. The name, special of special relativity and general of general relativity came from these context.

### 2. What is Inertial Observer?

The notion of flat spacetime is not the all ingredients of special relativity recipe. Special relativity needs one more ingredient, observers. Flat spacetime should be observed, and the observation is what special relativity deals with. And special relativity usually let the scope down to special observers, called inertial observers.

Inertial observer means a special observer who observes the the law of inertia to be valid. You may heard about the law of inertia, rest object continues to be rest and moving object with certain velocity continues to move at the same velocity if there is no external force acting on it. Let's assume there is one inertial observer. Then any observer moving with a constant velocity with respect to the first observer should be an inertial observer. An observer who decelerates or accelerates with respect to the first observer, i.e., whose velocity is changing, is non-inertial observer. And these non-inertial observers have an observation that deviates from the law of inertia.

Special relativity could be said to be a special spacetime theory, which deals with special spacetime (flat spacetime) with special observers (inertial observers). On the other hand, general relativity could be said to be a general spacetime theory, which deals with general spacetime with general observers. In other words, flat spacetime (special) is observed by inertial observers (special), and this observation is what special relativity deals with. Flat or curved spacetime (general) is observed by inertial or non-inertial observers (general) and this observation is what general realtivity deals with.

### 3. What is Lorentz Symmetry?

Further, if we use a notion of Lorentz symmetry, the concept of special relativity is much clear. As previously said, special relativity is about the observation of inertial observers on flat spacetime. Then, Lorentz symmetry could be a guiding principle on how the observations should be. In this introduction we talk about meaning of symmetry first.

In physics, Symmetry has special meanings. Symmetry needs two ingredients, one is called operation and one is called object. If we take an operation on some object and the object retains a same form after the operation, we say object is symmetric about that operation.

<center><img src="snowflake.jpg" width="20%" alt="Snowflake"></center>

If we have a vertical line passing through the center of snowflake and take an inversing operation on the snowflake about the vertical line, then snowflake still retains a same form. We say snowflake is symmetric about an inversion about a vertical line. Also as you can see, snowflake is symmetric about 60 degree rotation.

Lorentz Symmetry states that physical law or constants should be symmetric about change between inertial observers. One example is speed of light. Lorentz Symmetry states that if we meausre the speed of light by one inertial observer, then take an operation, which changes the observer to other inertial observer, and meausre the speed of light by the other observer, then the speed of light should be same. The speed of light should be symmetric about inter-change of inertial observers.

### 4. What is Galilean Symmetry?

Actually, the idea that physical law should be symmetric about inter-change of inertial observer was present before Einstein, back to Newtonian mechanics. The idea of symmetry of physical law and constants about inter-change of inertial observer before special realtivity is called Galilean symmetry. In other words,  Galilean symmmetry and Lorentz symmetry share the same idea that physical law should be symmetric about inter-change of inertial observer. However, the difference between Galilean symmmetry and Lorentz symmetry is their view point on how differently two inertial observers observes distance and time.

Galilean symmetry assumes absoluteness of time, i.e., time is not relative for an inerital observer (time is not depending on observers) but absolute for inertial observers (time is same for inertial observers). Then Galilean symmetry assumes distance from the observer to an object is relative for an inertial observer and not absolute for observers. However, Galilean symmetry kicks out speed of light from physical constants. In Galilean symmetry, speed of light is not absolute but relative to observers. That is the problem of Galilean symmetry and what should be kicked out is not speed of light but Galilean symmetry. 

## II. Distance and Time

### 1. Observed Time difference

Let us assume that there are two inertial observers and their relative velocity is $$v$$. Also assume that two observers were initially at same position and at the initial instant they set the clock to show $$t=0$$. Then sometime later, observer A observes his clock showing time $$\Delta t$$ has passed from the initial time $$t=0$$. And when he observes this, he sends the light to the observer B. When the observer B receives the light, he would observe his clock showing time $$\alpha \Delta t$$ has passed from $$t=0$$.

Let us assume light can propagate in backward time, so observer A send the light to the past. This assumption is not physical, but just a trick to calculate $$\alpha$$. Also assume observer A sends the backward-light at the same time when he sends forward-light to observer B, i.e., at the instant that he observes clock to show $$\Delta t$$ has passed from $$t=0$$. Then by symmetry, observer B receives the backward-light when he observes his clock to show $$\Delta t/\alpha$$ has passed from $$t=0$$.

Let us denote $$\Delta t'$$ for time for sent light (backward or forward) to take to travel from A to B. Then

$$v\left(\frac{1}{\alpha}\Delta t+\Delta t'\right)=v\left(\alpha \Delta t - \Delta t'\right)=c \Delta t'$$

Here $$c$$ denotes speed of light. So $$\Delta t'$$ is 

$$\Delta t'=\frac{1}{c-v}\left(v\left(\frac{1}{\alpha}\Delta t\right)\right)=\frac{1}{c+v}(v(\alpha\Delta t))$$

Then $$\alpha$$ is

$$\alpha=\sqrt{\frac{c+v}{c-v}}=\sqrt{\frac{1+v/c}{1-v/c}}$$

Then $$\Delta t'$$ is

$$\Delta t'=\frac{1}{\sqrt{c^2-v^2}}v\Delta t=\frac{1}{\sqrt{1-(v/c)^2}}\frac{v}{c}\Delta t$$

So inferred time that observer B observes by the clock and infers to be simultaneous with light sending action by observer A is

$$\frac{c}{v}\Delta t'=\frac{1}{\sqrt{1-(v/c)^2}}\Delta t=\gamma \Delta t$$

Also the inferred time could be expressed in terms of observed time.

$$\gamma \Delta t =\frac{c}{c-v}\left(\frac{1}{\alpha}\Delta t\right)=\frac{c}{c+v}(\alpha\Delta t)$$

### 2. Observed Distance difference

Let us assume that there are three inertial observers. The relative velocity between observer A and observer B is $$v$$ and the relative velocity between observer A and observer C is 0.

Observer A and observer B were at same position at $$t=0$$. Also assume observer A sends light at $$t=0$$ to observer C. When observer C gets the light, he immediately sends light back to A.

The time that observer B observes by his clock when he receives the reflected light is $$2 \alpha \Delta x/c$$. Then the observed distance from A and C is

$$\alpha \Delta x - v\left(\gamma \frac{2\Delta x}{c}\right)=\frac{1}{2}\left(\alpha (2 \Delta x) - 2v\left(\gamma \frac{2\Delta x}{c}\right)\right)=\frac{1}{2}\left(\frac{1}{\alpha} (2 \Delta x)\right)=\frac{1}{\alpha}\Delta x$$

So inferred distance that observer B infers to be distance from A to C from his point of view is

$$\alpha \Delta x-v\frac{\alpha \Delta x}{c}=\frac{1}{\alpha}\Delta x+\frac{v}{c}\frac{1}{\alpha}\Delta x=\frac{1}{\gamma}\Delta x$$

### 3. Observed Time and Distance difference

## III. Energy-momentum and Mass
