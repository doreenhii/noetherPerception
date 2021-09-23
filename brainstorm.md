---
layout: page
title: "Attempts"
url: brainstorm
description: "of Making the Connection"
image: assets/images/attempt.jpg
nav-menu: true
---

<blockquote>
	Documenting attempts of linking perception to Noether's theorem.
	<br /><br />
	Where do we stand? What are the challenges ahead? What can we learn from the history of Physics? Can we follow the same steps to arrive at a set of equations to describe human perception? 
</blockquote>

<p>
Observations on invariance or symmetry regarding some aspect of nature is the basis for this project. As we have outlined in <a href="perceptualConstancy.html">Perceptual Constancy</a> page, the phenomena of 3D shape constancy of human visual perception is the perfect test bed for this investigation. 
</p>
<p>
We first outline our proposal on defining 3D shapes by its mirror symmetry (bilateral symmetry). We then describe three general perspectives that may be relevant if one wishes to propose other variables.  
</p>


<header class="major">
    <h3>Proposed Variables: Mirror Symmetry + Visual Cues</h3>
</header>
<h4>Why mirror symmetry?</h4>
<p>
	<b>Motivation</b>: To study 3D shape perception, we need a definition of a shape. But what is a shape? What are the necessary and sufficient variables to define a shape? <br />
	We propose that mirror symmetry (bilateral symmetry) of a 3D object as the abstract variable that summarizes the 3D shape well. In stronger words, mirror symmetry is the appropriate, <strike>sufficient,</strike> and indispensable quantity for shape constancy to occur. 
</p>
<p>
	<b>Why mirror symmetry?</b>
	Both natural and man-made objects exhibit mirror-symmetry. Nature could have picked up on that and evolve to utilize the information. <br />
	<b>Why do almost all objects exhibit mirror symmetry?</b> This could be linked to stability (symmetrical distribution of weights), or to their functionality (being able to move straightly, or move in all directions, being able to bear objects, ...) [Over 99% of modern animals exhibit mirror symmetry. Refer to Finnerty, J. R., Pang, K., Burton, P., Paulson, D., & Martindale, M. Q. (2004)]. It is hard to find non-symmetrical shapes in nature, an outlier will be the arrangements of internal organs, where space constraint is most pressing.<br />
	Other than that, symmetry entails redundancy. Zyg & de Barros (2021) believe that "redundancy is the most effective constraint in solving ill-posed inverse problems." Mirror symmetry is the simplest case redundancy, with one symmetry under the operation of mirror reflection. 
</p>
<h4>Observations (invariance in nature)</h4>
<p>
	Experiments showed that without symmetry, shape constancy cannot be achieved: "when only one 2D image is available and a 3D object has no trace of symmetry, this object is not perceived as 3D" (Pizlo & de Barros, 2021). Another supportive case could be a Necker cube, where slight twist in local feature distorts the overall global perception. Why? Mirror symmetry is lost. 
</p>
<div class="row uniform">
	<div class="6u 12u$(medium)">
		<span><img src="assets/images/neckerCubes.png" alt="Necker Cubes"></span>
	</div>
	<div class="6u 12u$(medium)">
		<p>
			Left: Original Necker cube illusion, where we arrive at the the perception of a 3D cube from eight disks oriented in a specific way. <br />
			Right: Necker cube with two disk rotated clockwise by 20 degrees. We no longer arrive at the percept of a cube.<br /><br />
		</p>
	</div>
</div>

<p>
	Mirror symmetry alone is powerful enough to restrict the space of possibility for the family of possible solutions to one class of solutions [Jayadevan, V., Sawada, T., Delp, E., & Pizlo, Z. (2018). Perception of 3D symmetrical and nearly symmetrical shapes. Symmetry, 10(8), 344.]. However, additional constraints are needed to pinpoint the unique percept. Compactness of the shape may be another visual cue that can be included.
</p>
<h4>The Lagrangian</h4>
<p>
	How would the Lagrangian look like if we would like to describe 3D shapes using mirror symmetry? As an immature placeholder, we imagine a Lagrangian that takes as input the left side and the right side of the 3D object. The precise mathematical form on how to describe that shape is to be worked out. Consider all the points to the left side and points to the right side of the 3D object. The "dynamics" of the object, the Lagrangian, is a function that will sweep through the region in between the left and right side, so that the action functional will be the integral of the whole walk through all the points of the shape. This integral does not change (is constant or is invariant) if both the left and right side of the shape changes together, so the functional is invariant under the transformation operation that changes the shape of the object but retaining its mirror symmetry property. 
</p>


<header class="major">
    <h3>Directions of Research</h3>
</header>
Below are some general approaches that may help framing the questions, or to propose other variables.
<header class="major">
    <h4>General approach 1: The front door</h4>
</header>
<p>
	This approach moves in the direction of selecting the appropriate variables, followed by proposing a suitable Lagrangian to describe the phenomena (invariance), then deriving its conservation law. 
</p>
<p>
	The challenge to this approach is that we do not know how to describe perception, neither do we have a formal definition of shape. To draw a parallel, in Physics, objects are abstracted away and described in terms of energies. Motion of objects are therefore also captured as changes in their energies. After suitable variables such as energies are identified, there needs to be the appropriate proposal of Lagrangian, e.g. $L = K - U$. For mechanical systems, $L = K - U$ just works, but for other domains, the Lagrangian should be a function that generates equations of motion. But how was $L = K - U$ first proposed? How did the author know that it just works? One could even ask, why distilling the substance of an object to be its energy? In our case, what could be the "energy variables" that captures the concept of "shape of a 3D object"? In a broad sense, in order for select the appropriate variables to abstractly represent some property, scientists start with making observations, followed by formulating theories, and finally refining the theories to capture more cases. This is the face-to-face confrontation method because you need special insights to propose something that will capture the hidden, intrinsic, inner workings of perception; as well as distilling the concept of 3D shape to be represented by a set of variables.
</p>
<p>
	The importance of picking an insight-provoking phenomena. To draw a parallel, in Physics, an object by itself does not offer much incentive to study. In other words, there is not enough perspective for physicists to come up with brilliant guesses on the underlying laws of the object. It is when objects are set into motion that a perspective opened up, which led to the proposal of characterizing dynamics or motion of systems by energy and momentum. That may be the reason for the field of mechanics to be one of the oldest branches in physics. Similarly, what are some phenomena that we can study when we set perception in "motion"? Then, subsequent questions may follow: What are the possible ways to describe perception? What have been tried? What should be the Lagrangian that generates the "motion" of perception, such that we can quantitatively compare the similarity between two percepts to check if two percepts are invariant?
</p>
<p>
	Verification step to check the legitimacy of Lagrangian (and the proposed abstraction of perception): check its number of symmetries. If the arrived percept does not depend on some variable $z$, then applying transformations along $z$ axis should have no impact on the dynamics under study (symmetric along the dimension).
</p>
<p>
	Possible critique on the solutions provided by this approach: why does the brain choose on that thing to be conserved (questions people tend to ask more when it comes to biological systems, but people don’t ask why is energy the quantity that is conserved)? You need a lot of experiments showing that the proposal is generalizable, so that it is shown, experiment-by-experiment, that it is the correct (an adequate) Lagrangian. 
</p>
<blockquote>
"It is important to realize that in physics today we have no knowledge of what energy is" &#8212; Richard Feynman (<a href="https://www.feynmanlectures.caltech.edu/I_04.html">Lecture 4: Conservation of Energy</a>)
</blockquote>



<header class="major">
    <h4>General approach 2: The patio door</h4>
</header>
<p>
	The indirect trial and error method:
	From observed symmetry, can we come up with a cost functional that exhibit similar behavior with the measured system? In other words, can we come up with cost functionals that reflect human behaviors, although the cost functional may not be the exact functional utilized by humans. The criterion for the propose cost functional would be that it assigns lowest cost to human solution, since the human solution is the nature-picked best solution with minimal cost. 
</p>
<p>
	From the cost functional that is minimized, how can we derive the conserved quantity? How do we come up with the Lagrangian given only the cost functional? 
</p>


<header class="major">
    <h4>General approach 3: The back door</h4>
</header>
<p>
	Is it possible to go from the direction of proving that the phenomena belongs to some finite symmetry group? This way we search for related works of applying Noether's theorem to that finite group, works done by others can be applied to the phenomena as well.
</p>
















