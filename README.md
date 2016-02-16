# 6g firewall

https://perishablepress.com/6g/


		<article id="post-15649" class="post-15649 post type-post status-publish format-standard hentry category-htaccess category-security tag-apache tag-blacklist tag-firewall tag-mod_rewrite">

	<div class="post-content">

		<header>
			<h1>
				<a class="b" href="https://perishablepress.com/6g/" title="Posted: January 27th, 2016 | 11 Comments">6G Firewall 2016</a>
							</h1>

					</header>

		<div class="entry-content">
			<p><img class="l static-image" src="https://perishablepress.com/wp/wp-content/images/2016/6G-firewall.png" alt="[ 6G Firewall ]"> After three years of <a href="https://perishablepress.com/6g-beta/" title="6G Beta">development, testing, and feedback</a>, I&#8217;m pleased to announce the official launch version of the <a href="https://perishablepress.com/6g/" title="6G Firewall">6G Firewall</a> (aka the <abbr title="6th Generation">6G</abbr> Blacklist). This version of the <abbr title="1st, 2nd, 3rd, 4th, 5th, 6th, etc. Generation">nG</abbr> Firewall is greatly refined, heavily tested, and better than ever. Fine-tuned to minimize false positives, the 6G Firewall protects your site against a wide variety of malicious <abbr title="Uniform Resource Indicator">URI</abbr> requests, bad bots, spam referrers, and other attacks. Blocking bad traffic improves site <a href="https://perishablepress.com/category/security/" title="Read posts about Web Security">security</a>, reduces server load, and conserves precious resources. The 6G Firewall is entirely plug-n-play with no configuration required. It&#8217;s also open source, easy to use, and completely <em>free</em>, providing strong protection for any Apache-powered website.</p>
<p><span id="more-15649"></span></p>
<h3 id="table-of-contents">Contents</h3>
<p>Shortcut menu for this post:</p>
<ul>
<li><a class="anchor" href="#about-6g">About 6G</a></li>
<li><a class="anchor" href="#description">Description</a></li>
<li><a class="anchor" href="#requirements">Requirements</a></li>
<li><a class="anchor" href="#6g-firewall">6G Firewall</a></li>
<li><a class="anchor" href="#notes">Notes</a></li>
<li><a class="anchor" href="#changelog">Changelog</a></li>
<li><a class="anchor" href="#faqs">FAQs</a></li>
<li><a class="anchor" href="#troubleshooting">Troubleshooting</a></li>
<li><a class="anchor" href="#reporting-bugs">Reporting Bugs</a></li>
<li><a class="anchor" href="#show-support">Show Support</a></li>
<li><a class="anchor" href="#license">License</a></li>
<li><a class="anchor" href="#disclaimer">Disclaimer</a></li>
<li><a class="anchor" href="#learn-more">Learn More</a></li>
<li><a class="anchor" href="#7g-firewall">Coming Soon</a></li>
<li><a class="anchor" href="#thank-you">Thank You</a></li>
</ul>
<h3 id="about-6g">About 6G</h3>
<p>Over the past few years, malicious server scans and bad requests have increased dramatically. If you have yet to implement strong security measures for your site, <em>now</em> is the time to <strong>beef up security</strong> and <strong>lock things down</strong>. There are many great security solutions available for your site, but none provide the simplicity, flexibility, and performance of 6G. </p>
<p>The 6G Firewall is a powerful, well-optimized blacklist that checks all URI requests against a set of carefully constructed <a href="https://perishablepress.com/category/htaccess/" title="Read posts about .htaccess">.htaccess</a> directives. This happens quietly behind the scenes at the server level, which is optimal for performance and resource conservation. Most WordPress plugins require both <abbr title="PHP: Hypertext Preprocessor">PHP</abbr> and <abbr title="My Structured Query Language">MySQL</abbr>, which can be overkill and even wasteful depending on the scenario and your overall security strategy. Implementing an .htaccess solution such as the 6G Firewall, the code is executed without invoking the memory and resources required for PHP, MySQL, etc. That gives you better performance while saving server resources for legitimate traffic.</p>
<p>The 6G Firewall integrates the best features of the following resources:</p>
<ul>
<li><a href="https://perishablepress.com/6g-beta/">6G Beta</a></li>
<li><a href="https://perishablepress.com/5g-blacklist-2013/">5G Firewall</a></li>
<li><a href="https://perishablepress.com/2014-micro-blacklist/">2014 Micro Blacklist</a></li>
<li><a href="https://perishablepress.com/latest-blacklist-entries/">2010 Blacklist Update</a></li>
<li><a href="https://perishablepress.com/wordpress-5g-blacklist/">5G for WordPress</a></li>
<li>Plus all-new rules and patterns</li>
</ul>
<p><strong>Bottom line:</strong> 6G is an easy-to-use, cost-effective way to secure your site against malicious <abbr title="Hypertext Transfer Protocol">HTTP</abbr> activity. It helps to protect against evil exploits, ill requests, and other nefarious garbage, such as <abbr title="Cross Site Scripting">XSS</abbr> attacks, <abbr title="Structured Query Language">SQL</abbr>/<abbr title="PHP: Hypertext Preprocessor">PHP</abbr> injections, cache poisoning, response splitting, dual-header exploits, and more.</p>
<h3 id="description">How it works</h3>
<p>Like other <a href="https://perishablepress.com/tag/blacklist/" title="Learn more about blocking bad bots and securing your site with firewalls and blacklists">Apache firewalls and blacklists</a>, the 6G operates at the server-level. Basically you add the 6G code to your site&#8217;s root .htaccess file and then sit back and relax while 6G works its magic. That&#8217;s the beauty of it: there is no configuration required. Just add the code and done. </p>
<p>Once implemented, 6G scans every HTTP request made to your site. It compares key aspects of each request against a carefully formulated set of patterns and expressions. So if someone or something triggers a match, they immediately are blocked, silently behind the scenes (via 403 Forbidden response). So legitimate visitors can continue to surf your site with total confidence, while the bad guys are busy getting kicked to the curb by 6G. </p>
<p><a href="https://perishablepress.com/6g-beta/" title="6G Firewall (beta)">Learn more about 6G and how it works &raquo;</a></p>
<h3 id="requirements">Requirements</h3>
<p>Before installing 6G, please make sure that your setup meets the requirements:</p>
<ul>
<li>Apache version 2 or better</li>
<li>.htaccess files enabled on your server</li>
</ul>
<p>If you are unsure about either of these requirements, ask your web host. If you are new to Apache and/or .htaccess, and want to learn more about it, I wrote an entire <a href="https://htaccessbook.com/" title=".htaccess made easy">book on using .htaccess to secure and optimize your site</a>. Also, here is a tutorial that explains <a href="https://wp-mix.com/create-htaccess-files-osx-windows/" title="Create .htaccess files on OS X and Windows">how to create an .htaccess file on your local machine</a>.</p>
<p><strong>Important!</strong></p>
<p>Always make a backup copy of your .htaccess before making any changes. That way if something goes awry, you can restore original functionality immediately. I realize that this may be obvious to some, but it&#8217;s important for everyone to know.</p>
<p><strong>Reporting bugs</strong></p>
<p>If you encounter any issue with 6G, please refer to the <a class="anchor" href="#troubleshooting" title="Scroll to Troubleshooting">Troubleshooting</a> and <a class="anchor" href="#reporting-bugs" title="Scroll to Reporting Bugs">Reporting Bugs</a> sections below for important information.</p>
<p><strong>WordPress alternative for 6G</strong></p>
<p>If your site does not meet the requirements, I develop the following <a href="https://plugin-planet.com/" title="Plugin Planet: Premium WordPress Plugins">WordPress plugins</a>:</p>
<ul>
<li><a href="https://wordpress.org/plugins/block-bad-queries/" title="BBQ (free version) hosted at WordPress.org">BBQ: Block Bad Queries</a> (free plugin)</li>
<li><a href="https://plugin-planet.com/bbq-pro/" title="BBQ Pro (premium version) hosted at Plugin Planet">BBQ Pro</a> (premium plugin with advanced security and features)</li>
</ul>
<p>Both of these plugins are blazing fast and integrate 5G/6G technology, providing strong firewall protection for your WordPress-powered site.</p>
<h3 id="6g-firewall">6G Firewall</h3>
<p>The 6G Firewall/Blacklist consists of the following sections:</p>
<ul>
<li><code># 6G:[QUERY STRING]</code></li>
<li><code># 6G:[REQUEST METHOD]</code></li>
<li><code># 6G:[REFERRER]</code></li>
<li><code># 6G:[REQUEST STRING]</code></li>
<li><code># 6G:[USER AGENT]</code></li>
<li><code># 6G:[IP ADDRESS]</code></li>
</ul>
<p>Each of these sections works independently of the others, such that you could, say, omit the entire query-string and IP-address blocks and the remaining sections would continue to work just fine. Mix &rsquo;n match &rsquo;em to suit your needs. This code is formatted for deployment in your site&#8217;s <em>root</em> <code>.htaccess</code> file. Remember: always make a backup of your .htaccess before making any changes.</p>
<pre><code># 6G FIREWALL/BLACKLIST
# @ https://perishablepress.com/6g/

# 6G:[QUERY STRINGS]
&lt;IfModule mod_rewrite.c&gt;
	RewriteEngine On
	RewriteCond %{QUERY_STRING} (eval\() [NC,OR]
	RewriteCond %{QUERY_STRING} (127\.0\.0\.1) [NC,OR]
	RewriteCond %{QUERY_STRING} ([a-z0-9]{2000}) [NC,OR]
	RewriteCond %{QUERY_STRING} (javascript:)(.*)(;) [NC,OR]
	RewriteCond %{QUERY_STRING} (base64_encode)(.*)(\() [NC,OR]
	RewriteCond %{QUERY_STRING} (GLOBALS|REQUEST)(=|\[|%) [NC,OR]
	RewriteCond %{QUERY_STRING} (&lt;|%3C)(.*)script(.*)(&gt;|%3) [NC,OR]
	RewriteCond %{QUERY_STRING} (\\|\.\.\.|\.\./|~|`|&lt;|&gt;|\|) [NC,OR]
	RewriteCond %{QUERY_STRING} (boot\.ini|etc/passwd|self/environ) [NC,OR]
	RewriteCond %{QUERY_STRING} (thumbs?(_editor|open)?|tim(thumb)?)\.php [NC,OR]
	RewriteCond %{QUERY_STRING} (\'|\")(.*)(drop|insert|md5|select|union) [NC]
	RewriteRule .* - [F]
&lt;/IfModule&gt;

# 6G:[REQUEST METHOD]
&lt;IfModule mod_rewrite.c&gt;
	RewriteCond %{REQUEST_METHOD} ^(connect|debug|delete|move|put|trace|track) [NC]
	RewriteRule .* - [F]
&lt;/IfModule&gt;

# 6G:[REFERRERS]
&lt;IfModule mod_rewrite.c&gt;
	RewriteCond %{HTTP_REFERER} ([a-z0-9]{2000}) [NC,OR]
	RewriteCond %{HTTP_REFERER} (semalt.com|todaperfeita) [NC]
	RewriteRule .* - [F]
&lt;/IfModule&gt;

# 6G:[REQUEST STRINGS]
&lt;IfModule mod_alias.c&gt;
	RedirectMatch 403 (?i)([a-z0-9]{2000})
	RedirectMatch 403 (?i)(https?|ftp|php):/
	RedirectMatch 403 (?i)(base64_encode)(.*)(\()
	RedirectMatch 403 (?i)(=\\\'|=\\%27|/\\\'/?)\.
	RedirectMatch 403 (?i)/(\$(\&amp;)?|\*|\"|\.|,|&amp;|&amp;amp;?)/?$
	RedirectMatch 403 (?i)(\{0\}|\(/\(|\.\.\.|\+\+\+|\\\"\\\")
	RedirectMatch 403 (?i)(~|`|&lt;|&gt;|:|;|,|%|\\|\s|\{|\}|\[|\]|\|)
	RedirectMatch 403 (?i)/(=|\$&amp;|_mm|cgi-|etc/passwd|muieblack)
	RedirectMatch 403 (?i)(&amp;pws=0|_vti_|\(null\)|\{\$itemURL\}|echo(.*)kae|etc/passwd|eval\(|self/environ)
	RedirectMatch 403 (?i)\.(aspx?|bash|bak?|cfg|cgi|dll|exe|git|hg|ini|jsp|log|mdb|out|sql|svn|swp|tar|rar|rdf)$
	RedirectMatch 403 (?i)/(^$|(wp-)?config|mobiquo|phpinfo|shell|sqlpatch|thumb|thumb_editor|thumbopen|timthumb|webshell)\.php
&lt;/IfModule&gt;

# 6G:[USER AGENTS]
&lt;IfModule mod_setenvif.c&gt;
	SetEnvIfNoCase User-Agent ([a-z0-9]{2000}) bad_bot
	SetEnvIfNoCase User-Agent (archive.org|binlar|casper|checkpriv|choppy|clshttp|cmsworld|diavol|dotbot|extract|feedfinder|flicky|g00g1e|harvest|heritrix|httrack|kmccrew|loader|miner|nikto|nutch|planetwork|postrank|purebot|pycurl|python|seekerspider|siclab|skygrid|sqlmap|sucker|turnit|vikspider|winhttp|xxxyy|youda|zmeu|zune) bad_bot
	&lt;limit GET POST PUT&gt;
		Order Allow,Deny
		Allow from All
		Deny from env=bad_bot
	&lt;/limit&gt;
&lt;/IfModule&gt;

# 6G:[BAD IPS]
&lt;Limit GET HEAD OPTIONS POST PUT&gt;
	Order Allow,Deny
	Allow from All
	# uncomment/edit/repeat next line to block IPs
	# Deny from 123.456.789
&lt;/Limit&gt;</code></pre>
<p><strong>To implement:</strong> include the entire 6G Blacklist in the root .htaccess file of your site. Remember to backup your original .htaccess file before making any changes. Then test your pages thoroughly while enjoying a delicious beverage. If you encounter any issues, please read the <a class="anchor" href="#troubleshooting" title="Scroll to Troubleshooting">troubleshooting tips</a> and the section on <a class="anchor" href="#reporting-bugs" title="Scroll to Reporting Bugs">reporting bugs</a>. As always, feel free to share feedback and ask any questions in the <a class="anchor" href="#comments" title="Scroll to Comments">comment section</a> :)</p>
<h3 id="notes">Notes</h3>
<p>Some notes about the 6G:</p>
<p><strong>Code placement</strong></p>
<p>If running WordPress in its own directory, you may need to move the QUERY STRING rules to the .htaccess file found in the root of that directory. So for example, if WordPress is installed in a subdirectory named &ldquo;blackmothsuperrainbow&rdquo;, 6G would be included as follows:</p>
<ul>
<li>The .htaccess file contained in the <code>blackmothsuperrainbow</code> directory includes the QUERY STRING rules</li>
<li>The .htaccess file contained in the root directory contains everything else</li>
</ul>
<p>Also, in some cases it may be necessary to place the QUERY STRING rules before any WordPress Permalink rules. The best way to determine if this is necessary is to make the following request (note: replace <code>example.com</code> with your own domain name):</p>
<p><code>http://example.com/?eval(</code></p>
<p>After making that request, if you get a 403 Forbidden response, then you&#8217;re fine. If you receive a 404 error or something else, make sure that the QUERY STRING rules are included as prescribed above.</p>
<p><strong>Blocking IPs</strong></p>
<p>Apache-based firewalls and blacklists can <a href="https://perishablepress.com/eight-ways-to-blacklist-with-apaches-mod_rewrite/" title="Eight Ways to Blacklist with Apache's mod_rewrite">block just about any part of an URI request</a>: <abbr title="Internet Protocol">IP</abbr> address, user agent, request string, query string, referrer, and everything in between. But IP addresses change constantly, and user agents and referrers are easily spoofed. As <a href="https://perishablepress.com/building-the-3g-blacklist-part-1/" title="Improving Site Security by Recognizing and Exploiting Server Attack Patterns">discussed</a>, blocking via request string yields the best results: greater protection with fewer false positives.</p>
<p>With that in mind, the 6G Firewall includes a section for blocking IP addresses. This is meant to provide a convenient way for admins to block unwanted visitors/bots. But keep in mind that denying access based on IP is a <em>temporary</em> strategy, best suited for quickly blocking specific threats.</p>
<p><strong>TimThumb</strong></p>
<p>6G blocks requests for the TimThumb script/plugin with the following rule:</p>
<p><code>RewriteCond %{QUERY_STRING} (thumbs?(_editor|open)?|tim(thumb)?)\.php [NC,OR]</code></p>
<p>So if you are running TimThumb on your site, comment out or remove the previous rule, for example:</p>
<p><code># RewriteCond %{QUERY_STRING} (thumbs?(_editor|open)?|tim(thumb)?)\.php [NC,OR]</code></p>
<p>By adding a hash symbol (pound sign, whatever) <code>#</code> to the beginning of any line in your .htaccess file, you effectively turn the line into a comment that is ignored by Apache.</p>
<h3 id="changelog">Changelog</h3>
<p>Changelog for 6G Firewall:</p>
<p><strong>2016/01/31</strong></p>
<ul>
<li>Appended <code>php</code> to <code>(wp-)?config\.</code> (Thanks <a rel="external" href="https://francesdath.name/">Franceska</a>)</li>
</ul>
<p><strong>2016/01/27</strong></p>
<ul>
<li>Removed <code>%</code> from QUERY STRINGS (Thanks <a rel="external" href="http://sierracircle.org/">Adam</a>)</li>
</ul>
<p><strong>2016/01/26</strong></p>
<ul>
<li>Initial release!</li>
</ul>
<p>For more information about development, check out the <a href="https://perishablepress.com/6g-beta/" title="6G Beta">6G Beta</a>.</p>
<h3 id="faqs">FAQs</h3>
<p>A list of frequently asked questions.</p>
<p><strong>Do I need both 5G and 6G?</strong></p>
<p>Nope, 6G is designed to replace 5G, based on the evolving landscape of malicious threats and exploits. If you want to run both firewalls, that&#8217;s fine too. There will be some redundant rules, but otherwise the firewalls are 100% compatible.</p>
<p><strong>Does 6G work with WordPress?</strong></p>
<p>The 6G works beautifully with WordPress, and should help <em>any</em> Apache-powered site conserve bandwidth and server resources while protecting against <a href="https://perishablepress.com/malicious-server-scans/" title="What a Malicious Server Scan Looks Like">malicious activity</a>. That said, WordPress is the big player these days, so most of the testing is tuned to that particular platform. If you&#8217;re installing 6G on any other <abbr title="Content Management System">CMS</abbr>, please be mindful and take the time to test all of your pages.</p>
<p><strong>Can I add 6G to a live site?</strong></p>
<p>While it&#8217;s always recommended to test all code in a text/development environment, it&#8217;s totally fine to add 6G directly to a live/production site. As long as your site meets the above requirements, you should be good to go. Just to be safe, make a backup copy of your .htaccess file, as advised in the next section.</p>
<h3 id="troubleshooting">Troubleshooting</h3>
<p>If you encounter any errors or non-loading resources after installing 6G, remove the entire block of code and restore your original .htaccess file. Then continue as follows..</p>
<p><strong>Resource not loading</strong></p>
<p>If some page or resource is not loading after adding 6G, determine its URI. Make note of any non-alphanumeric characters or anything else that looks unusual. Then compare against the rules defined in 6G. If you can spot the offending pattern, you can remove it, comment it out, or report it (see <a class="anchor" href="#reporting-bugs" title="Scroll to Reporting Bugs">Reporting Bugs</a>).</p>
<p>If you are unable to determine which pattern is at issue, further investigation is required. There are numerous ways of going about it. Here is a good <a href="http://www.wpsecuritychecklist.com/the-perishable-press-halving-method/" title="The Perishable Press Halving Method">walkthrough</a> of my <a href="https://perishablepress.com/the-halving-method-of-identifying-problematic-code/" title="The Halving Method of Isolating Problematic Code">halving method</a> of isolating problematic code, which I recommend unless you have your own favorite way of troubleshooting ;)</p>
<p><strong>Server error</strong></p>
<p>If you get a server error after installing 6G, double-check that your site meets the  <a class="anchor" href="#requirements" title="Scroll to Requirements">requirements</a>. If you are sure that the requirements are met, you can either <a href="https://perishablepress.com/how-to-troubleshoot-wordpress/" title="Related tutorial: The Art of Troubleshooting WordPress">troubleshoot</a> to determine the offending rule(s), and/or you can report the issue as explained below.</p>
<h3 id="reporting-bugs">Reporting bugs</h3>
<p>If you discover any bugs, issues, or errors, <a href="https://perishablepress.com/contact/" title="Contact Jeff Starr">report them directly via my contact form</a>. Please do <strong>not</strong> report bugs in the comment area, thanks.</p>
<h3 id="show-support">Show support</h3>
<p>I spend countless hours researching and developing the 6G Firewall. I share it freely and openly with the hope that it will help make the Web a safer place for everyone.</p>
<p>If you benefit from my work with the 6G and would like to show support, consider buying one of my <a href="https://wp-tao.com/store/" title="Perishable Press Bookstore">books</a>, such as <a href="https://htaccessbook.com/" title=".htaccess made easy">.htaccess made easy</a>. You&#8217;ll get a complete guide to .htaccess, exclusive forum access, and a ton of awesome techniques for configuring, optimizing, and securing your site. </p>
<p>Of course, tweets, likes, links, and shares are super helpful and very much appreciated.</p>
<p>Your generous support allows me to continue developing the 6G Firewall and other awesome resources for the community. Thank you kindly :)</p>
<h3 id="license">License</h3>
<p>As mentioned previously, the 6G Firewall is entirely open source and free for all to use. The only requirement is that the following credit lines are included wherever 6G is used:</p>
<pre><code># 6G BLACKLIST/FIREWALL
# @ https://perishablepress.com/6g/</code></pre>
<p>Other than that, it&#8217;s all yours!</p>
<h3 id="disclaimer">Disclaimer</h3>
<p>The 6G Firewall is provided &#8220;as-is&#8221;, with the intention of helping people protect their sites against bad requests and other malicious activity. The code is open and free to use and modify as long as the first two credit lines remain intact. By using this code you assume all risk &amp; responsibility for anything that happens, whether good or bad. In short, use wisely, test thoroughly, don&#8217;t sue me.</p>
<h3 id="learn-more">Learn More..</h3>
<p>To learn more about the theory and development of the 6G Firewall, check out my articles on <a href="https://perishablepress.com/series-summary-building-the-3g-blacklist/" title="Series Summary: Building the 3G Blacklist">building the 3G</a>, <a href="https://perishablepress.com/building-the-perishable-press-4g-blacklist/" title="Building the Perishable Press 4G Blacklist">4G</a> and <a href="https://perishablepress.com/building-the-5g-blacklist/" title="Building the 5G Blacklist">5G Blacklist</a>. The <a href="https://perishablepress.com/6g-beta/" title="6G Beta">6G beta</a> article also contains some good information. And if all that&#8217;s not enough, a quick search for &#8220;blacklist&#8221; should also yield <em>many</em> results (search bar is available under the &#8220;Archives&#8221; menu).</p>
<h3 id="7g-firewall">Coming soon..</h3>
<p>Like 5G/6G? Keep an eye out for the <strong>7G Firewall Beta</strong>, which currently is in the initial development phase. <a class="external" href="https://perishablepress.com/feed/" title="Subscribe to the Perishable Press RSS Feed for free updates, news, and tutorials">Stay tuned!</a></p>
<h3 id="thank-you">Thank You</h3>
<p>Thanks to everyone who helped <a href="https://perishablepress.com/tools/htaccess/" title="Perishable Press Tools: nG Blacklist Dev">test the beta</a> and provide feedback on 6G. Also thank you to everyone who supports <a href="https://perishablepress.com/" title="WordPress, Web Design, Code &amp; Tutorials">Perishable Press</a> &mdash; I couldn&rsquo;t do it without you!</p>
<p><!--authenticate--></p>
<div class='yarpp-related'>
<h3>Related posts:</h3><ol>
<li><a href="https://perishablepress.com/5g-firewall-beta/" rel="bookmark" title="5G Firewall Beta">5G Firewall Beta </a></li>
<li><a href="https://perishablepress.com/5g-blacklist-2012/" rel="bookmark" title="5G Blacklist 2012">5G Blacklist 2012 </a></li>
<li><a href="https://perishablepress.com/2014-micro-blacklist/" rel="bookmark" title="2014 Micro Blacklist">2014 Micro Blacklist </a></li>
<li><a href="https://perishablepress.com/the-perishable-press-4g-blacklist/" rel="bookmark" title="The Perishable Press 4G Blacklist">The Perishable Press 4G Blacklist </a></li>
<li><a href="https://perishablepress.com/5g-blacklist-2013/" rel="bookmark" title="5G Blacklist 2013">5G Blacklist 2013 </a></li>
</ol>
</div>
		</div>

		
	</div>

</article>
