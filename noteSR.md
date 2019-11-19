<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
<link rel="stylesheet" type="text/css" href="http://tikzjax.com/v1/fonts.css"> <script src="http://tikzjax.com/v1/tikzjax.js"></script>
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

Let us denote $$\Delta t'$$ for time, for sent light (backward or forward) to take to travel from A to B, inferred by B. Then

$$v\left(\frac{1}{\alpha}\Delta t+\Delta t'\right)=v\left(\alpha \Delta t - \Delta t'\right)=c \Delta t'$$

Here $$c$$ denotes speed of light. So $$\Delta t'$$ is 

$$\Delta t'=\frac{1}{c-v}\left(v\left(\frac{1}{\alpha}\Delta t\right)\right)=\frac{1}{c+v}(v(\alpha\Delta t))$$

Then $$\alpha$$ is

$$\alpha=\sqrt{\frac{c+v}{c-v}}=\sqrt{\frac{1+v/c}{1-v/c}}$$

Then $$\Delta t'$$ is

$$\Delta t'=\frac{1}{\sqrt{c^2-v^2}}v\Delta t=\frac{1}{\sqrt{1-(v/c)^2}}\frac{v}{c}\Delta t$$

So inferred time that observer B infers to be simultaneous with light sending action by observer A is

$$\frac{c}{v}\Delta t'=\frac{1}{\sqrt{1-(v/c)^2}}\Delta t=\gamma \Delta t$$

<center>
<svg width="360" height="405" viewBox="0 0 400 450">

  <g transform="translate(50,0)">

  <line x1="-50" y1="400" x2="340" y2="400" style="stroke:black;stroke-width:1" />
  	<g transform="translate(340,400)">
  	<line x1="-6" y1="-6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  	<line x1="-6" y1="6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  	<foreignObject x="0" y="5">\(x\)</foreignObject>
  	</g>

  <line x1="20" y1="450" x2="20" y2="10" style="stroke:black;stroke-width:1" />
  	<g transform="translate(20,10) rotate(-90)">
  	<line x1="-6" y1="-6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  	<line x1="-6" y1="6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  		<g transform="rotate(90)">
  		<foreignObject x="10" y="-10">\(t\)</foreignObject>
  		</g>
  	</g>

  	<g transform="translate(20,400)">
  		<g transform="rotate(-60)">
  		<line x1="0" y1="0" x2="400" y2="0" style="stroke:black;stroke-width:1" />
  		<path d="M 0 0 q 124 22 248 0" style="stroke:darkgrey;stroke-width:1" fill="none" />

  			<g transform="translate(248,0)">

  				<g transform="rotate(60)">
  				<path stroke-dasharray="8,3" d="M 0 0 -125 0" style="stroke:black;stroke-width:1" fill="none" />
				</g>
  				<g transform="translate(-124,0) rotate(60)">
  				<rect x="2" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  				<foreignObject x="0" y="-6" fill="black">\(\Delta t\)</foreignObject> 
  				</g>
  				<g transform="rotate(-30)">
  				<path d="M 0 0 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15" style="stroke:rgb(255, 195, 56);stroke-width:1.5" fill="none"/>
  				</g>
  				<g transform="rotate(-120)">
  				<path d="M 0 0 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15" style="stroke:rgb(255, 195, 56);stroke-width:1.5" fill="none"/>
  				</g>

  			</g>

  		</g>

  	<path d="M 0 0 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15" style="stroke:rgb(255, 195, 56);stroke-width:1.5" fill="none"/>

  	<path d="M 0 0 q -20 -40 0 -80" style="stroke:darkgrey;stroke-width:1" fill="none" />
  		<g transform="translate(-26,-40)">
  		<rect x="0" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  		<foreignObject x="-18" y="-32" fill="black">$$\frac{1}{\alpha}\Delta t$$</foreignObject>
  		</g> 

  	<path d="M 0 0 q -40 -110 0 -220" style="stroke:darkgrey;stroke-width:1" fill="none" />
  		<g transform="translate(-40,-110)">
  		<rect x="2" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  		<foreignObject x="0" y="-22" fill="black">$$\gamma\Delta t$$</foreignObject>
  		</g> 

  	<path d="M 0 0 q -60 -170 0 -340" style="stroke:darkgrey;stroke-width:1" fill="none" />
  		<g transform="translate(-60,-170)">
  		<rect x="8" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  		<foreignObject x="6" y="-22" fill="black">$$\alpha\Delta t$$</foreignObject>
  		</g> 
  	</g>

  </g>
</svg>

</center>

Also the inferred time could be expressed in terms of observed time.

$$\gamma \Delta t =\frac{c}{c-v}\left(\frac{1}{\alpha}\Delta t\right)=\frac{c}{c+v}(\alpha\Delta t)$$

Also

$$\gamma \Delta t=\frac{1}{2}\left(\alpha-\frac{1}{\alpha}\right)\Delta t$$

,i.e., simultanity is assumed to be the middle point between received times of forward light and backward light.

You can also check that

$$\alpha\left(\Delta t-\frac{v}{c}\Delta t\right)=\frac{1}{\alpha}\left(\Delta t+\frac{v}{c}\Delta t\right)=\frac{1}{\gamma}\Delta t$$

<center>
<svg width="360" height="405" viewBox="0 0 400 450">

  <g transform="translate(50,0)">

  <line x1="-50" y1="400" x2="340" y2="400" style="stroke:black;stroke-width:1" />
  		<g transform="translate(340,400)">
  	<line x1="-6" y1="-6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  	<line x1="-6" y1="6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  	<foreignObject x="0" y="5">\(x\)</foreignObject>
  	</g>

  <line x1="20" y1="450" x2="20" y2="10" style="stroke:black;stroke-width:1" />
  	<g transform="translate(20,10) rotate(-90)">
  	<line x1="-6" y1="-6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  	<line x1="-6" y1="6" x2="0" y2="0" style="stroke:black;stroke-width:1" />
  		<g transform="rotate(90)">
  		<foreignObject x="10" y="-10">\(t\)</foreignObject>
  		</g>
  	</g>
  	
      <g transform="translate(20,400)">
  		<path d="M 0 0 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15" style="stroke:rgb(255, 195, 56);stroke-width:1.5" fill="none"/>

   <g transform="rotate(-60)">
  		<line x1="0" y1="0" x2="425" y2="0" style="stroke:black;stroke-width:1" />
  		<path d="M 0 0 q 124 35 248 0" style="stroke:black;stroke-width:1" fill="none" />
   <path d="M 102 0 Q 175 20 248 0" style="stroke:grey;stroke-width:1" fill="none" />
   <path d="M 248 0 Q 309 20 370 0" style="stroke:grey;stroke-width:1" fill="none" />
   <g transform="translate(175,5) rotate(60)">
  				<rect x="2" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  					<rect x="2" y="-13" width="14" height="40" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  				<foreignObject x="0" y="-28"><span style="color:rgb(90,90,90)">$$\frac{v}{c}\Delta t$$</span></foreignObject> 
  				</g>
    <g transform="translate(309,5) rotate(60)">
  				<rect x="2" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  					<rect x="2" y="-13" width="14" height="40" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  				<foreignObject x="0" y="-28"><span style="color:rgb(90,90,90)">$$\frac{v}{c}\Delta t$$</span></foreignObject> 
  				</g> 
  			<g transform="translate(248,0)">

  				<g transform="rotate(60)">
  				<path stroke-dasharray="8,3" d="M 0 0 -125 0" style="stroke:black;stroke-width:1" fill="none" />
		  		</g>
  				<g transform="translate(-124,5) rotate(60)">
  				<rect x="2" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  				<foreignObject x="0" y="-6" fill="black">\(\Delta t\)</foreignObject> 
  				</g>
                                <g transform="rotate(-30)">
  				<path d="M 0 0 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 20 -20" style="stroke:khaki;stroke-width:1.5" fill="none"/>
  				</g>
  				<g transform="rotate(-120)">
  				<path d="M 0 0 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 20 -20" style="stroke:khaki;stroke-width:1.5" fill="none"/>
  					</g>
  				
	  		<g transform="rotate(-150)">
	   <path stroke-dasharray="8,3" d="M 0 0 140 0" style="stroke:black;stroke-width:1" fill="none" />
  			</g>
</g>
  		</g>
        
   <path d="M 0 0 q -20 -40 0 -80" style="stroke:darkgrey;stroke-width:1" fill="none" />
          
   <path d="M 0 0 q -40 -75 0 -150" style="stroke:black;stroke-width:1" fill="none" />
          
  	<path d="M 0 0 q -60 -110 0 -220" style="stroke:darkgrey;stroke-width:1" fill="none" />

  	<path d="M 0 0 q -80 -170 0 -340" style="stroke:darkgrey;stroke-width:1" fill="none" />
  		<g transform="translate(-80,-170)">
  		<rect x="24" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  		<foreignObject x="12" y="-22"><span style="color:grey">$$\alpha\Delta t$$</span></foreignObject>
  		</g> 
          
   <g transform="translate(-26,-30)">
  		<rect x="0" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  		<foreignObject x="-18" y="-32"><span style="color:grey">$$\frac{1}{\alpha}\Delta t$$</span></foreignObject>
  		</g> 
          
   <g transform="translate(-40,-85)">
  		<rect x="0" y="4" width="25" height="16" style="fill:white;stroke-width:0;	stroke:rgb(0,0,0)" />
  		<foreignObject x="-9" y="-25">$$\frac{1}{\gamma}\Delta t$$</foreignObject>
  		</g>
          
   <g transform="translate(-60,-110)">
  		<rect x="10" y="-3" width="25" height="16" style="fill:white;stroke-width:0;stroke:rgb(0,0,0)" />
  		<foreignObject x="6" y="-22"><span style="color:grey">$$\gamma\Delta t$$</span></foreignObject>
  		</g> 
          
    <g transform="rotate(-60)">  
    <g transform="translate(102,0) rotate(-30)">
  				<path d="M 0 0 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 7 0 7 -7" style="stroke:rgb(255, 195, 56);stroke-width:1.5" fill="none"/>
  				</g>
  				<g transform="translate(370,0) rotate(-120)">
  				<path d="M 0 0 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 15 -15 q 0 -15 15 -15 q 15 0 20 -20" style="stroke:rgb(255, 195, 56);stroke-width:1.5" fill="none"/>
  				</g>
    </g>
  	</g>
    
  </g>
</svg>
</center>

<script type="text/tikz">
\begin{tikzpicture}
\draw[->] (0,0) -- (1,0);
\end{tikzpicture}
</script>

### 2. Observed Distance difference

Let us assume that there are three inertial observers. The relative velocity between observer A and observer B is $$v$$ and the relative velocity between observer A and observer C is 0.

Observer A and observer B were at same position at $$t=0$$. Also assume observer A sends light at $$t=0$$ to observer C. When observer C gets the light, he immediately sends light back to A.

The time that observer B observes by his clock when he receives the reflected light is $$2 \alpha \Delta x/c$$. Then the observed distance from A and C, observed by B is

$$\alpha \Delta x - v\left(\gamma \frac{2\Delta x}{c}\right)=\frac{1}{2}\left(\alpha (2 \Delta x) - 2v\left(\gamma \frac{2\Delta x}{c}\right)\right)=\frac{1}{2}\left(\frac{1}{\alpha} (2 \Delta x)\right)=\frac{1}{\alpha}\Delta x$$

So inferred distance that observer B infers to be distance from A to C from his point of view is

$$\alpha \Delta x-v\frac{\alpha \Delta x}{c}=\frac{1}{\alpha}\Delta x+\frac{v}{c}\frac{1}{\alpha}\Delta x=\frac{1}{\gamma}\Delta x$$

You can easily see that

$$\alpha \Delta x-v\frac{\alpha \Delta x}{c}=\alpha c\left(\frac{\Delta x}{c}-\frac{v}{c}\frac{\Delta x}{c}\right)=\frac{1}{\gamma}\Delta x$$

$$\frac{1}{\alpha}\Delta x+\frac{v}{c}\frac{1}{\alpha}\Delta x=\frac{1}{\alpha}c\left(\frac{\Delta x}{c}+\frac{v}{c}\frac{\Delta x}{c}\right)=\frac{1}{\gamma}\Delta x$$

### 3. Observed Time and Distance difference

Let us assume that there are two inertial observers, A and B and their relative velocity is $$v$$. As before, we set distance from A to B to be zero when their clock is synchronized to be zero. Also there is event C which is along the line of $$v$$. Assume that event C send light forward and backward in time to obsever A and B. Then A receives forward light when he observes his clock to show $$\Delta t$$ and receives backward light when he observes his clock to show $$\Delta t - 2\Delta x/c$$. Then observer B receives the forward light when he observes his clock to show $$\alpha \Delta t$$ and receives the backward light when he observes his clock to show $$(\Delta t - 2\Delta x/c)/\alpha$$. Therefore, the distance of event C from observer B in B's point of view is

$$\frac{1}{2}c\left(\alpha \Delta t -\frac{1}{\alpha}\left(\Delta t - \frac{2\Delta x}{c}\right)\right)=\frac{1}{\alpha}\left(\Delta x+\gamma v(\alpha \Delta t)\right)$$

Inversely, if observer B receives forward light by time $$\Delta t'$$ and backward light by time $$\Delta t' - 2\Delta x'/c$$ then observer A receives forward light by $$\Delta t'/\alpha$$ and the distance from A to C in A's point of view is

$$\frac{1}{2}c\left(\frac{1}{\alpha} \Delta t' -\alpha\left(\Delta t' - \frac{2\Delta x'}{c}\right)\right)=\alpha\left(\Delta x'-\gamma v \left(\frac{1}{\alpha} \Delta t'\right)\right)$$


## III. Energy-momentum and Mass
