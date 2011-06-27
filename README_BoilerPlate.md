#  HTML5 Boilerplate [http://html5boilerplate.com](http://html5boilerplate.com)

## Summary:

This is a set of files that a front-end developer can use to get started on a website, with following included:

1. Cross-browser compatible (IE6, yeah we got that.)
2. HTML5 ready. Use the new tags with certainty.
3. Optimal caching and compression rules for grade-A performance
4. Best practice site configuration defaults
5. Think there's too much? The HTML5 Boilerplate is delete-key friendly. :)
6. Mobile browser optimizations
7. Progressive enhancement graceful degredation ........ yeah yeah we got that
8. IE specific classes for maximum cross-browser control
9. Want to write unit tests but lazy? A full, hooked up test suite is waiting for you.
10. Javascript profiling.. in IE6 and IE7? Sure, no problem.
11. Console.log nerfing so you won't break anyone by mistake.
12. Never go wrong with your doctype or markup!
13. An optimal print stylesheet, performance optimized
14. iOS, Android, Opera Mobile-adaptable markup and CSS skeleton.
15. IE6 pngfix baked in.
16. jQuery, waiting for you

#### Build Script
<ul>
	<li>Files linked via @import will be inlined into the files they are imported to using Corey Hart's CSS Compressor.</li>
	<li>Environments are definable.</li>
	<li>htaccess Expires headers are upgraded to 1year, as the filenames are revved</li>
	<li>Massive rewrite so you can define which HTML, CSS, JS files to operate on in your configurable project.properties files. This allows you to let the build script operate on very unique folder architecture, including non-H5BP projects.</li>
	<li>Added a source directory option in the build config, so your source files can be in a different directory from the final generated files (useful for other CMSes/frameworks like Django). </li>		
</ul>

#### style.css
<ul>
	<li>Added <code>.focusable</code> helper class that extends <code>.visuallyhidden</code> to allow the element to be focusable when navigated to via the keyboard.</li>
	<li>Anchor links are no longer reset. Basically our reset is the effectively merged with Eric Meyer's recent CSS reset update and also the HTML5 Doctor reset.</li>
	<li>An unordered list within a nav element will no longer have a margin.</li>
	<li>All helper classes are now after primary styles to ensure correct overrides and not be burdened with resets. </li>
	<li><code>.visuallyhidden</code> is no longer camelCase, as to be consistent with other classname formats.</li>
	<li>Updated the specificity of <code>.visuallyhidden</code> rule to make sure it overrides all other declarations. </li>
	<li>Removed reset on image elements within table cells as they look ugly alongside multiline texts. Browsers default to baseline alignment for images which works better than top alignment.</li>
	<li>Increased margin-left on ol, to allow for 2-digit list numbers.</li>
	<li>Added a print reset on IE's proprietary filters.</li>
	<li>Print styles no longer prints hash links or javascript links.</li>
	<li>Updated sub/sup css to make them not be impacted by line-height, so now you can do sub/superscripts without worrying.</li>		
</ul>


#### Webserver Configs
#### .htaccess
<ul>
	<li>.htaccess is far more documented now. Take a read through it!</li>
	<li><a href="https://github.com/paulirish/html5-boilerplate/commit/37b5fec090d00f38de64b591bcddcb205aadf8ee">Changed mimetype of .ico files to "image/x-icon"</a>.</li>
	<li>HTML Manifest files now use <code>.appcache</code> extension instead of <code>.manifest</code>, as per <a href="http://html5.org/r/5812">http://html5.org/r/5812</a>.</li>
	<li>Force deflate for accept-encoding headers mangled by turtle tappers, courtesy of <a href="http://developer.yahoo.com/blogs/ydn/posts/2010/12/pushing-beyond-gzipping/">Yahoo!'s research</a></li>
	<li>We nerfed some of the directives in case you're on server without <code>mod_headers</code>. (Which is totally crazy, man)</li>
	<li>Block access to .git and .svn folders.</li>
	<li>Eradicating Chrome's console warning on WOFF font downloads.</li>
	<li>More optimizations available if you set the .htaccess details up in your httpd.conf</li>
	<li>.htaccess now caches .htc files</li>
  
	<li>Moved all server configurations (except apache's .htaccess) over to <a href ="https://github.com/paulirish/html5-boilerplate-server-configs">the new html5-boilerplate-server-configs repo</a>. Head over there if you are not using Apache. </li>
	
	<li>Updated <code>.htaccess</code> and <code>mime.types</code> for ogg formats.</li>
	<li>Fixed regression where EOT fonts had been excluded from DEFLATE compression</li>
	<li>Apache version independence: Use <code>mod_filter</code> for compression, with fallback to AddOutputFilterByType directive for legacy versions</li>
	<li>Added plugin/extension mime types for Safari, Chrome, Firefox</li>
</ul>
#### nginx
<ul>
	<li>Cleaned up cache expires directives.</li>
	<li>Now includes SVG and font formats for gzipping.</li>
	<li>expires header bug fixed.</li>
</ul>

<ul>
	<li>Also Google App Engine, Lighttpd, and NodeJS <a href="https://github.com/paulirish/html5-boilerplate-server-configs">configurations were added</a></li>
</ul>




  