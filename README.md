# Text editor testing
Please upload codes used for text edtiors testing and document comparison criteria. 

The goal is comparing two editors based on 

- Extensiveness of documentation 
- Plugin/Add-ons example
- How easy to implement the same functionality in each editor. – we picked implementing heading structure
- How to inform users about accessibility checking 
- More

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
<td></td>
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
 	<li>Registered developers:<strong>116,648</strong></li>
 	<li>Number of downloads:16,419,009</li>
 	<li><a href="http://stackoverflow.com/tags/ckeditor/info">StackOverflow CKEditor forum</a></li>
</ul>
</td>
<td><a href="http://community.tinymce.com/forum/">TinyMCE forum</a>
<ul>
 	<li>Registered users: 23,140</li>
 	<li>Number of downloads: unknown</li>
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
<td> Filtering Content:

Filters incoming HTML content by transforming and deleting disallowed elements, attributes, classes and styles.The way the editor handles the input and output of content.</td>
<td> <a href="http://sdk.ckeditor.com/samples/acf.html">Advanced Content Filter</a></td>
<td> <a href="https://www.tinymce.com/docs/configure/content-filtering/">Content filtering</a></td>
</tr>
<tr>
<td>Add-ons /Plugin Option:

How plugin works</td>
<td></td>
<td> Allows to specify which plugins TinyMCE will attempt to load when starting up.
(hint: use <code>plugins</code> string)
<a href="https://www.tinymce.com/docs/configure/integration-and-setup/#plugins" target="_blank">Code Example</a>Specify a URL based location of plugins outside of the normal TinyMCE plugins directory.
(hint: Use <code>external_plugins</code> object)
<a href="https://www.tinymce.com/docs/configure/integration-and-setup/#external_plugins" target="_blank">Code Example</a></td>
</tr>
<tr>
<td>Copy and Paste(ex.MS word):

How to configure copy and paste from another program works into chosen text editor</td>
<td></td>
<td></td>
</tr>
<td><span style="color: #993300;">Test Case</span>: Heading Structure</td>
<td></td>
<td></td>
</tr>
<tr>
<td><span style="color: #993300;">Test Case</span>: Copy and Paste from MS Word</td>
<td></td>
<td></td>
</tr>
</tbody>
</table>
<h2>References</h2>
<ul>
 	<li>*http://www.krizalys.com/article/ckeditor-vs-tinymce</li>
 	<li>**http://socialcompare.com/en/comparison/javascript-online-rich-text-editors(confirmed that all the bugs are closed for CKEditor)</li>
</ul>
Git repository: <a href="https://github.com/a11yfirst/texteditortesting">Text editor testing</a>
