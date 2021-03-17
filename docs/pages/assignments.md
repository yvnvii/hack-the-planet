---
layout: default
image: /assets/images/hackers-1.jpg
---


{% comment %}
{% for session in site.data.assignments %}
<div class="card mb-3">
	{% assign row = site.data.assignments[0] %}
	{{ row | inspect }}
	<div class="card-header">
		<h5 class="mb-0"> {{ session[1] }} </h5>
	</div>
	<div class="card-body">
		...
	</div>
</div>
{% endfor %}
{% endcomment %}


<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 1 <small class="float-right mt-1">1/11/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Introductions and explanation of the Syllabus. Describe the <i>ethos</i> and goals of this class. Why learn to program? What is programming?</li>
			<li>In class:
				<ul>
					<li><a href="../lectures/1.0">Lecture 1</a>: programming ethos.</li>
					<li><a href="https://mybinder.org/v2/gh/eaton-lab/hack-the-planet/HEAD?filepath=notebooks">Connect to binder notebook server</a>: (1.1. introduction to jupyter notebook.)</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://forms.gle/hJs3v5v6a5h7K76j6">Poll: on your experience with programming.</a></li>
					<li><a href="https://www.youtube.com/watch?v=tc4ROCJYbm0&t=1290s">Watch: Unix history video (Only watch up to 21:30).</a></li>
					<li><a href="https://ryanstutorials.net/linuxtutorial/navigation.php">Read linux tutorial sections 1-5.</a> If you are on Windows and do not have WSL2 installed, then wait until next class before installing. For now, use these instructions to connect to a Linux terminal in the cloud to practice exercises in these readings.</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		


<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 2 <small class="float-right mt-1">1/13/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objectives: poll, filepaths, bash advanced, PATH</li>
			<li>In class:
				<ul>
					<li><a href="../lectures/2.0">Lecture 2.0</a>: program design.</li>
					<li><a href="../lectures/2.1">Lecture 2.1</a>: bash advanced, GitHub.</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://eaton-lab.org/hack-the-planet/tutorials/2.0-github.html">Tutorial 2.0</a>: GitHub init</li>
					<li><a href="https://eaton-lab.org/hack-the-planet/tutorials/2.1-path.html">Tutorial 2.1</a>: bash lession</li>
					<li><a href="https://mybinder.org/v2/gh/eaton-lab/hack-the-planet/HEAD?filepath=notebooks">Notebook 2.0</a>: bash assessment</li>
				</ul>
			</li>
			<li>Before Wednesday (<b>Windows users only</b>):
				<ul>
					<li>Try to install Windows Subsystem for Linux 2.</li>
					<li><a href="https://www.youtube.com/watch?v=_fntjriRe48">graphical tutorial</a> (Note: Only follow instructions up to 6:20. make sure when you create a username that does not have any spaces in it. Only install WSL2 and Ubuntu 20.04, do not follow instructions after 6:20 where he installs additional versions.)</li>
					<li><a href="https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10">alternative command line tutorial</a></li>
					<li>If problems, please join office hours at the Canvas zoom link on Friday 1/15 at 3pm, or Tues 1/19 at 10am.</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		


<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 3 <small class="float-right mt-1">1/18/2021</small></h5>		
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>No Class; University holiday</li>
		</ul>
	</div>
</div>		



<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 4 <small class="float-right mt-1">1/20/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: git, GitHub, WSL2, coding editors</li>
			<li>In class:
				<ul>
					<li>Interactive review and introduction to git. (See zoom recording).</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="../tutorials/4.0-markdown.html">Tutorial 4.0</a>: Markdown revisited.</li>
					<li><a href="../tutorials/4.1-learning-git.html">Tutorial 4.1</a>: Learning git.</li>
					<li><a href="../tutorials/4.2-github-pages.html">Tutorial 4.2</a>: Create a GitHub pages website.</li>
					{% comment %}- [Tutorial 4.3:] Not due Monday, coming soon. SublimeText3 tutorial.{% endcomment %}
					{% comment %}- [Tutorial 4.4:] Not due Monday, coming soon. VSCode tutorial.	{% endcomment %}
				</ul>
			</li>
		</ul>
	</div>
</div>		


<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 5 <small class="float-right mt-1">1/25/2021</small></h5>		
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Installing Python and other packages with conda; using jupyter; 
			and intro to Python</li>
			<li>In class:
				<ul>
					<li>GitHub pages breakout sessions</li>
					<li><a href="../lectures/5.0/">Lecture 5.0</a>: Python intro.</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="../tutorials/5.0-conda.html">Tutorial 5.0</a>: conda.</li>
					<li><a href="../tutorials/5.1-jupyter.html">Tutorial 5.1</a>: jupyter</li>
					<li><a href="https://docs.python.org/3/tutorial/">Read</a>: Python tutorial chapters 1 and 3</li>
					<li><a href="../tutorials/5.2-forking.html">Tutorial 5.2</a>: GitHub forking and Python assessment</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		




<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 6 <small class="float-right mt-1">1/27/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: When to use different Python types, how to understand 
			exceptions and how to control flow with loops and conditionals.</li>
			<li>In class:
				<ul>
					<li><a href="../lectures/6.0/">Lecture 6.0</a>: Python types, exceptions and flow.</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://docs.python.org/3/tutorial/">Read</a>: Python tutorial chapters 4-5</li>
					<li><a href="../tutorials/6.0-python-advanced.html">Tutorial 6.0</a>: Python advanced</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		


<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 7 <small class="float-right mt-1">2/1/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			{% comment %}<li>Date: 2/1/2021 (Mon.)</li>{% endcomment %}
			<li>Learning objective: Learning to solve problems.</li>
			<li>In class:
				<ul>
					<li>interactive discussion</li>
					<!-- <li><a href="#">Lecture 7.0</a>: Python stdlib and scripting.</li> -->
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="../tutorials/7.0-subprocess.html">Tutorial 7.0</a>: subprocess notebook</li>
					<li><a href="../tutorials/7.1-think.html">Tutorial 7.1</a>: thinking functionally</li>
					<!-- Next time be more clear about CLI as an optional interface, perhaps use Click -->
					<li><a href="../tutorials/7.2-scripting.html">Tutorial 7.2</a>: scripting and execution</li>
					<li><a href="../tutorials/7.3-imports.html">Tutorial 7.3</a>: imports and modules</li>
					<li><a href="../tutorials/7.4-classes.html">Tutorial 7.4</a>: intro to classes</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		



<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 8 <small class="float-right mt-1">2/3/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Python classes and Python style guide.</li>
			<li>In class:
				<ul>
					<li><a href="../lectures/8.0">Lecture 8.0</a>: Scripting review, style introduction.</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://www.python.org/dev/peps/pep-0020/">Read</a>: Zen of Python</li>
					<li><a href="https://docs.python-guide.org/writing/style/">Read</a>: Python Style</li>
					<li><a href="../tutorials/8.0-style.html">Tutorial 8.0</a>: black style</li>
				</ul>
			</li>
		</ul>
	</div>
</div>



<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 9 <small class="float-right mt-1">2/8/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Review of Python scripting</li>
			<li>In class:
				<ul>
					<li>Lecture 9.0: interactive coding demonstration (see zoom recording).</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="../tutorials/9.0a-sublimetext3.html">Tutorial 9.0a</a>: sublimetext setup</li>
					<li><a href="../tutorials/9.0b-vscode.html">Tutorial 9.0b</a>: vscode setup</li>
					<li><a href="../tutorials/9.1-exercise.html">Tutorial 9.1</a>: editor linting/building/packaging challenge</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		



<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 10 <small class="float-right mt-1">2/10/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Python Data Science</li>
			<li>In class:
				<ul>
					<li><a href="../lectures/10.0/">Lecture 10.0: Numpy and Pandas</a></li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://jakevdp.github.io/PythonDataScienceHandbook/">Python Data Science Handbook chapters 2 & 3</a></li>
					<li><a href="https://mybinder.org/v2/gh/eaton-lab/hack-the-planet/HEAD?filepath=notebooks">Practice binder notebooks (10.0, 10.1, 10.2)</a></li>
					<li><a href="../tutorials/10.0-data-science.html">Tutorial 10.0</a>: data science project</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		



<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 11 <small class="float-right mt-1">2/15/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Project planning</li>
			<li>In class:
				<ul>
					<li><a href="../lectures/11.0/">Lecture 11.0: Numpy/Pandas review</a></li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://jakevdp.github.io/PythonDataScienceHandbook/">Python Data Science Handbook chapter 4</a></li>
					<li><a href="../tutorials/project-planning-1.html">Project planning 1</a></li>
					<li><a href="../tutorials/project-planning-2.html">Project planning 2</a></li>
				</ul>
			</li>
		</ul>
	</div>
</div>		




<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 12 <small class="float-right mt-1">2/17/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Python REST API and data</li>
			<li>In class:
				<ul>
					<li><a href="../lectures/12.0/">Lecture 12.0: REST API</a></li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://mybinder.org/v2/gh/eaton-lab/hack-the-planet/HEAD?filepath=notebooks">Binder notebook (12.0)</a></li>
					<li><a href="../tutorials/12.0-fastapi.html">Tutorial 12.0: Python REST API</a></li>
				</ul>
			</li>
		</ul>
	</div>
</div>		




<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 13 <small class="float-right mt-1">2/22/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Project planning</li>
			<li>In class:
				<ul>
					<li>Lecture 13.0: Review and projects</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li>Review: git, argparse, linters</li>
					<!-- <li>Midpoint assessment poll</li> -->
					<li>Turning our focus back to source code</li>
					<li><a href="./proposals.html">Project proposals</a></li>
				</ul>
			</li>
		</ul>
	</div>
</div>		




<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 14 <small class="float-right mt-1">2/24/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Project planning</li>
			<li>In class:
				<ul>
					<li>Lecture 14.0: Review and projects</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li>Collaboration and project discussions</li>
					<li><a href="https://mybinder.org/v2/gh/eaton-lab/hack-the-planet/HEAD?filepath=notebooks">Binder notebook (14.0)</a></li>
					<li><a href="../tutorials/nb-14.0-challenges.html">Solutions</a></li>
				</ul>
			</li>
		</ul>
	</div>
</div>		






<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 15 <small class="float-right mt-1">3/8/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Git collaboration</li>
			<li>In class:
				<ul>
					<li>Notebook assignment review</li>
					<li>git collaboration example</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="../tutorials/15.0-git-collab.html">git collab info</a></li>
					<li><a href="../tutorials/15.1-git-collab-assign.html">git collab assignment</a></li>		
				</ul>
			</li>
		</ul>
	</div>
</div>		




<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 16 <small class="float-right mt-1">3/15/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Git conflicts</li>
			<li>In class:
				<ul>
					<li>git collaboration discussions</li>
					<li>git conflict example</li>					
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="../tutorials/16.0-git-conflict.html">git conflicts</a></li>
				</ul>
			</li>
		</ul>
	</div>
</div>		





<div class="card mb-4">
	<div class="card-header">
		<h5 class="mb-0">Session 17 <small class="float-right mt-1">3/17/2021</small></h5>
	</div>
	<div class="card-body">
		<ul class="mb-0">
			<li>Learning objective: Project structure</li>
			<li>In class:
				<ul>
					<li>Eaton lab repos walkthrough</li>
				</ul>
			</li>
			<li>Assignment:
				<ul>
					<li><a href="https://realpython.com/python-concurrency/">Reading: Python concurrency</a></li>
					<li><a href="https://loguru.readthedocs.io/en/stable/index.html">Reading: Python logging</a></li>					
					<li><a href="../tutorials/17.0-minimal-working.html">minimal working example</a></li>
				</ul>
			</li>
		</ul>
	</div>
</div>		

