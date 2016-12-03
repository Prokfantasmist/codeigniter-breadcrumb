# codeigniter-breadcrumb
Codeigniter Breadcrumb


<h5>Installation</h5>
<ul>
<li>Put Breadcrumbs.php in application/library folder</li>
<li>Put breadcrumbs.php in application/config folder</li>
</ul>


<pre><code><h6>** Load Breadcrumbs</h6>
$this-&gt;load-&gt;library('breadcrumbs');
<hr>
<h6>** Add breadcrumbs</h6>
$this-&gt;breadcrumbs-&gt;push('Area', '/area');
$this-&gt;breadcrumbs-&gt;push('Sample', '/area/sample');
<hr>
<h6>** Unshift crumb</h6>
$this-&gt;breadcrumbs-&gt;unshift('Sample', '/');
<hr>
<h6>** Output</h6>
$this-&gt;breadcrumbs-&gt;show();
</code></pre>
