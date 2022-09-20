<h1 class="gap">0x06. AirBnB clone - Web dynamic</h1>
<div class="panel-heading">
      <h3 class="panel-title">Concepts</h3>
    </div>
    <div class="panel-body">
      <p>
        <em>For this project, we expect you to look at this concept:</em>
      </p>

<ul>
    <li>
    <a href="/concepts/74">AirBnB clone</a>
    </li>
</ul>
</div>
<div class="panel panel-default" id="project-description">
  <div class="panel-body">
    <h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/P6NwDHW6mfJx6GmjNdKI6g" title="Selector" target="_blank">Selector</a> </li>
<li><a href="/rltoken/AK3NYPE-lPpFN5A68eZZuw" title="Get and set content" target="_blank">Get and set content</a> </li>
<li><a href="/rltoken/a0TkagyQoNbxU1PBmuPgEw" title="Manipulate CSS classes" target="_blank">Manipulate CSS classes</a> </li>
<li><a href="/rltoken/WgO2EKHiYtpTrTkTFh8zUQ" title="Manipulate DOM elements" target="_blank">Manipulate DOM elements</a> </li>
<li><a href="/rltoken/Rw8BNB0UlMAWwGdO5psitQ" title="Document ready" target="_blank">Document ready</a> </li>
<li><a href="/rltoken/zuFIy5a0EECbmL52IyGDsg" title="Introduction" target="_blank">Introduction</a> </li>
<li><a href="/rltoken/Z6evZd017rj-0wToO-8fVw" title="GET &amp; POST request" target="_blank">GET &amp; POST request</a> </li>
<li><a href="/rltoken/zbHt3dS-olwsNFXo5i7uNQ" title="HTTP access control (CORS)" target="_blank">HTTP access control (CORS)</a> </li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/EX07DBSW3o5_5pMCutImBQ" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>How cool it is to request your own API</li>
<li>How to modify an HTML element style</li>
<li>How to get and update an HTML element content</li>
<li>How to modify the DOM</li>
<li>How to make a <code>GET</code> request with JQuery Ajax</li>
<li>How to make a <code>POST</code> request with JQuery Ajax</li>
<li>How to listen/bind to DOM events</li>
<li>How to listen/bind to user events</li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be interpreted on Chrome (version 57.0)</li>
<li>All your files should end with a new line</li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>Your code should be <code>semistandard</code> compliant with the flag <code>--global $</code>: <code>semistandard *.js --global $</code></li>
<li>All your JavaScript must be in the folder <code>scripts</code></li>
<li>You must use JQuery version 3.x</li>
<li>You are not allowed to use <code>var</code></li>
<li>HTML should not reload for each action: DOM manipulation, update values, fetch data…</li>
</ul>

<h3>GitHub</h3>

<p><strong>There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.</strong></p>

<h2>More Info</h2>

<h3>Import JQuery</h3>

<pre><code>&lt;head&gt;
    &lt;script src="https://code.jquery.com/jquery-3.2.1.min.js"&gt;&lt;/script&gt;
&lt;/head&gt;
</code></pre>

<h3>Before starting the project…</h3>

<p>You will work on a codebase using <a href="/rltoken/upM-mIveswewkkkonuhDhQ" title="Flasgger" target="_blank">Flasgger</a>, you will need to install it locally first before starting the RestAPI:</p>

<pre><code>$ sudo apt-get install -y python3-lxml
$ sudo pip3 install flask_cors # if it was not installed yet
$ sudo pip3 install flasgger
</code></pre>

<p>If the RestAPI is not starting, please read the error message. 
Based on the(ses) error message(s), you will have to troubleshoot potential dependencies issues. </p>

<p>Here some solutions:</p>

<h4><code>jsonschema</code> exception</h4>

<pre><code>$ sudo pip3 uninstall -y jsonschema 
$ sudo pip3 install jsonschema==3.0.1
</code></pre>

<h4><code>No module named 'pathlib2'</code></h4>

<pre><code>$ sudo pip3 install pathlib2
</code></pre>

<h3>Expose ports from your Vagrant</h3>

<p>In your <code>Vagrantfile</code>, add this line for each port forwarded</p>

<pre><code># I expose the port 5001 of my vm to the port 5001 on my computer
config.vm.network :forwarded_port, guest: 5001, host: 5001 
</code></pre>

<p>if you need to expose other ports, same line but you will need to replace the “guest port” (inside your vagrant) and your “host port” (outside your vagrant, used from your browser for example)</p>

<p>It’s important in your project, to use the AirBnB API with the port <code>5001</code></p>

<p><br>
<br>
<img src="https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step5.png" alt="" loading="lazy" style=""></p>

<h3>Manual QA Review</h3>

<p><strong>It is your responsibility to request a review for this project from a peer before the project’s deadline. If no peers have been reviewed, you should request a review from a TA or staff member.</strong></p>

  </div>
</div>
