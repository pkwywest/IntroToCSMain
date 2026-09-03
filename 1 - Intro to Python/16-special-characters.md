<span class="section" id="special-characters">
<h1>7.6. Special Characters<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/strings/special-characters.html?highlight=newline#special-characters" title="Permalink to this headline">¶</a></h1>
<p id="index-0">Aside from letters, numbers, and symbols, there is another class of characters
we can use in strings, known as <strong>special characters</strong>. These characters
involve special codes that all begin with a <code class="docutils literal notranslate"><span class="pre">\</span></code> (backslash). Special
characters allow us to include control characters, whitespace characters, and
items that do not appear on our keyboards (like shapes or emojis).</p>
<span class="section" id="newline-and-tab">
<h2>7.6.1. <span class="highlighted">Newline</span> and Tab<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/strings/special-characters.html?highlight=newline#newline-and-tab" title="Permalink to this headline">¶</a></h2>
<p>Two commonly used special characters are <code class="docutils literal notranslate"><span class="pre">\n</span></code> and <code class="docutils literal notranslate"><span class="pre">\t</span></code>, which are the
<span class="highlighted">newline</span> and tab characters, respectively. A <strong><span class="highlighted">newline</span></strong> represents tapping the
<i>Return</i> or <i>Enter</i> key while typing.</p>
<h4>Example</h4>
<span class="highlight-python notranslate"><span class="highlight"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s2">"A message,</span><span class="se">\n</span><span class="s2">broken across lines,</span><span class="se">\n\t</span><span class="s2">and indented."</span><span class="p">)</span>
</pre></span>
</span>
<p><strong>Console Output</strong></p>
<span class="last highlight-none notranslate"><span class="highlight"><pre><span></span>A message,
broken across lines,
   and indented.
</pre></span>
</span>
</span>
<h4>Try It!</h4>
<p>Modify the code in the editor below to produce this output:</p>

<span class="highlight-none notranslate"><span class="highlight"><pre><span></span>Use <span class="highlighted">newline</span>
   and tab
      characters to
         create this
      output with
   a single
print statement.
</pre></span>

</span>

```python.run
# Use the special characters for newline and tab to produce the indented, multi-line output shown in the instructions.

print('Use newline and tab characters to create this output with a single print statement.')
```


</span>

<span class="section" id="other-characters">
<span id="unicode"></span><h2>7.6.2. Other Characters<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/strings/special-characters.html?highlight=newline#other-characters" title="Permalink to this headline">¶</a></h2>
<p id="index-1">We can also add characters to a string that do not appear on all keyboards.
These <strong>Unicode characters</strong> use combinations of the form <code class="docutils literal notranslate"><span class="pre">\uXXXX</span></code>, where the
four Xs are numbers or letters that stand for a particular symbol. This allows
us to use character sets that don’t use the Latin letters (A-Z), such as Greek,
Cyrillic, and Arabic, as well as a wide array of non-letter symbols.</p>
<h4>Example:</h4>
<span class="highlight-python notranslate"><span class="highlight"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">'</span><span class="se">\u25E8</span><span class="s1">     </span><span class="se">\u26BD</span><span class="s1">     </span><span class="se">\u26A1</span><span class="s1">'</span><span class="p">)</span>
</pre></span>
</span>
<p><strong>Console Output</strong></p>
<span class="last highlight-none notranslate"><span class="highlight"><pre><span></span>◨     ⚽     ⚡
</pre></span>
</span>

<p>For a complete listing of codes, check out this
<a class="reference external" href="https://unicode-table.com/en/" target="_blank">Unicode table<i class="fas fa-external-link-alt" aria-hidden="true"></i></a>.</p>
</span>
<span class="section" id="check-your-understanding">
<h2>7.6.3. Check Your Understanding<a class="headerlink" href="https://education.launchcode.org/lchs/chapters/strings/special-characters.html?highlight=newline#check-your-understanding" title="Permalink to this headline">¶</a></h2>

Go to [the textbook](https://education.launchcode.org/lchs/chapters/strings/special-characters.html?highlight=newline#check-your-understanding) to CYU

</span>

