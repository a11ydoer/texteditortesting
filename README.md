Git repository: <a href="https://github.com/a11yfirst/texteditortesting">Text editor testing</a>

This document can also be found in <a href="https://github.com/a11yfirst/texteditortesting/blob/master/README.md">A11yFirst github repository.</a>
<h2>Pre packaged/pre existing features</h2>
<table>
<tbody>
<tr>
<td>Criteria</td>
<td>CKEditor</td>
<td>TinyMCE</td>
</tr>
<tr>
<td>Most Recent Version</td>
<td>4.4.1</td>
<td>4.2.7</td>
</tr>
<tr>
<td>Documentation</td>
<td>http://docs.ckeditor.com/</td>
<td>https://www.tinymce.com/docs/</td>
</tr>
<tr>
<td>License</td>
<td><a href="https://en.wikipedia.org/wiki/GNU_General_Public_License">GPL</a>, <a href="https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License">LGPL</a>, <a href="https://en.wikipedia.org/wiki/Mozilla_Public_License">MPL </a>/ Commercial</td>
<td><a href="https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License">LGPL,</a> Commercial</td>
</tr>
<tr>
<td>Accessibility Checker</td>
<td><a href="http://ckeditor.com/addon/a11ychecker">a11y checker</a>(Available as Add-on and with payment)

<a href="http://docs.ckeditor.com/#!/guide/dev_accessibility_checker">Documentation</a>/ <a href="https://www.tinymce.com/pricing/">Demo</a></td>
<td><a href="https://www.tinymce.com/docs/plugins/a11ychecker/">a11y checker</a>(Available as plugin and with Enterprise subscription)
<a href="https://www.tinymce.com/pricing/">Demo(check the bottom of the page)</a></td>
</tr>
<tr>
<td>Installing Add-ons/Plugins Options</td>
<td> <a href="http://ckeditor.com/addons/plugins/all">Add-ons repository</a> (464 plugins)</td>
<td><a href="https://www.tinymce.com/docs/get-started/work-with-plugins/">Plugin list (48)</a></td>
</tr>
<tr>
<td>Expert Opinion/Recommendation</td>
<td>Matt King, APG member(Accessibility expert is working on CKEditor project)</td>
<td> Default text editor for WordPress. Wordpress is the choice of Univeristy of Illinois library Content Managemtn System(CMS).</td>
</tr>
<tr>
<td>Keyboard accessibility</td>
<td><a href="http://docs.ckeditor.com/#!/guide/dev_shortcuts">Keyboard shortcuts</a></td>
<td><a href="https://www.tinymce.com/docs/advanced/accessibility/">Keyboard shortcuts </a></td>
</tr>
<tr>
<td>Browser compatibility</td>
<td>Desktop environments:
-Internet Explorer(8.0 and 9.0 – close to full support, 10 and 11 – full support, 9.0 Quirks Mode and 9.0 Compatibility Mode – limited support.)
-Firefox, Chrome, Safari, Microsoft Edge, Opera: Latest stable release – full support.
<a href="http://docs.ckeditor.com/#!/guide/dev_browsers">Reference</a></td>
<td>Firefox(3.0+),IE(8+),Chrome(1.0+),Opera(11.0+),Safari(5+)
<a href="http://archive.tinymce.com/wiki.php/TinyMCE3x:Browser_compatiblity">3.x version reference</a></td>
</tr>
<tr>
<td>Copy-Paste
(ex.google)</td>
<td> Better than TinyMCE*</td>
<td>Copy-past from word plugin is available in Premium features</td>
</tr>
<tr>
<td>Image upload and handling</td>
<td>Feature rich.*</td>
<td>
<p class="font-bree-serif">limited option*</p>
<p class="font-bree-serif"><a href="http://ww.moxiemanager.com/">MoxieManager:</a> Image/File manager server side component.(Paid component)</p>
</td>
</tr>
<tr>
<td>Developer Guide</td>
<td><a href="http://docs.ckeditor.com/#!/guide">CKEditor Guides and SDK</a></td>
<td>
<p class="light">"<a href="https://www.tinymce.com/docs/advanced/">Explore Advanced Topics" in TinyMCE documentation</a></p>
</td>
</tr>
<tr>
<td>Mobile Ready</td>
<td>iOS 6+, Chrome for Android**
<b>(</b>Safari (iOS 6+) – close to full support, Chrome (Android) – close to full support, Internet Explorer Mobile (Windows Phone 8.1+) – support under evaluation.) <strong>Reference</strong></td>
<td>No Info</td>
</tr>
<tr>
<td>Developer Community</td>
<td><a href="http://ckeditor.com/Forums/CKEditor">Forum</a>
<ul>
<ul>
 	<li>Registered developers:<strong>116,648</strong></li>
 	<li>Number of downloads:16,419,009</li>
 	<li><a href="http://stackoverflow.com/tags/ckeditor/info">StackOverflow CKEditor forum</a></li>
</ul>
</ul>
</td>
<td> <a href="http://community.tinymce.com/forum/">TinyMCE forum</a>
<ul>
 	<li>Registered users: 23,140</li>
 	<li>Number of downloads: unknown</li>
 	<li>Wordpress default editor</li>
</ul>
</td>
</tr>
</tbody>
</table>
<h2>Functionality/Methods</h2>
<table>
<tbody>
<tr>
<td>Criteria</td>
<td>CKEditor</td>
<td>TinyMCE</td>
</tr>
<tr>
<td> Filtering Content</td>
<td> <a href="http://sdk.ckeditor.com/samples/acf.html">Advanced Content Filter</a>

Filters incoming HTML content by transforming and deleting disallowed elements, attributes, classes and styles.</td>
<td> <a href="https://www.tinymce.com/docs/configure/content-filtering/">Content filtering</a>

The way the editor handles the input and output of content.</td>
</tr>
<tr>
<td>How plugin works</td>
<td><a href="http://docs.ckeditor.com/#!/api/CKEDITOR.plugins">CKEditor Plugins </a></td>
<td>Internal Plugin <a href="https://www.tinymce.com/docs/configure/integration-and-setup/#plugins" target="_blank">Code Example</a> (hint: use <code>plugins</code> string)
External <a href="https://www.tinymce.com/docs/configure/integration-and-setup/#external_plugins" target="_blank">Code Example</a>(hint: Use <code>external_plugins</code> object)</td>
</tr>
<tr>
<td>Copy and Paste from Word

How to configure copy and paste from another program works into chosen text editor</td>
<td><a href="http://ckeditor.com/addon/pastefromword">Paste from Word</a> (Free plugin for the editor)</td>
<td><a href="https://www.tinymce.com/docs/enterprise/paste-from-word/">Paste From Word</a> (included in the TinyMCE Enterprise download)</td>
</tr>
<tr>
<td>Consistency (Content Editable, Editable Content)</td>
<td><a href="http://docs.ckeditor.com/#!/api/CKEDITOR.dom.range"> CKEDITOR.dom.range</a>

<a href="http://docs.ckeditor.com/#!/api/CKEDITOR.plugins.contextMenu">CKEDITOR.plugins.contextMenu</a></td>
<td></td>
</tr>
</tbody>
</table>
<h2>Test Case</h2>
<table>
<tbody>
<tr>
<td>Criteria</td>
<td>CKEditor</td>
<td>TinyMCE</td>
</tr>
<tr>
<td><span style="color: #993300;">Test Case</span>: Heading Structure</td>
<td> In Progress (Jon Gunderson)</td>
<td> In Progress(William Weathers)</td>
</tr>
<tr>
<td><span style="color: #993300;">Test Case</span>: Copy and Paste from MS Word</td>
<td> In Progress (Jemma)</td>
<td> In Progress (Jemma)</td>
</tr>
</tbody>
</table>
<h2>References</h2>
*http://www.krizalys.com/article/ckeditor-vs-tinymce
**http://socialcompare.com/en/comparison/javascript-online-rich-text-editors(confirmed that all the bugs are closed for CKEditor)

Git repository: <a href="https://github.com/a11yfirst/texteditortesting">Text editor testing</a>
