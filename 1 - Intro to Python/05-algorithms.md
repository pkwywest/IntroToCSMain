<span class="section" id="algorithms">
<h1><span class="section-number">2.1. </span>Algorithms<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/how-programs-work/algorithms.html#algorithms" title="Permalink to this headline">¶</a></h1>
<p>Have you ever alphabetized a stack of papers or a list of words? Did you sing
the alphabet song while you were performing the task? Did you sort the words
into groups based on the first letter? Did you “fan” the papers so you could
look at all of the names as you organized the stack? Did you get help from a
partner and split the task in half?</p>
<p>Regardless of how you completed the task, you probably followed a <i>pattern</i> to
make the process easier. If you had to repeat the task with a new set of words,
you could jump right in and follow the same pattern.</p>
<p id="index-0">The word <strong>algorithm</strong> is just a fancy name for a pattern or set of steps that
solve a specific problem.</p>
<span class="section" id="algorithms-are-easy-to-find">
<h2><span class="section-number">2.1.1. </span>Algorithms Are Easy to Find<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/how-programs-work/algorithms.html#algorithms-are-easy-to-find" title="Permalink to this headline">¶</a></h2>
<p>Imagine a recipe for baking cookies. After the list of ingredients comes a
series of step-by-step instructions for making the treats. If you want to cook
something else, like a cake or a roast, you follow a different set of steps
using a different set of ingredients.</p>
<p>An <i>algorithm</i> is like a recipe. It is a careful series of steps that, when
followed, produce a specific result. Programmers create algorithms to
accomplish small tasks. By combining many separate, small tasks, programmers
build larger applications.</p>
<span class="section" id="for-example">
<h3><span class="section-number">2.1.1.1. </span>For Example<a class="headerlink" href="#for-example" title="Permalink to this headline">¶</a></h3>
<p>Let’s take a look at alphabetizing a list of words:</p>
<p><code class="docutils literal notranslate"><span class="pre">apple,</span> <span class="pre">pear,</span> <span class="pre">zebra,</span> <span class="pre">box,</span> <span class="pre">rutabaga,</span> <span class="pre">fox,</span> <span class="pre">banana,</span> <span class="pre">socks,</span> <span class="pre">foot</span></code></p>
<p>Here is one way to complete the task:</p>
<ol class="arabic">
<li><p>Arrange the words from a - z based only on the first letter:</p>
<p><code class="docutils literal notranslate"><span class="pre">apple,</span> <span class="pre">box,</span> <span class="pre">banana,</span> <span class="pre">fox,</span> <span class="pre">foot,</span> <span class="pre">pear,</span> <span class="pre">rutabaga,</span> <span class="pre">socks,</span> <span class="pre">zebra</span></code></p>
</li>
<li><p>If more than one word starts with ‘a’, rearrange those words based on the
second letter. Repeat for the words that start with ‘b’, then ‘c’, etc.:</p>
<p><code class="docutils literal notranslate"><span class="pre">apple,</span> <span class="pre">banana,</span> <span class="pre">box,</span> <span class="pre">fox,</span> <span class="pre">foot,</span> <span class="pre">pear,</span> <span class="pre">rutabaga,</span> <span class="pre">socks,</span> <span class="pre">zebra</span></code></p>
</li>
<li><p>If multiple words start with ‘a’ and have the same second letter, rearrange
those words based on the third letter. Repeat for the ‘b’ words, then the
‘c’ words, etc.:</p>
<p><code class="docutils literal notranslate"><span class="pre">apple,</span> <span class="pre">banana,</span> <span class="pre">box,</span> <span class="pre">foot,</span> <span class="pre">fox,</span> <span class="pre">pear,</span> <span class="pre">rutabaga,</span> <span class="pre">socks,</span> <span class="pre">zebra</span></code></p>
</li>
<li><p>If other repeats exist, continue sorting the list by comparing the 4th, 5th,
6th letters (etc.) until all the words are properly arranged.</p></li>
</ol>
<p>This is not the ONLY way to solve the task, but it provides a series of steps
that can be used in many different situations to organize different lists of
words.</p>
<p>Alphabetizing is a process we can teach a computer to do, and the algorithm
will complete the process much more rapidly than a human.</p>
</span>
</span>
<span class="section" id="algorithms-do-many-things">
<h2><span class="section-number">2.1.2. </span>Algorithms Do Many Things<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/how-programs-work/algorithms.html#algorithms-do-many-things" title="Permalink to this headline">¶</a></h2>
<p>Cookbooks contain pages and pages of algorithms. Following 2 or 3 of these
produces a nice dinner plus dessert. Programmers use this same idea, only they
work with devices instead of food.</p>
<p>Every algorithm is designed to do one small job. Combining different algorithms
together allows programmers to solve much more complicated problems.</p>
<ol class="arabic">
<li><p>Have you ever used the “You may also like…” option when looking at movies
or books online? Algorithms take your past choices and use them to recommend
new titles.</p></li>
<li><p>In 2019, astronomers took X-ray data collected by NASA and used algorithms
to create the first image ever taken of a black hole.</p>
<span class="figure align-default">

</span>
![image description goes here](https://www.nasa.gov/sites/default/files/styles/full_width/public/thumbnails/image/blackhole.png?itok=THJrwcHP)
<p><a class="reference external" href="https://www.nasa.gov/mission_pages/chandra/news/black-hole-image-makes-history" target="_blank">https://www.nasa.gov/mission_pages/chandra/news/black-hole-image-makes-history<i class="fas fa-external-link-alt" aria-hidden="true"></i></a></p>
</li>
<li><p>The apps on a phone are just combinations of algorithms working together to
do a job. Applying a filter to a photo, playing a game with users across
the world, or just calling mom all result from carefully designed sets of
instructions.</p></li>
</ol>
<p>Programmers can do so many things with computers, but the devices are useless
unless we give them algorithms to follow.</p>
</span>
</span>

