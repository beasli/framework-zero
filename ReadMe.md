<div style="text-align: center; padding: 20px;">
    <img src="https://beasli.github.io/framework-zero/images/logo.png" alt="Framework Zero Logo">
</div>

<div style="padding-inline: 25%;">
<!-- Introduction -->
<h2 style="margin-block: 20px;">Introduction</h2>
<p>
    Framework Zero is a JavaScript-based frontend framework developed by Er. Shubham Sharma. It's designed for creating fast and component-based web projects that can be run on shared servers as plain HTML, CSS, and JavaScript projects.
</p>

<!-- Getting Started Section -->
<h2 style="margin-block: 20px;">Getting Started</h2>

<h3 style="margin-block: 20px;">Prerequisites</h3>
<p>Before you begin, ensure you have the following installed:</p>
<ul>
    <li>Node.js: <a href="https://nodejs.org/" target="_blank">Download Node.js</a></li>
</ul>

<h3 style="margin-block: 20px;">Installation</h3>
<ol>
    <li>Clone the Framework Zero repository:</li>
</ol>
<pre style="background: black;padding: 20px;border-radius: 10px;"><code style="color: #76f476 !important;">git clone https://github.com/beasli/framework-zero.git</code></pre>
<ol start="2">
    <li>Change to the project directory:</li>
</ol>
<pre style="background: black;padding: 20px;border-radius: 10px;"><code style="color: #76f476 !important;">cd framework-zero</code></pre>
<ol start="3">
    <li>Install the required Node.js packages:</li>
</ol>
<pre style="background: black;padding: 20px;border-radius: 10px;"><code style="color: #76f476 !important;">npm install</code></pre>

<h3 style="margin-block: 20px;">Configuration</h3>
<p>In the <code>config.json</code> file, define the following environment-specific variables:</p>
<ul>
    <li><code>API_BASE_URL</code>: The base URL for your API.</li>
    <li><code>BASE_URL</code>: The base URL for your web application.</li>
</ul>

<h2 style="margin-block: 20px;">Usage</h2>

<h3 style="margin-block: 20px;">Development</h3>
<p>To compile the code to the <code>dist</code> folder for local development, run:</p>
<pre style="background: black;padding: 20px;border-radius: 10px;"><code style="color: #76f476 !important;">gulp</code></pre>

<h3 style="margin-block: 20px;">Local Configuration</h3>
<p>To compile the code to the <code>dist</code> folder with a local configuration, run:</p>
<pre style="background: black;padding: 20px;border-radius: 10px;"><code style="color: #76f476 !important;">gulp --env=local</code></pre>

<h3 style="margin-block: 20px;">Production Configuration</h3>
<p>To compile the code to the <code>dist</code> folder with a production configuration, run:</p>
<pre style="background: black;padding: 20px;border-radius: 10px;"><code style="color: #76f476 !important;">gulp --env=prod</code></pre>

<h3 style="margin-block: 20px;">Generating a New Component</h3>
<p>To generate a new component, run:</p>
<pre style="background: black;padding: 20px;border-radius: 10px;"><code style="color: #76f476 !important;">gulp component --name=&lt;component-name&gt;</code></pre>
<p>Replace <code>&lt;component-name&gt;</code> with the desired name for your new component.</p>


</div>
