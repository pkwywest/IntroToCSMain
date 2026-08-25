<span class="section" id="why-python">
<h1><span class="section-number">1.2. </span>Why Python?<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/introduction/why-learn-python.html#why-python" title="Permalink to this headline">¶</a></h1>
<p>Most programmers have a favorite coding language, but there is NOT a single,
best choice. Each language does some things very well, other things pretty well, and
a few things not so well.</p>
<p>For most tasks, any programming language can do the job.
To pick which one to use, think about what each language does best and which languages you enjoy.
So why start with Python?</p>
<span class="section" id="python-is-a-friendly-first-language">
<h2><span class="section-number">1.2.1. </span>Python Is A Friendly First Language<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/introduction/why-learn-python.html#python-is-a-friendly-first-language" title="Permalink to this headline">¶</a></h2>
<span class="figure align-default">
<img src = "https://education.launchcode.org/lchs/_images/good-at-python.jpg" alt = "A comic where Harry Potter says, 'How am I so good at this? I've never written code before?'. He sits behind a silver computer with a Python book next to him. Ron is standing in the room with an iPad under his arm." >

</span>
<p>If you start typing “Why learn” into the Google search box, one of the top
auto-fill suggestions is “Why learn python”. If you continue your search, you
will likely find terms like <i>elegant</i>, <i>flexible</i>, <i>most loved</i>, <i>beginner
friendly</i>, and <i>in demand</i>.</p>
<p>Take a look at the following code samples, which select a random integer (whole
number) from 1 - 10 and then print it to the screen.</p>
<span class="admonition-examples admonition">
<h4>Examples</h4>
<p>Python:</p>
<span class="highlight-python notranslate"><table class="highlighttable"><tbody><tr><td class="linenos"><span class="linenodiv"></span></td><td class="code"><span class="highlight"><pre><span></span><span class="kn">import</span> <span class="nn">random</span>

<span class="n">number</span> <span class="o">=</span> <span class="n">random</span><span class="o">.</span><span class="n">randint</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">number</span><span class="p">)</span>
</pre></span>
</td></tr></tbody></table></span>

<p>JavaScript:</p>
<span class="highlight-JavaScript notranslate"><table class="highlighttable"><tbody><tr><td class="linenos"><span class="linenodiv"></span></td><td class="code"><span class="highlight"><pre><span></span><span class="kd">let</span> <span class="nx">number</span> <span class="o">=</span> <span class="nb">Math</span><span class="p">.</span><span class="nx">floor</span><span class="p">(</span><span class="nb">Math</span><span class="p">.</span><span class="nx">random</span><span class="p">()</span><span class="o">*</span><span class="mf">10</span><span class="p">)</span> <span class="o">+</span> <span class="mf">1</span><span class="p">;</span>
<span class="nx">console</span><span class="p">.</span><span class="nx">log</span><span class="p">(</span><span class="nx">number</span><span class="p">);</span>
</pre></span>
</td></tr></tbody></table></span>
<p>Java:</p>
<span class="last highlight-JavaScript notranslate"><table class="highlighttable"><tbody><tr><td class="linenos"><span class="linenodiv">

</span></td><td class="code"><span class="highlight"><pre>
<span class="nx">public</span> <span class="kd">class</span> <span class="nx">Main</span><span class="p">{</span>
   <span class="nx">public</span> <span class="k">static</span> <span class="k">void</span> <span class="nx">main</span><span class="p">(</span><span class="nb">String</span><span class="p">[]</span> <span class="nx">args</span><span class="p">){</span>

      
<span class="kr">int</span> <span class="nx">number</span><span class="p">;</span>

<span class="nx">number</span> <span class="o">=</span> <span class="p">(</span><span class="kr">int</span><span class="p">)</span> <span class="p">(</span><span class="nb">Math</span><span class="p">.</span><span class="nx">random</span><span class="p">()</span><span class="o">*</span><span class="mf">9</span><span class="p">)</span> <span class="o">+</span> <span class="mf">1</span><span class="p">;</span>

<span class="nx">System</span><span class="p">.</span><span class="nx">out</span><span class="p">.</span><span class="nx">println</span><span class="p">(</span><span class="nx">number</span><span class="p">);</span>

   <span class="p">}</span>
<span class="p">}</span>
</pre></span>
</td></tr></tbody></table></span>
</span>
<p>Each code sample does exactly the same thing, but the keywords that Python uses
are very similar to their English meanings. <code class="docutils literal notranslate"><span class="pre">random.randint(1,</span> <span class="pre">10)</span></code> can be
read as “select a random integer from 1 - 10”, and <code class="docutils literal notranslate"><span class="pre">print</span></code> does just what it
says. <code class="docutils literal notranslate"><span class="pre">console.log()</span></code> and <code class="docutils literal notranslate"><span class="pre">System.out.println()</span></code> are not as clear.
For this reason, new coders may find Python more readable than Java or JavaScript.</p>
</span>
<span class="section" id="python-does-lots-of-things">
<h2><span class="section-number">1.2.2. </span>Python Does Lots of Things<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/introduction/why-learn-python.html#python-does-lots-of-things" title="Permalink to this headline">¶</a></h2>
<span class="figure align-default">
<img src = "https://education.launchcode.org/lchs/_images/Perfect-Programmer.jpg" alt = "A snake is coding at a computer terminal in a cubicle. Two humans walk by talking to each other. One says to the other, 'That's Tony, our top programmer. His code is always perfect and bug free! I just don't know how he does it.'">

</span>
<p>Even though Python code gets described as “simple”, this is because the
language handles a lot of complexity for you. The nitty-gritty details occur
behind the scenes, allowing you to focus more on getting your ideas to work.
Plus, there is plenty of free, ready-made code that you can pull into your
own Python projects.</p>
<p>The hot topics in computing—machine learning, data analysis, web development,
cybersecurity, etc.—can all be done with Python.</p>
</span>
<span class="section" id="python-makes-it-easier-to-learn-other-languages">
<h2><span class="section-number">1.2.3. </span>Python Makes it Easier to Learn Other Languages<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/introduction/why-learn-python.html#python-makes-it-easier-to-learn-other-languages" title="Permalink to this headline">¶</a></h2>
<p>Once you learn how to code something in Python—like printing to the screen
or asking the user for input—you will recognize the same tasks when they
appear in Java, C++, JavaScript, etc. Even though the structure of the
languages might be unfamiliar, you will still have an idea of what the code is
doing.</p>
<p>This course is different from other ways you can learn Python. It focuses on
programming <i>fundamentals</i> and <i>thinking like a coder</i>. These skills apply to
ALL programming languages. Once you learn them for Python, you will be able to
reuse those skills when you switch to a different language.</p>
<p>The logic and problem-solving techniques necessary to write programs are
standard. We will teach you how to <i>code</i>. Python is simply the tool we use to
do it.</p>



