<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd"> 
<html lang="en">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" /> 
	<title>Blog &raquo; Debuggable - Node.js Consulting</title>

	<link href="http://feeds.feedburner.com/debuggable" type="application/rss+xml" rel="alternate" title="RSS 2.0" />	<link rel="pingback" href="Debuggable.com/pingback" />
	<link rel="stylesheet" type="text/css" href="/css/aggregate/58a4727fb2207154ddd0739cbc3b15104ad6cd03/4026ee2275e22a4e5ec8aea13747c557.php" /></head>
	<body>
		<div class="container_16">
			<h1 id="logo-text"><a href="/">debuggable</a></h1>
			<ul id="navigation">
				<ul>
<li class="active"><a href="/blog">Blog</a></li><li class=""><a href="/">About</a></li></ul>			</ul>
			<div class="clear">&nbsp;</div>

			<div id="blueprint">
				<a href="/contact" class="contact">Contact Us</a>			</div>

			<div class="clear">&nbsp;</div>
			<div class="grid_11 alpha" id="content">
	<cake:nocache>
			<div class="messages empty"></div>
	</cake:nocache>
	
	<div class="post">
	<h2><a href="/posts/releasing-node-mysql-2-0-0-alpha:4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb">Releasing node-mysql 2.0.0-alpha</a></h2>	<div class="posted-on">
		<p>Posted on 15/5/12 by 
		<a href="/felix">Felix Geisendörfer</a>				</p>
		<div class="thumb">
			<img alt="" src="/img/felix_thumb.jpg"/>		</div>
	</div>
	<div class="body">
				<p>Today I am releasing an alpha version of <a href="https://github.com/felixge/node-mysql">node-mysql v2.0</a>. If you are using
v0.9.x at this point, I highly encourage you to try it out, as now is your best
chance to influence the API and features of the final release.</p>

<p>To install the new version, do:</p>

<pre class="terminal">
npm install mysql@2.0.0-alpha
</pre>

<p>Then check out the <a href="https://github.com/felixge/node-mysql/blob/master/Changes.md#v200-alpha-2012-05-15">Upgrading Guide</a> and adjust your code as needed.</p>

<p>After that make sure to join the new <a href="https://groups.google.com/forum/?fromgroups#!forum/node-mysql">mailing list</a> or #node-mysql IRC
channel to provide any feedback you may have.</p>

<p>This new version comes with a few exciting improvements:</p>

<ul>
<li>~5x faster than v0.9.x for parsing query results</li>
<li>Support for <code>pause()</code> / <code>resume()</code> (for streaming rows)</li>
<li>Support for multiple statement queries</li>
<li>Support for stored procedures</li>
<li>Support for transactions</li>
<li>Support for binary columns (as blobs)</li>
<li>Consistent &amp; well documented error handling</li>
<li>A new Connection class that has well defined semantics (unlike the old Client class).</li>
<li>Convenient escaping of objects / arrays that allows for simpler query construction</li>
<li>A significantly simpler code base</li>
<li>Many bug fixes &amp; other small improvements (Closed 62 out of 66 GitHub issues)</li>
</ul>

<p>I have been working on this new version for quite some time, but only now was
able to complete the final work thanks to my amazing new sponsors:</p>

<ul>
<li><a href="http://www.holidayextras.co.uk/">HolidayExtras</a> (they are <a href="http://join.holidayextras.co.uk/vacancy/senior-web-technologist/">hiring</a>)</li>
<li><a href="http://newscope.com/">Newscope</a> (they are <a href="http://www.newscope.com/stellenangebote">hiring</a>)</li>
</ul>

<p>For those of you interested in the future of v0.9.x:</p>

<ul>
<li>There will be no v1.0 release, the way 0.9.x handles its queue and reconnect
mechanism are broken and not easily fixable without breaking BC.</li>
<li>I will merge critical bug fixes that come with tests and don't break BC.</li>
<li>There will be no major changes, especially features.</li>
</ul>

<p>Going forward, I also hope to find some time to write about:</p>

<ul>
<li>The new parser and what makes v2 so fast</li>
<li>The choice of rewriting vs. refactoring (I tried both)</li>
<li>My failed first attempt for a new parser design</li>
</ul>

<p>--fg</p>

<p><img style="display: none;" src="http://debuggable.com/posts/tick/4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb"></p>
	</div>
	<div class="clear">&nbsp;</div>
	<div class="social">
	<p class="subscribe">Did you like this blog post? If so, please consider <a href="http://feeds.feedburner.com/debuggable">subscribing to the Blog RSS feed</a>.</p>

	<ul>
	<li class="sociablefirst">
				<a class="linkedin" title="LinkedIn" href="javascript:window.location='http://www.linkedin.com/shareArticle?mini=true&amp;url=http%3A%2F%2Fdebuggable.com%2Fposts%2Freleasing-node-mysql-2-0-0-alpha%3A4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb &amp;title=Releasing+node-mysql+2.0.0-alpha';" rel="nofollow">
			<img class="sociable-hovers" alt="Linked In" title="Linked In" src="/img/social_icons/linkedin.png"/>
		</a>
	</li>
	<li>
		<a class="sphinn" title="Sphinn" href="javascript:window.location='http://sphinn.com/index.php?c=post&amp;m=submit&amp;link=http%3A%2F%2Fdebuggable.com%2Fposts%2Freleasing-node-mysql-2-0-0-alpha%3A4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb';" rel="nofollow">
		<img class="sociable-hovers" alt="Sphinn" title="Sphinn" src="/img/social_icons/sphinn.png"/>
		</a>
	</li>
	<li>
		<a class="digg" title="Digg" href="javascript:window.location='http://digg.com/submit?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Freleasing-node-mysql-2-0-0-alpha%3A4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb&amp;title=Releasing+node-mysql+2.0.0-alpha&amp;bodytext=+..&amp;media=News&amp;topic=Programming';" rel="nofollow">
		<img class="sociable-hovers" alt="Digg" title="Digg" src="/img/social_icons/digg.png"/>
		</a>
	</li>
	<li>
	<a class="del.icio.us" title="del.icio.us" href="javascript:window.location='http://delicious.com/post?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Freleasing-node-mysql-2-0-0-alpha%3A4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb&amp;title=Releasing+node-mysql+2.0.0-alpha';" rel="nofollow">
		<img class="sociable-hovers" alt="Delicious" title="Delicious" src="/img/social_icons/delicious.png"/>
	</a>
	</li>
	<li class="sociablelast">
		<a class="stumbleupon" title="StumbleUpon" href="javascript:window.location='http://www.stumbleupon.com/submit?url=http%253A%252F%252Fyoast.com%252F40-wordpress-optimisation-tips%252F&amp;title=40%2520WordPress%2520Optimisation%2520tips';" rel="nofollow">
		<img class="sociable-hovers" alt="StumbleUpon" title="StumbleUpon" src="/img/social_icons/stumbleupon.png"/>
		</a>
	</li>
	</ul>
</div>

	
	<div class="post-footer">
		<img src="/css/img/comments.png" alt="Comments"> <a href="/posts/releasing-node-mysql-2-0-0-alpha:4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb">2 Comments</a> &nbsp; | &nbsp; 
		<img src="/css/img/add_comment.png" alt="Add Comment"> <a href="/posts/releasing-node-mysql-2-0-0-alpha:4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb#CommentAddForm">Add Comment</a>	</div>
	</div>
<div class="post">
	<h2><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb">How to write jQuery plugins</a></h2>	<div class="posted-on">
		<p>Posted on 29/3/12 by 
		<a href="/tim">Tim Koschützki</a>				</p>
		<div class="thumb">
			<img alt="" src="/img/tim_thumb.jpg"/>		</div>
	</div>
	<div class="body">
				<p><a href="http://jquery.com">jQuery</a>, the most popular javascript library out there, is great for DOM abstraction. It allows you to encapsulate functionality into your own plugins, which
is a great way to write reusable code. However, jQuery's rules for writing plugins are very loose, which leads to different plugin development practices - some of which are pretty poor.</p>

<p>With this article I want to provide a simple plugin development pattern that will work in many situations. If the functionality you would like to encapsulate is large and really complex, jQuery plugins are probably not what you should use in the first place.
You'd rather use something like <a href="http://documentcloud.github.com/backbone/">BackboneJS</a> or <a href="http://javascriptmvc.com/docs.html#!jQuery.Controller">jQuery.Controller</a> in this case.</p>

<p>If you can't or don't want to use Backbone, you might still get away with my solution ...</p>

<h2>Starting off</h2>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="co1">// plugin code will come here</span><br />
<br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;</div></p>

<p>The semi-colon before the function invocation keeps the plugin from breaking if our plugin is concatenated with other scripts that are not closed properly.</p>

<p>"use strict"; puts our code into strict mode, which catches some common coding problems by throwing exceptions, prevents/throws errors when relatively "unsafe" actions are taken and disables Javascript features that are confusing or poorly thought out.
To read about this in detail, please check <a href="http://ejohn.org/blog/ecmascript-5-strict-mode-json-and-more/">ECMAScript 5 Strict Mode, JSON, and More</a> by John Resig.</p>

<p>Wrapping the jQuery object into the dollar sign via a closure avoids conflicts with other libraries that also use the dollar sign as an abbreviation.
window and document are passed through as local variables rather than as globals, because this speeds up the resolution process and can be more efficiently minified.</p>

<h2>Invoking our plugin</h2>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="kw2">function</span> Widget<span class="br0">&#40;</span>el, opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el &nbsp;= $<span class="br0">&#40;</span>el<span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">opts</span> = opts;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">init</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span><br />
<br />
&nbsp; Widget.<span class="me1">prototype</span>.<span class="me1">init</span> = <span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
<br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; $.<span class="me1">fn</span>.<span class="me1">widget</span> = <span class="kw2">function</span><span class="br0">&#40;</span>opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">return</span> <span class="kw1">this</span>.<span class="me1">each</span><span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; &nbsp; <span class="kw2">new</span> Widget<span class="br0">&#40;</span><span class="kw1">this</span>, opts<span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;<br />
<br />
$<span class="br0">&#40;</span><span class="st0">'#mywidget'</span><span class="br0">&#41;</span>.<span class="me1">widget</span><span class="br0">&#40;</span><span class="br0">&#123;</span>optionA: <span class="st0">'a'</span>, optionB: <span class="st0">'b'</span><span class="br0">&#125;</span><span class="br0">&#41;</span>;</div></p>

<p>We invoke our plugin on a jQuery object or jQuery set by simply calling our widget() method on it and pass it some options.
Never forget about "return this.each(function() { ... })" in order to not break the chain-ability of jQuery objects.</p>

<p>The main functionality of the plugin is encapsulated into a separate Widget class, which we instantiate for each member in our jQuery set. Now all functionality is encapsulated in these wrapper objects.
The constructor is designed to just keep track of the passed options and the DOM element that the widget was initialized on.</p>

<p>You could also keep track of more sub-elements here to avoid having to always .find() them (think of performance) as you need them:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="kw2">function</span> Widget<span class="br0">&#40;</span>el, opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el &nbsp; &nbsp; = $<span class="br0">&#40;</span>el<span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">opts</span> &nbsp; &nbsp;= opts;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$header = <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.header'</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$body &nbsp; = <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.body'</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">init</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span><br />
<br />
&nbsp; <span class="co1">// ...</span><br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;</div></p>

<h2>Parsing options</h2>

<p>When we invoked the plugin we passed it some options. Often you need default options that you want to extend. This is how we bring the two together in our object's init() method:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="kw2">function</span> Widget<span class="br0">&#40;</span>el, opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el &nbsp;= $<span class="br0">&#40;</span>el<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">defaults</span> = <span class="br0">&#123;</span><br />
&nbsp; &nbsp; &nbsp; optionA: <span class="st0">'someOption'</span>,<br />
&nbsp; &nbsp; &nbsp; optionB: <span class="st0">'someOtherOption'</span><br />
&nbsp; &nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw2">var</span> meta &nbsp;= <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="st0">'widget-plugin-opts'</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">opts</span> = $.<span class="me1">extend</span><span class="br0">&#40;</span><span class="kw1">this</span>.<span class="me1">defaults</span>, opts, meta<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="co1">// ...</span><br />
&nbsp; <span class="br0">&#125;</span><br />
<br />
&nbsp; <span class="co1">// ...</span><br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;<br />
<br />
$<span class="br0">&#40;</span><span class="st0">'#mywidget'</span><span class="br0">&#41;</span>.<span class="me1">widget</span><span class="br0">&#40;</span><span class="br0">&#123;</span>optionA: <span class="st0">'a'</span>, optionB: <span class="st0">'b'</span><span class="br0">&#125;</span><span class="br0">&#41;</span>;</div></p>

<p>I like keeping the default options within the constructor of the wrapper class and not outside of it. This provides the flexibility to just take the whole wrapping class and copy it to somewhere else where you might not even have jQuery available.</p>

<p>If the element has options for us saved within its data attributes, we also want to take them into account. This is handy for when you have plugins that auto-initialize themselves (which we will do later) so that you have no way
to pass options to them via their plugin invocation.</p>

<p>Here is an example:</p>

<p><div class="clear"></div><div class="code debuggable_sh_html" style="white-space: wrap;white-space: nowrap;"><span class="sc2"><a href="http://december.com/html/4/element/div.html"><span class="kw2">&lt;div</span></a> <span class="kw3">class</span>=<span class="st0">&quot;widget js-widget&quot;</span> data-widget-plugin-opts=<span class="st0">&quot;{&quot;</span>optionA<span class="st0">&quot;:&quot;</span>someCoolOptionString<span class="st0">&quot;}&quot;</span><span class="kw2">&gt;</span></a></span></div></p>

<h2>Optional: Keeping a reference to our wrapper object in the element</h2>

<p>It's a good idea to keep a reference to our plugin object on the DOM element, because that helps a lot with debugging using your browser's javascript console later.
I don't always do this because it may just be overkill for the situation at hand. But I want to show you how to do this regardless:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="kw2">var</span> <span class="kw3">name</span> = <span class="st0">'js-widget'</span>;<br />
<br />
&nbsp; <span class="kw2">function</span> Widget<span class="br0">&#40;</span>el, opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el &nbsp;= $<span class="br0">&#40;</span>el<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">defaults</span> = <span class="br0">&#123;</span><br />
&nbsp; &nbsp; &nbsp; optionA: <span class="st0">'someOption'</span>,<br />
&nbsp; &nbsp; &nbsp; optionB: <span class="st0">'someOtherOption'</span><br />
&nbsp; &nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; &nbsp; <span class="co1">// let's use our name variable here as well for our meta options</span><br />
&nbsp; &nbsp; <span class="kw2">var</span> meta &nbsp;= <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="kw3">name</span> + <span class="st0">'-opts'</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">opts</span> = $.<span class="me1">extend</span><span class="br0">&#40;</span><span class="kw1">this</span>.<span class="me1">defaults</span>, opts, meta<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="kw3">name</span>, <span class="kw1">this</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="co1">// ...</span><br />
&nbsp; <span class="br0">&#125;</span><br />
<br />
&nbsp; <span class="co1">// ...</span><br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;<br />
<br />
$<span class="br0">&#40;</span><span class="st0">'#mywidget'</span><span class="br0">&#41;</span>.<span class="me1">widget</span><span class="br0">&#40;</span><span class="br0">&#123;</span>optionA: <span class="st0">'a'</span>, optionB: <span class="st0">'b'</span><span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
<br />
console.<span class="me1">log</span><span class="br0">&#40;</span>$<span class="br0">&#40;</span><span class="st0">'#mywidget'</span><span class="br0">&#41;</span>.<span class="me1">data</span><span class="br0">&#40;</span><span class="st0">'js-widget'</span><span class="br0">&#41;</span><span class="br0">&#41;</span>;</div></p>

<p>As you can see, we just expose our wrapper object using jQuery's $.data function. Easy.</p>

<h2>Binding some events</h2>

<p>Let's use our wrapper object's init() function to bind some events and write some real plugin code:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="kw2">var</span> <span class="kw3">name</span> = <span class="st0">'js-widget'</span>;<br />
<br />
&nbsp; <span class="kw2">function</span> Widget<span class="br0">&#40;</span>el, opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el &nbsp; &nbsp; &nbsp;= $<span class="br0">&#40;</span>el<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">defaults</span> = <span class="br0">&#123;</span><br />
&nbsp; &nbsp; &nbsp; optionA: <span class="st0">'someOption'</span>,<br />
&nbsp; &nbsp; &nbsp; optionB: <span class="st0">'someOtherOption'</span><br />
&nbsp; &nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw2">var</span> meta &nbsp; &nbsp; = <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="kw3">name</span> + <span class="st0">'-opts'</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">opts</span> &nbsp; &nbsp;= $.<span class="me1">extend</span><span class="br0">&#40;</span><span class="kw1">this</span>.<span class="me1">defaults</span>, opts, meta<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="kw3">name</span>, <span class="kw1">this</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$header = <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.header'</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$body &nbsp; = <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.body'</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span><br />
<br />
&nbsp; Widget.<span class="me1">prototype</span>.<span class="me1">init</span> = <span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw2">var</span> self = <span class="kw1">this</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$header.<span class="me1">on</span><span class="br0">&#40;</span><span class="st0">'click.'</span> + <span class="kw3">name</span>, <span class="st0">'.title'</span>, <span class="kw2">function</span><span class="br0">&#40;</span>e<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; &nbsp; e.<span class="me1">preventDefault</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; &nbsp; self.<span class="me1">editTitle</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$header.<span class="me1">on</span><span class="br0">&#40;</span><span class="st0">'change.'</span> + <span class="kw3">name</span>, <span class="st0">'select'</span>, <span class="kw2">function</span><span class="br0">&#40;</span>e<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; &nbsp; e.<span class="me1">preventDefault</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; &nbsp; self.<span class="me1">saveTitle</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; Widget.<span class="me1">prototype</span>.<span class="me1">editTitle</span> = <span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$header.<span class="me1">addClass</span><span class="br0">&#40;</span><span class="st0">'editing'</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; Widget.<span class="me1">prototype</span>.<span class="me1">saveTitle</span> = <span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw2">var</span> val = <span class="kw1">this</span>.$header.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.title'</span><span class="br0">&#41;</span>.<span class="me1">val</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="co1">// save val to database</span><br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$header.<span class="me1">removeClass</span><span class="br0">&#40;</span><span class="st0">'editing'</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; <span class="co1">// ...</span><br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;</div></p>

<p>Notice that we have bound the events via .on() in delegation mode, which means that our .title element doesn't even have to be in the DOM yet when the events are bound.
It's generally good practice to use event delegation, as you do not have to constantly bind/unbind events as elements are added/removed to/from the DOM.</p>

<p>We use our name variable as an event namespace here, which allows easy unbinding later without removing event listeners on the widget elements that were not bound using our plugin.</p>

<h2>How to prevent designers from breaking your plugins</h2>

<p>Something else that I like doing is attaching different classes to elements depending on if they are meant for css styling or for javascript functionality.</p>

<p>The markup that we could use for the plugin above could be:</p>

<p><div class="clear"></div><div class="code debuggable_sh_html" style="white-space: wrap;white-space: nowrap;"><span class="sc2"><a href="http://december.com/html/4/element/div.html"><span class="kw2">&lt;div</span></a> <span class="kw3">class</span>=<span class="st0">&quot;widget&quot;</span><span class="kw2">&gt;</span></a></span><br />
&nbsp; <span class="sc2"><a href="http://december.com/html/4/element/div.html"><span class="kw2">&lt;div</span></a> <span class="kw3">class</span>=<span class="st0">&quot;header&quot;</span><span class="kw2">&gt;</span></a></span><span class="sc2"><span class="kw2">&lt;/div&gt;</span></span><br />
&nbsp; <span class="sc2"><a href="http://december.com/html/4/element/div.html"><span class="kw2">&lt;div</span></a> <span class="kw3">class</span>=<span class="st0">&quot;body&quot;</span><span class="kw2">&gt;</span></a></span><span class="sc2"><span class="kw2">&lt;/div&gt;</span></span><br />
<span class="sc2"><span class="kw2">&lt;/div&gt;</span></span></div></p>

<p>And then we do:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
$<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; $<span class="br0">&#40;</span><span class="st0">'.widget'</span><span class="br0">&#41;</span>.<span class="me1">widget</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
<span class="br0">&#125;</span><span class="br0">&#41;</span>;</div></p>

<p>This is all fine and dandy, but now our designer comes along, changes the classes around, because he is not aware of our new plugin (or worse, he doesn't even care). This would break our client javascript functionality.
So what I often do is this instead:</p>

<p><div class="clear"></div><div class="code debuggable_sh_html" style="white-space: wrap;white-space: nowrap;"><span class="sc2"><a href="http://december.com/html/4/element/div.html"><span class="kw2">&lt;div</span></a> <span class="kw3">class</span>=<span class="st0">&quot;widget js-widget&quot;</span><span class="kw2">&gt;</span></a></span><br />
&nbsp; <span class="sc2"><a href="http://december.com/html/4/element/div.html"><span class="kw2">&lt;div</span></a> <span class="kw3">class</span>=<span class="st0">&quot;header js-header&quot;</span><span class="kw2">&gt;</span></a></span><span class="sc2"><span class="kw2">&lt;/div&gt;</span></span><br />
&nbsp; <span class="sc2"><a href="http://december.com/html/4/element/div.html"><span class="kw2">&lt;div</span></a> <span class="kw3">class</span>=<span class="st0">&quot;body js-body&quot;</span><span class="kw2">&gt;</span></a></span><span class="sc2"><span class="kw2">&lt;/div&gt;</span></span><br />
<span class="sc2"><span class="kw2">&lt;/div&gt;</span></span></div></p>

<p>Then in our plugin change how we find the body and header:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
<span class="kw2">function</span> Widget<span class="br0">&#40;</span>el, opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="kw1">this</span>.$el &nbsp; &nbsp; = $<span class="br0">&#40;</span>el<span class="br0">&#41;</span>;<br />
<br />
&nbsp; <span class="kw1">this</span>.<span class="me1">defaults</span> = <span class="br0">&#123;</span><br />
&nbsp; &nbsp; optionA: <span class="st0">'someOption'</span>,<br />
&nbsp; &nbsp; optionB: <span class="st0">'someOtherOption'</span><br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; <span class="kw2">var</span> meta &nbsp; &nbsp; = <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="kw3">name</span> + <span class="st0">'-opts'</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="kw1">this</span>.<span class="me1">opts</span> &nbsp; &nbsp;= $.<span class="me1">extend</span><span class="br0">&#40;</span><span class="kw1">this</span>.<span class="me1">defaults</span>, opts, meta<span class="br0">&#41;</span>;<br />
<br />
&nbsp; <span class="kw1">this</span>.$header = <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.js-header'</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="kw1">this</span>.$body &nbsp; = <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.js-body'</span><span class="br0">&#41;</span>;<br />
<span class="br0">&#125;</span></div></p>

<p>And change our invocation:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
$<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; $<span class="br0">&#40;</span><span class="st0">'.js-widget'</span><span class="br0">&#41;</span>.<span class="me1">widget</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
<span class="br0">&#125;</span><span class="br0">&#41;</span>;</div></p>

<p>I agree it's a little more markup to write and you might not need to use this. Also, since we manipulate the DOM with jQuery plugins we might depend on specific tag types anyway.
So if the designer changed all div's to be li's instead, it might still break our plugin. If you are in a situation where you have regressions due to frontend engineers and designers not communicating properly, using js- prefixed classes on all important elements might be a step in the right direction.</p>

<p>Notice how this.$header and this.$body are also agnostic to the html tag of the element that they cover.</p>

<h2>How to remove our plugin without removing the DOM element</h2>

<p>For large applications it's important to allow multiple plugins to operate on the same elements.
For this to work, you need to be able to add and remove plugins on the same element without affecting the other plugins.</p>

<p>Most jQuery plugins expect you to remove the element entirely to teardown the plugin. But what if you want to remove the plugin without removing the element?
We can do this using a destroy function:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
Widget.<span class="me1">prototype</span>.<span class="me1">destroy</span> = <span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="kw1">this</span>.$el.<span class="me1">off</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'*'</span><span class="br0">&#41;</span>.<span class="me1">off</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; <span class="kw1">this</span>.$el.<span class="me1">removeData</span><span class="br0">&#40;</span><span class="kw3">name</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="kw1">this</span>.$el = <span class="kw2">null</span>;<br />
<span class="br0">&#125;</span>;</div></p>

<p>It takes our local name variable again and removes all events in that namespace. It also removes the reference to the wrapper object from the element.
Now we can easily remove the plugin from the outside:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
$<span class="br0">&#40;</span><span class="st0">'.js-widget'</span><span class="br0">&#41;</span>.<span class="me1">data</span><span class="br0">&#40;</span><span class="st0">'js-widget'</span><span class="br0">&#41;</span>.<span class="me1">destroy</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;</div></p>

<p>By the way, if you remove the DOM element, jQuery will take care of removing all associated data and events by itself, so there is no need to worry about that case.</p>

<h2>How to write self-initializing plugins</h2>

<p>If you need to deal with a lot of Ajax requests in your app and then need to bind plugins on the DOM elements that were just loaded, this tip might be pretty useful for you.</p>

<p>What I like doing is using a PubSub implementation to automatically invoke plugins:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
$<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="kw2">var</span> $document = $<span class="br0">&#40;</span>document<span class="br0">&#41;</span>;<br />
&nbsp; $document.<span class="me1">trigger</span><span class="br0">&#40;</span><span class="st0">'dom<em>loaded'</span>, $document<span class="br0">&#41;</span>;<br />
<br />
&nbsp; $<span class="br0">&#40;</span><span class="st0">'.some</em>selector'</span><span class="br0">&#41;</span>.<span class="me1">load</span><span class="br0">&#40;</span><span class="st0">'/my/url'</span>, <span class="kw2">function</span><span class="br0">&#40;</span>nodes<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; $document.<span class="me1">trigger</span><span class="br0">&#40;</span><span class="st0">'ajax_loaded'</span>, nodes<span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
<span class="br0">&#125;</span><span class="br0">&#41;</span>;</div></p>

<p>Now we can allow the plugin to bind itself to all elements that by class definition need to be bound to it:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="kw2">var</span> <span class="kw3">name</span> = <span class="st0">'js-widget'</span>;<br />
<br />
&nbsp; <span class="co1">// wrapper object implementation, etc.</span><br />
<br />
&nbsp; $<span class="br0">&#40;</span>doc<span class="br0">&#41;</span>.<span class="me1">on</span><span class="br0">&#40;</span><span class="st0">'dom<em>loaded ajax</em>loaded'</span>, <span class="kw2">function</span><span class="br0">&#40;</span>nodes<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw2">var</span> $nodes = $<span class="br0">&#40;</span>nodes<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw2">var</span> $elements = $nodes.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; $elements = $elements.<span class="me1">add</span><span class="br0">&#40;</span>$nodes.<span class="me1">filter</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; $elements.<span class="me1">widget</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;</div></p>

<p>You can also come up with your own very custom events and even namespaces to allow your plugins to talk to each other without having to know about each other.</p>

<p>Advantages of this:</p>

<ol>
<li><p>This removes a lot of boilerplate code from our app! Re-initializing plugins after an ajax request without extra codelines? No problem!</p></li>
<li><p>We can simply remove functionality from our application by not loading a specific plugin's javascript file.</p></li>
</ol>

<p>I can see two obvious disadvantages here, though:</p>

<ol>
<li><p>We cannot provide options to the plugin invocation via this. We'd have to rely on options bound using the html5 data property "data-js-widget-opts" (read above).
In my experience this not as often needed as one would think, though.</p></li>
<li><p>If you have a very complex app with a lot of plugins and code flying around, this PubSub mechanism might not be the most performant way of doing things.
Think of 20 plugins all doing some .find() and .filter() operation on a large piece of markup that was just loaded via ajax. Ugh. :)</p></li>
</ol>

<h2>Conclusion</h2>

<p>Wrapping usable code in a jQuery plugin is not always easy, but following a few guidelines makes it a much better experience.
The ultimate takeaway here is to always wrap the plugin functionality in a wrapper class, so that the elements in your jQuery set that you bind the plugin to do not interfer with each other.</p>

<p>If your plugin is more complex, you could even use multiple wrapper classes and let their objects talk to each other. Or even cooler, try to move some of the functionality your plugin requires out into another, smaller plugin.
And let the both of them talk to each other via PubSub.</p>

<p>The rest is a couple nice extras that made my live easier.</p>

<p>Here is the full skeleton again that I use when I write new plugins (rename accordingly):</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
;<span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span>$, doc, win<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="st0">&quot;use strict&quot;</span>;<br />
<br />
&nbsp; <span class="kw2">var</span> <span class="kw3">name</span> = <span class="st0">'js-widget'</span>;<br />
<br />
&nbsp; <span class="kw2">function</span> Widget<span class="br0">&#40;</span>el, opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el &nbsp; &nbsp; &nbsp;= $<span class="br0">&#40;</span>el<span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="kw3">name</span>, <span class="kw1">this</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">defaults</span> = <span class="br0">&#123;</span><span class="br0">&#125;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw2">var</span> meta &nbsp; &nbsp; &nbsp;= <span class="kw1">this</span>.$el.<span class="me1">data</span><span class="br0">&#40;</span><span class="kw3">name</span> + <span class="st0">'-opts'</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">opts</span> &nbsp; &nbsp; = $.<span class="me1">extend</span><span class="br0">&#40;</span><span class="kw1">this</span>.<span class="me1">defaults</span>, opts, meta<span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; <span class="kw1">this</span>.<span class="me1">init</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span><br />
<br />
&nbsp; Widget.<span class="me1">prototype</span>.<span class="me1">init</span> = <span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; Widget.<span class="me1">prototype</span>.<span class="me1">destroy</span> = <span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el.<span class="me1">off</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'*'</span><span class="br0">&#41;</span>.<span class="me1">off</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el.<span class="me1">removeData</span><span class="br0">&#40;</span><span class="kw3">name</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw1">this</span>.$el = <span class="kw2">null</span>;<br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; $.<span class="me1">fn</span>.<span class="me1">widget</span> = <span class="kw2">function</span><span class="br0">&#40;</span>opts<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw1">return</span> <span class="kw1">this</span>.<span class="me1">each</span><span class="br0">&#40;</span><span class="kw2">function</span><span class="br0">&#40;</span><span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; &nbsp; <span class="kw2">new</span> Widget<span class="br0">&#40;</span><span class="kw1">this</span>, opts<span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span>;<br />
<br />
&nbsp; $<span class="br0">&#40;</span>doc<span class="br0">&#41;</span>.<span class="me1">on</span><span class="br0">&#40;</span><span class="st0">'dom_loaded ajax_loaded'</span>, <span class="kw2">function</span><span class="br0">&#40;</span>e, nodes<span class="br0">&#41;</span> <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="kw2">var</span> $nodes = $<span class="br0">&#40;</span>nodes<span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; <span class="kw2">var</span> $elements = $nodes.<span class="me1">find</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span>;<br />
&nbsp; &nbsp; $elements = $elements.<span class="me1">add</span><span class="br0">&#40;</span>$nodes.<span class="me1">filter</span><span class="br0">&#40;</span><span class="st0">'.'</span> + <span class="kw3">name</span><span class="br0">&#41;</span><span class="br0">&#41;</span>;<br />
<br />
&nbsp; &nbsp; $elements.<span class="me1">widget</span><span class="br0">&#40;</span><span class="br0">&#41;</span>;<br />
&nbsp; <span class="br0">&#125;</span><span class="br0">&#41;</span>;<br />
<span class="br0">&#125;</span><span class="br0">&#41;</span><span class="br0">&#40;</span>jQuery, document, window<span class="br0">&#41;</span>;</div></p>

<p>Kind regards,
Tim</p>

<p><a href="https://twitter.com/#!/tim_kos">@tim_kos</a>
<img style="display: none;" src="http://debuggable.com/posts/tick/4f72ab2e-7310-4a74-817a-0a04cbdd56cb"></p>
	</div>
	<div class="clear">&nbsp;</div>
	<div class="social">
	<p class="subscribe">Did you like this blog post? If so, please consider <a href="http://feeds.feedburner.com/debuggable">subscribing to the Blog RSS feed</a>.</p>

	<ul>
	<li class="sociablefirst">
				<a class="linkedin" title="LinkedIn" href="javascript:window.location='http://www.linkedin.com/shareArticle?mini=true&amp;url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fhow-to-write-jquery-plugins%3A4f72ab2e-7310-4a74-817a-0a04cbdd56cb &amp;title=How+to+write+jQuery+plugins';" rel="nofollow">
			<img class="sociable-hovers" alt="Linked In" title="Linked In" src="/img/social_icons/linkedin.png"/>
		</a>
	</li>
	<li>
		<a class="sphinn" title="Sphinn" href="javascript:window.location='http://sphinn.com/index.php?c=post&amp;m=submit&amp;link=http%3A%2F%2Fdebuggable.com%2Fposts%2Fhow-to-write-jquery-plugins%3A4f72ab2e-7310-4a74-817a-0a04cbdd56cb';" rel="nofollow">
		<img class="sociable-hovers" alt="Sphinn" title="Sphinn" src="/img/social_icons/sphinn.png"/>
		</a>
	</li>
	<li>
		<a class="digg" title="Digg" href="javascript:window.location='http://digg.com/submit?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fhow-to-write-jquery-plugins%3A4f72ab2e-7310-4a74-817a-0a04cbdd56cb&amp;title=How+to+write+jQuery+plugins&amp;bodytext=+..&amp;media=News&amp;topic=Programming';" rel="nofollow">
		<img class="sociable-hovers" alt="Digg" title="Digg" src="/img/social_icons/digg.png"/>
		</a>
	</li>
	<li>
	<a class="del.icio.us" title="del.icio.us" href="javascript:window.location='http://delicious.com/post?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fhow-to-write-jquery-plugins%3A4f72ab2e-7310-4a74-817a-0a04cbdd56cb&amp;title=How+to+write+jQuery+plugins';" rel="nofollow">
		<img class="sociable-hovers" alt="Delicious" title="Delicious" src="/img/social_icons/delicious.png"/>
	</a>
	</li>
	<li class="sociablelast">
		<a class="stumbleupon" title="StumbleUpon" href="javascript:window.location='http://www.stumbleupon.com/submit?url=http%253A%252F%252Fyoast.com%252F40-wordpress-optimisation-tips%252F&amp;title=40%2520WordPress%2520Optimisation%2520tips';" rel="nofollow">
		<img class="sociable-hovers" alt="StumbleUpon" title="StumbleUpon" src="/img/social_icons/stumbleupon.png"/>
		</a>
	</li>
	</ul>
</div>

	
	<div class="post-footer">
		<img src="/css/img/comments.png" alt="Comments"> <a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb">13 Comments</a> &nbsp; | &nbsp; 
		<img src="/css/img/add_comment.png" alt="Add Comment"> <a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#CommentAddForm">Add Comment</a>	</div>
	</div>
<div class="post">
	<h2><a href="/posts/vim-workshop-in-berlin-april-20:4f702b83-ce24-429c-9403-0e39cbdd56cb">Vim Workshop in Berlin (April 20)</a></h2>	<div class="posted-on">
		<p>Posted on 26/3/12 by 
		<a href="/felix">Felix Geisendörfer</a>				</p>
		<div class="thumb">
			<img alt="" src="/img/felix_thumb.jpg"/>		</div>
	</div>
	<div class="body">
				<p>My friend <a href="https://twitter.com/#!/nelstrom">Drew</a> of <a href="http://vimcasts.org/">Vimcast</a> fame is organizing two half-day <a href="http://vimcasts.eventbrite.com/">vim workshops</a> in Berlin on April 20.</p>

<p>As a former Textmate user, I cannot overstate the productivity gains from mastering vim. With the early bird discount, the tickets sell at 75 GBP (~90 EUR), and there are only a few tickets left, so you should act quickly.</p>

<p>The workshops are aimed at intermediate users, so if your vim skills are non-existing or very rusty, you should probably play with <a href="http://vim.wikia.com/wiki/Tutorial#Vim_tutor">vimtutor</a> before showing up.</p>

<p>I'll be attending the <a href="http://berlin-vimcasts-pm-1-eorg.eventbrite.com/">afternoon workshop</a> along with <a href="https://twitter.com/#!/tim_kos">Tim</a>, so hope to see you there!</p>

<p>--fg</p>

<p>Full Disclosure: I gain nothing by promoting this event other than the joy of seeing people boost their productivity.</p>

<p><img style="display: none;" src="http://debuggable.com/posts/tick/4f702b83-ce24-429c-9403-0e39cbdd56cb"></p>
	</div>
	<div class="clear">&nbsp;</div>
	<div class="social">
	<p class="subscribe">Did you like this blog post? If so, please consider <a href="http://feeds.feedburner.com/debuggable">subscribing to the Blog RSS feed</a>.</p>

	<ul>
	<li class="sociablefirst">
				<a class="linkedin" title="LinkedIn" href="javascript:window.location='http://www.linkedin.com/shareArticle?mini=true&amp;url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fvim-workshop-in-berlin-april-20%3A4f702b83-ce24-429c-9403-0e39cbdd56cb &amp;title=Vim+Workshop+in+Berlin+%28April+20%29';" rel="nofollow">
			<img class="sociable-hovers" alt="Linked In" title="Linked In" src="/img/social_icons/linkedin.png"/>
		</a>
	</li>
	<li>
		<a class="sphinn" title="Sphinn" href="javascript:window.location='http://sphinn.com/index.php?c=post&amp;m=submit&amp;link=http%3A%2F%2Fdebuggable.com%2Fposts%2Fvim-workshop-in-berlin-april-20%3A4f702b83-ce24-429c-9403-0e39cbdd56cb';" rel="nofollow">
		<img class="sociable-hovers" alt="Sphinn" title="Sphinn" src="/img/social_icons/sphinn.png"/>
		</a>
	</li>
	<li>
		<a class="digg" title="Digg" href="javascript:window.location='http://digg.com/submit?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fvim-workshop-in-berlin-april-20%3A4f702b83-ce24-429c-9403-0e39cbdd56cb&amp;title=Vim+Workshop+in+Berlin+%28April+20%29&amp;bodytext=+..&amp;media=News&amp;topic=Programming';" rel="nofollow">
		<img class="sociable-hovers" alt="Digg" title="Digg" src="/img/social_icons/digg.png"/>
		</a>
	</li>
	<li>
	<a class="del.icio.us" title="del.icio.us" href="javascript:window.location='http://delicious.com/post?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fvim-workshop-in-berlin-april-20%3A4f702b83-ce24-429c-9403-0e39cbdd56cb&amp;title=Vim+Workshop+in+Berlin+%28April+20%29';" rel="nofollow">
		<img class="sociable-hovers" alt="Delicious" title="Delicious" src="/img/social_icons/delicious.png"/>
	</a>
	</li>
	<li class="sociablelast">
		<a class="stumbleupon" title="StumbleUpon" href="javascript:window.location='http://www.stumbleupon.com/submit?url=http%253A%252F%252Fyoast.com%252F40-wordpress-optimisation-tips%252F&amp;title=40%2520WordPress%2520Optimisation%2520tips';" rel="nofollow">
		<img class="sociable-hovers" alt="StumbleUpon" title="StumbleUpon" src="/img/social_icons/stumbleupon.png"/>
		</a>
	</li>
	</ul>
</div>

	
	<div class="post-footer">
		<img src="/css/img/comments.png" alt="Comments"> <a href="/posts/vim-workshop-in-berlin-april-20:4f702b83-ce24-429c-9403-0e39cbdd56cb">0 Comments</a> &nbsp; | &nbsp; 
		<img src="/css/img/add_comment.png" alt="Add Comment"> <a href="/posts/vim-workshop-in-berlin-april-20:4f702b83-ce24-429c-9403-0e39cbdd56cb#CommentAddForm">Add Comment</a>	</div>
	</div>
<div class="post">
	<h2><a href="/posts/npm-an-intervention:4f44dd25-a114-4361-ada1-6cefcbdd56cb">NPM - An intervention</a></h2>	<div class="posted-on">
		<p>Posted on 22/2/12 by 
		<a href="/felix">Felix Geisendörfer</a>				</p>
		<div class="thumb">
			<img alt="" src="/img/felix_thumb.jpg"/>		</div>
	</div>
	<div class="body">
				<p><strong>Update:</strong> Isaac <a href="http://debuggable.com/posts/npm-an-intervention:4f44dd25-a114-4361-ada1-6cefcbdd56cb#comment-4f453c4b-7aac-4224-8c65-3f15cbdd56cb#comment-4f4533a2-f590-4b40-bde1-52eacbdd56cb">commented</a> and explained why fuzzy version specifiers are here to stay. I'll be ok with it and will adapt my workflow accordingly.</p>

<p><strong>Update 2:</strong> I did not give up on the bug that is part of the story below, a test case and fix has been <a href="https://github.com/nodejitsu/forever/pull/246">submitted and merged</a>!</p>

<p><strong>Update 3:</strong> NPM Shrinkwrap is now a <a href="http://blog.nodejs.org/2012/02/27/managing-node-js-dependencies-with-shrinkwrap/">real thing</a>.</p>

<p>NPM is the official node.js package manager. Unlike many package managers
that came before, it is actually incredibly awesome, and has helped to create
one of the most vibrant communities in the history of open source.</p>

<p>However, today I want to talk about a few aspects of npm that concern me. In
particular I want to talk about stuff where I feel that NPM is making bad
things easy, and good things hard.</p>

<h2>NPM module versions are broken</h2>

<p>Today, I tried to contribute to the <a href="https://github.com/nodejitsu/forever">forever</a> module. The company I am helping
had to patch their version of it because of a hard-to-reproduce bug in
production and asked me to help submitting their fix upstream. Being the
scientific type, I set out to write a test case against the forever version
their patch is based on:</p>

<pre class="terminal">
$ npm install forever@0.7.2
</pre>

<p>Fantastic, NPM lets me specify which version of forever I want to install. Now
lets verify the installed version works:</p>

<pre class="terminal">
$ ./node_modules/forever/bin/forever

node.js:134
        throw e; // process.nextTick error, or 'error' event on first tick
        ^
TypeError: undefined is not a function
    at CALL_NON_FUNCTION_AS_CONSTRUCTOR (native)
    at Object.<anonymous> (/Users/Felix/Desktop/foo/node_modules/forever/lib/forever.js:43:23)
    ...
</pre>

<p>Oh no, what happened? Mind you, except for an unrelated patch, this version of
forever is running perfectly fine in production.</p>

<p>Well, as it turns out, you have been lied to. There is no such thing as forever
v0.7.2. At least not a single one. It depends on an implicit and unchangable
second parameter: time.</p>

<p>Why is that? Well, it is because forever v0.7.2 depends on this:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
<span class="st0">&quot;nconf&quot;</span>: <span class="st0">&quot;0.x.x&quot;</span>,</div></p>

<p>And as it turns out, nconf has released newer versions matching this selector,
featuring a different API.</p>

<h2>You are doing it wrong</h2>

<p>"Hah!", you might say. "That's why you should
<a href="http://www.mikealrogers.com/posts/nodemodules-in-git.html">check your node&#95;modules into git</a>!".</p>

<p>I am sorry, but that is not helpful. While this will allow me to pin down
the node modules used by my app exactly, it does not help me here. What I want to
do is to reproduce this bug in a standalone copy of forever v0.7.2, then
check if it exists in the latest version, and if so submit the test case and
fix for it upstream.</p>

<p>However, I can't. Not without manually resolving all forever dependencies the
way NPM resolved them when v0.7.2 was released. (The fact that forever is a bit
of a <a href="https://github.com/nodejitsu/forever/blob/382f8e7f2a1da99838615d8e462be6b964975de4/package.json#L24-40">spaceship</a> when it comes to dependencies does not help either).</p>

<h2>Discouraging Open Source</h2>

<p>Speaking about Mikeal's article. I felt that something was wrong about checking
your node&#95;modules into git when reading it, but it is only now that I can
point out what:</p>

<p>In the article, Mikeal argues that module authors should not try to exactly
reference their dependency versions, so this way users would get more frequent
updates of those dependencies and help test them.</p>

<p>However, he says doing so for your app is a good thing.</p>

<p>I disagree. To me, this approach discourages open source for two reasons:</p>

<h3>a) Bug reports:</h3>

<p>I currently maintain 44 NPM modules. It is very hard to keep
up with that.</p>

<p>If you are asking me to support multiple versions of all my dependencies, I
will have to stop helping people with bug reports for my modules.</p>

<p>When somebody reports a bug for a given version of my module, I want to know
<strong>exactly</strong> what version he used. Figuring out when he installed my module to
rule out dependency issues for every bug report is not an option for me.</p>

<h3>b) Contributions</h3>

<p>Ask yourself what is easier. Adding a quick patch to a node module you already
track include in the git repo of your app, --or-- creating a fork of it, fixing the problem in the
fork, pushing that fork on GitHub, changing your package.json to point to your
fork, and submitting a pull request.</p>

<p>I know people cannot be forced to contribute back, nor should they be. But
as things stand right now, checking in all node_modules of an app into git is
the <strong>only</strong> sane option, as the version numbers in your package.json are
essentially meaningless.</p>

<p>This means that contributing back to open source is made difficult by default,
while keeping your patches to yourself is made easy. I would like this to be
the other way arround.</p>

<h2>Conclusion</h2>

<p>I propose to gradually drop all support for fuzzy version specifiers from NPM.</p>

<p>To me, fuzzy version specifiers are entirely evil. They make things more
complex. They force me to manually snapshot the packages I depend on for my
apps. They prevent me from supporting and contributing to open source.</p>

<p>So rather than throwing more complexity at this problem, lets just remove
this feature alltogether.</p>

<p>If you agree, please <a href="https://twitter.com/felixge/status/172366107469029376">re-tweet this article</a> or leave a comment.</p>

<p>--fg</p>

<p><img style="display: none;" src="http://debuggable.com/posts/tick/4f44dd25-a114-4361-ada1-6cefcbdd56cb"></p>
	</div>
	<div class="clear">&nbsp;</div>
	<div class="social">
	<p class="subscribe">Did you like this blog post? If so, please consider <a href="http://feeds.feedburner.com/debuggable">subscribing to the Blog RSS feed</a>.</p>

	<ul>
	<li class="sociablefirst">
				<a class="linkedin" title="LinkedIn" href="javascript:window.location='http://www.linkedin.com/shareArticle?mini=true&amp;url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fnpm-an-intervention%3A4f44dd25-a114-4361-ada1-6cefcbdd56cb &amp;title=NPM+-+An+intervention';" rel="nofollow">
			<img class="sociable-hovers" alt="Linked In" title="Linked In" src="/img/social_icons/linkedin.png"/>
		</a>
	</li>
	<li>
		<a class="sphinn" title="Sphinn" href="javascript:window.location='http://sphinn.com/index.php?c=post&amp;m=submit&amp;link=http%3A%2F%2Fdebuggable.com%2Fposts%2Fnpm-an-intervention%3A4f44dd25-a114-4361-ada1-6cefcbdd56cb';" rel="nofollow">
		<img class="sociable-hovers" alt="Sphinn" title="Sphinn" src="/img/social_icons/sphinn.png"/>
		</a>
	</li>
	<li>
		<a class="digg" title="Digg" href="javascript:window.location='http://digg.com/submit?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fnpm-an-intervention%3A4f44dd25-a114-4361-ada1-6cefcbdd56cb&amp;title=NPM+-+An+intervention&amp;bodytext=+..&amp;media=News&amp;topic=Programming';" rel="nofollow">
		<img class="sociable-hovers" alt="Digg" title="Digg" src="/img/social_icons/digg.png"/>
		</a>
	</li>
	<li>
	<a class="del.icio.us" title="del.icio.us" href="javascript:window.location='http://delicious.com/post?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Fnpm-an-intervention%3A4f44dd25-a114-4361-ada1-6cefcbdd56cb&amp;title=NPM+-+An+intervention';" rel="nofollow">
		<img class="sociable-hovers" alt="Delicious" title="Delicious" src="/img/social_icons/delicious.png"/>
	</a>
	</li>
	<li class="sociablelast">
		<a class="stumbleupon" title="StumbleUpon" href="javascript:window.location='http://www.stumbleupon.com/submit?url=http%253A%252F%252Fyoast.com%252F40-wordpress-optimisation-tips%252F&amp;title=40%2520WordPress%2520Optimisation%2520tips';" rel="nofollow">
		<img class="sociable-hovers" alt="StumbleUpon" title="StumbleUpon" src="/img/social_icons/stumbleupon.png"/>
		</a>
	</li>
	</ul>
</div>

	
	<div class="post-footer">
		<img src="/css/img/comments.png" alt="Comments"> <a href="/posts/npm-an-intervention:4f44dd25-a114-4361-ada1-6cefcbdd56cb">28 Comments</a> &nbsp; | &nbsp; 
		<img src="/css/img/add_comment.png" alt="Add Comment"> <a href="/posts/npm-an-intervention:4f44dd25-a114-4361-ada1-6cefcbdd56cb#CommentAddForm">Add Comment</a>	</div>
	</div>
<div class="post">
	<h2><a href="/posts/testing-node-js-modules-with-travis-ci:4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb">Testing node.js modules with Travis CI</a></h2>	<div class="posted-on">
		<p>Posted on 18/11/11 by 
		<a href="/felix">Felix Geisendörfer</a>				</p>
		<div class="thumb">
			<img alt="" src="/img/felix_thumb.jpg"/>		</div>
	</div>
	<div class="body">
				<p>You have written a node.js module lately? It has a test suite? <a href="http://www.youtube.com/watch?v=2Z4m4lnjxkY">Awesome</a>! Time
to get yourself a nerd badge of honor:</p>

<p><img src="http://debuggable.com.s3.amazonaws.com/blog/2011/build-passing.png" alt="build passing" /></p>

<p>But hang on nerdy warrior, this precious award has to be earned. So go ahead and
check out the sweetness that is <a href="http://travis-ci.org">Travis CI</a>. Travis is an open
source, free to use, continuous integration server. Initially it was just
building ruby stuff, but these days it supports a ton of other languages,
including node.js.</p>

<p>And luckily, getting travis to run your tests on every GitHub push is really
easy as well:</p>

<p><strong>Step 1:</strong> Go to <a href="http://travis-ci.org">Travis</a> and login/connect with your GitHub account.</p>

<p><strong>Step 2:</strong> Hover over your name on the top right, and select "Profile" from the
dropdown.</p>

<p><strong>Step 3:</strong> You should see all your GitHub projects. Flip the "Off" switch to
"On" for a node.js project you want to use with travis.</p>

<p><strong>Step 4:</strong> Add a .travis.yml file to your project with the following:</p>

<pre class="terminal">
language: node_js
node_js:
  - 0.4
  - 0.6
</pre>

<p><strong>Step 5:</strong> Make sure your package.json has something like this:</p>

<p><div class="clear"></div><div class="code debuggable_sh_js" style="white-space: wrap;white-space: nowrap;">
<span class="st0">&quot;scripts&quot;</span>: <span class="br0">&#123;</span><br />
&nbsp; &nbsp; <span class="st0">&quot;test&quot;</span>: <span class="st0">&quot;make test&quot;</span><br />
&nbsp; <span class="br0">&#125;</span>,</div></p>

<p><strong>Step 6:</strong> Git push, and watch travis building your project on the home screen!</p>

<p><strong>Step 7:</strong> Assuming your tests are passing, it is time to get your badge of
honor. Adding it to your GitHub Readme.md is as simple as:</p>

<pre class="terminal">
[![Build Status](https://secure.travis-ci.org/&lt;GITHUB_USER&gt;/&lt;REPO_NAME&gt;.png)](http://travis-ci.org/&lt;GITHUB_USER&gt;/&lt;REPO_NAME&gt;)
</pre>

<p>If you want to see an example of what this looks like, and you also happen to
be in the market for some no-bullshit testing tools, check out my new libs:</p>

<ul>
<li><a href="https://github.com/felixge/node-utest">utest</a>: The minimal unit testing library.</li>
<li><a href="https://github.com/felixge/node-urun">urun</a>: The minimal test runner.</li>
</ul>

<p>That's it. And in case you are not excited enough yet, go and check out the
<a href="http://about.travis-ci.org/docs/">Travis Docs</a> to discover additional goodies like how to work with
databases, etc.</p>

<p>--fg</p>

<p><img style="display: none;" src="http://debuggable.com/posts/tick/4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb"></p>
	</div>
	<div class="clear">&nbsp;</div>
	<div class="social">
	<p class="subscribe">Did you like this blog post? If so, please consider <a href="http://feeds.feedburner.com/debuggable">subscribing to the Blog RSS feed</a>.</p>

	<ul>
	<li class="sociablefirst">
				<a class="linkedin" title="LinkedIn" href="javascript:window.location='http://www.linkedin.com/shareArticle?mini=true&amp;url=http%3A%2F%2Fdebuggable.com%2Fposts%2Ftesting-node-js-modules-with-travis-ci%3A4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb &amp;title=Testing+node.js+modules+with+Travis+CI';" rel="nofollow">
			<img class="sociable-hovers" alt="Linked In" title="Linked In" src="/img/social_icons/linkedin.png"/>
		</a>
	</li>
	<li>
		<a class="sphinn" title="Sphinn" href="javascript:window.location='http://sphinn.com/index.php?c=post&amp;m=submit&amp;link=http%3A%2F%2Fdebuggable.com%2Fposts%2Ftesting-node-js-modules-with-travis-ci%3A4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb';" rel="nofollow">
		<img class="sociable-hovers" alt="Sphinn" title="Sphinn" src="/img/social_icons/sphinn.png"/>
		</a>
	</li>
	<li>
		<a class="digg" title="Digg" href="javascript:window.location='http://digg.com/submit?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Ftesting-node-js-modules-with-travis-ci%3A4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb&amp;title=Testing+node.js+modules+with+Travis+CI&amp;bodytext=+..&amp;media=News&amp;topic=Programming';" rel="nofollow">
		<img class="sociable-hovers" alt="Digg" title="Digg" src="/img/social_icons/digg.png"/>
		</a>
	</li>
	<li>
	<a class="del.icio.us" title="del.icio.us" href="javascript:window.location='http://delicious.com/post?url=http%3A%2F%2Fdebuggable.com%2Fposts%2Ftesting-node-js-modules-with-travis-ci%3A4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb&amp;title=Testing+node.js+modules+with+Travis+CI';" rel="nofollow">
		<img class="sociable-hovers" alt="Delicious" title="Delicious" src="/img/social_icons/delicious.png"/>
	</a>
	</li>
	<li class="sociablelast">
		<a class="stumbleupon" title="StumbleUpon" href="javascript:window.location='http://www.stumbleupon.com/submit?url=http%253A%252F%252Fyoast.com%252F40-wordpress-optimisation-tips%252F&amp;title=40%2520WordPress%2520Optimisation%2520tips';" rel="nofollow">
		<img class="sociable-hovers" alt="StumbleUpon" title="StumbleUpon" src="/img/social_icons/stumbleupon.png"/>
		</a>
	</li>
	</ul>
</div>

	
	<div class="post-footer">
		<img src="/css/img/comments.png" alt="Comments"> <a href="/posts/testing-node-js-modules-with-travis-ci:4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb">8 Comments</a> &nbsp; | &nbsp; 
		<img src="/css/img/add_comment.png" alt="Add Comment"> <a href="/posts/testing-node-js-modules-with-travis-ci:4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb#CommentAddForm">Add Comment</a>	</div>
	</div>
<div class="paging">
	<div class="disabled">&laquo; Previous</div> <span class="current">1</span> | <span><a href="/posts/index/page:2">2</a></span> | <span><a href="/posts/index/page:3">3</a></span> | <span><a href="/posts/index/page:4">4</a></span> | <span><a href="/posts/index/page:5">5</a></span> | <span><a href="/posts/index/page:6">6</a></span> | <span><a href="/posts/index/page:7">7</a></span> | <span><a href="/posts/index/page:8">8</a></span> | <span><a href="/posts/index/page:9">9</a></span> <a href="/posts/index/page:2" class="next">Next &raquo;</a></div>	
</div>
<div class="grid_4 prefix_1 omega" id="sidebar">
	<cake:nocache>
			</cake:nocache>

	<h3>RSS Feeds</h3>
	<div id="bug">
		<img src="/img/rss_bug.png" alt="" />	</div>
	<div class="rss">
		<p class="bug-message"></p>
		<a href="http://feeds.feedburner.com/debuggable">Blog RSS</a><br/>
		<a href="http://feeds.feedburner.com/debuggable-comments">Comments RSS</a><br/><br/>
		<img width="88" height="26" alt="" style="border: 0pt none ;" src="http://feeds.feedburner.com/~fc/debuggable?bg=FF9933&amp;fg=444444&amp;anim=0"/>
		<div class="clear"></div>
	</div>

	<h3>Recent Posts</h3>
	<ul>
<li class=""><a href="/posts/releasing-node-mysql-2-0-0-alpha:4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb">Releasing node-mysql 2.0.0-alpha</a></li><li class=""><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb">How to write jQuery plugins</a></li><li class=""><a href="/posts/vim-workshop-in-berlin-april-20:4f702b83-ce24-429c-9403-0e39cbdd56cb">Vim Workshop in Berlin (April 20)</a></li><li class=""><a href="/posts/npm-an-intervention:4f44dd25-a114-4361-ada1-6cefcbdd56cb">NPM - An intervention</a></li><li class="active"><a href="/posts/testing-node-js-modules-with-travis-ci:4ec62298-aec4-4ee3-8b5a-2c96cbdd56cb">Testing node.js modules with Travis CI</a></li><li class=""><a href="/posts/private-npm-modules:4e68cc7d-1ac4-42d9-995a-343dcbdd56cb">Private npm modules</a></li></ul>
	<h3>Archive</h3>
	<p class="small align">
		<strong>443 Posts</strong>, <strong>4608 Comments</strong><br /><br />
		We are on air since 2006. Take a tour through the
		<a href="/posts/archive">blog archive</a>.
	</p>
	<div class="search">
	<form id="PostSearchForm" method="post" action="/posts/search"><fieldset style="display:none;"><input type="hidden" name="_method" value="POST" /></fieldset><input name="data[Post][keywords]" type="text" value="" id="PostKeywords" /><input type="submit" class="button" value="Search" /></form>	<div class="clear"></div>
</div>
	<h3>Recent Comments</h3>
	<div class="recent-comments">
		<div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=23968f0ca75b13463d2db5343e5c2096&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/releasing-node-mysql-2-0-0-alpha:4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb#comment-4fd32b85-220c-4fc8-84b2-378fcbdd56cb">William: thanks, fixed ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=b47010beec892f11619d1e81f0c94f11&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/releasing-node-mysql-2-0-0-alpha:4fb21c18-7f84-4e8c-a1ef-599bcbdd56cb#comment-4fd30119-06fc-4712-aecd-7fa5cbdd56cb">Hi Felix,

The Upgra ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=99b59e8a9cfe2c5575f0fa90f7f30307&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f99a4a2-9ad8-4476-b208-611acbdd56cb">Maybe you can write so ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=8364689a1eefb5eceb6a4f38bbf95731&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f9651b9-eb88-4096-94c1-0fc2cbdd56cb">This is very nice plug ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=7e3d69d16d3b845e89198512355b2ac9&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f8bb75a-96cc-4197-8e93-7c63cbdd56cb">Nice article!

Somet ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=e57a2bc121063a81e8e6a04aa85cc54f&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f83326b-8c28-43fc-b70d-097ecbdd56cb">That&#039;s fine ognian, th ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=994516a664c2bdc728d18c47e935bc14&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f832a25-5818-4d38-9e39-097ecbdd56cb">Really nice work! I wa ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=e57a2bc121063a81e8e6a04aa85cc54f&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f7c15ca-c7c4-48e3-a4db-27decbdd56cb">@Jörn: Sorry, thought  ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=d5d83832be2b6c70d1968635f68a1b4a&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f7c11aa-6f9c-448c-abdb-2066cbdd56cb">Thanks didn&#039;t quite un ..</a></div><div class="clear_left"></div><div class="comment"><a href="http://en.gravatar.com/site/signup" class="gravatar"><img src="http://www.gravatar.com/avatar.php?gravatar_id=e57a2bc121063a81e8e6a04aa85cc54f&size=15&rating=R&d=identicon" alt="" /></a><a href="/posts/how-to-write-jquery-plugins:4f72ab2e-7310-4a74-817a-0a04cbdd56cb#comment-4f7bf934-d4e8-4885-9a2c-7a93cbdd56cb">Well you could expose  ..</a></div><div class="clear_left"></div>	</div>
	<div class="clear_left"></div>
	<h3>Keep an eye on</h3>
<ul class="links external">
	<li><a href="http://transloadit.com" title="Video encoding, image resizing and more for your web or mobile app">Transloadit</a></li><li><a href="http://tus.io" title="Resumable file uploading, upload progress bar, faster upload speed">tus - resumable file upload protocol</a></li><li><a href="http://kevin.vanzonneveld.net/">Kevin van Zonneveld</a></li><li><a href="http://www.littlehart.net/atthekeyboard/">Chris Hartjes</a></li><li><a href="http://mark-story.com">Mark Story</a></li><li><a href="http://www.webbosaurus.de">Webbosaurus</a></li></ul>
	<a href='https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number' title='JavaScript JS Documentation: JS Number Example: Using the Number object to assign values to numeric variables, JavaScript Number Example: Using the Number object to assign values to numeric variables'><img src='http://static.jsconf.us/promotejshs.png' height='150' width='180' alt='JavaScript JS Documentation: JS Number Example: Using the Number object to assign values to numeric variables, JavaScript Number Example: Using the Number object to assign values to numeric variables'/></a>
</div>

						<div class="clear">&nbsp;</div>
		</div>

		<div id="footer">
			<div class="container_16">
				<ul id="footer_navigation">
					<ul>
<li class="active"><a href="/blog">Blog</a></li><li class=""><a href="/">About</a></li></ul>				</ul>
				<p>&copy; 2008 - 2015, Debuggable Ltd. All rights reserved.
				<i>Designed by <a href="http://www.fluidcore.net" target="_blank">fluidCORE</a>.</i>
			</div>
		</div>
	</div>
	<script type="text/javascript" src="/js/aggregate/58a4727fb2207154ddd0739cbc3b15104ad6cd03/5627ea2806458e56fb8a5f4b231a44c2.php"></script><script type="text/javascript">
var _gaq = _gaq || [];
_gaq.push(['_setAccount', 'UA-3306079-3']);
_gaq.push(['_trackPageview']);
(function() {
var ga = document.createElement('script');
ga.src = ('https:' == document.location.protocol ?
    'https://ssl' : 'http://www') +
    '.google-analytics.com/ga.js';
ga.setAttribute('async', 'true');
document.documentElement.firstChild.appendChild(ga);
})();
</script></body>
</html>
