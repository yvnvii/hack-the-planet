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
					<li><a href="../tutorials/7.2-scripting.html">Tutorial 7.2</a>: scripting and execution</li>
					<li><a href="../tutorials/7.3-imports.html">Tutorial 7.3</a>: imports and modules</li>
					<li><a href="../tutorials/7.4-classes.html">Tutorial 7.4</a>: intro to classes</li>
				</ul>
			</li>
		</ul>
	</div>
</div>		


{% comment %}

Monday prep:
	- lecture:
		- dicts and sets.
		- standard lib, os and subprocess
	- notebooks:
		- 7.0: subprocess and docstrings.
		- 7.1: challenge functions.
	- tuturials:
		- 7.0: thinking functionally (links to notebooks)
		- 7.1: scripting setup (paired with videos)
		- 7.2: challenge: transfer and run script from editor.

Wednesday prep:
	- lecture:
		- style and linting.
		- game challenge demo.
	- reading on style.
	- notebooks:
		- 8.0: auto-stying with black extension.
	- tutorials:
		- linting challenge
		- game devel. challenge

{% endcomment %}




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
					<li><a href="https://www.python.org/dev/peps/pep-0008/">Read</a>: PEP 8</li>
					<li><a href="https://www.python.org/dev/peps/pep-0020/">Read</a>: Zen of Python</li>
					<li>You will receive an email when the tutorials are posted</li>
					<li><a href=>Tutorial 8.0</a>: black style</li>					
					<li><a href=>Tutorial 8.1</a>: pylint style</li>
					<li><a href=>Tutorial 8.2</a>: assessment</li>
					<li><a href=>Tutorial 8.3a</a>: sublimetext setup</li>
					<li><a href=>Tutorial 8.3b</a>: vscode setup</li>
					<li><a href=>Tutorial 8.4</a>: coding exercises I</li>					
				</ul>
			</li>
		</ul>
	</div>
</div>		

... More coming soon.
