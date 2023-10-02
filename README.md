<article class="main-page-content" lang="en-US"><header><h1>Marking up a letter</h1></header><div class="section-content"><ul class="prev-next">
    <li><a class="button secondary" href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML"><span class="button-wrap"> Previous </span></a></li>
    <li><a class="button secondary" href="/en-US/docs/Learn/HTML/Introduction_to_HTML"><span class="button-wrap"> Overview: Introduction to HTML</span></a></li>
    <li><a class="button secondary" href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content"><span class="button-wrap"> Next  </span></a></li>
</ul>
<p>We all learn to write a letter sooner or later; it is also a useful example to test our text formatting skills. In this assignment, you'll have a letter to mark up as a test for your HTML text formatting skills, as well as hyperlinks and proper use of the HTML <code>&lt;head&gt;</code> element.</p>
<figure class="table-container"><table>
  <tbody>
    <tr>
      <th scope="row">Prerequisites:</th>
      <td>
        Before attempting this assessment you should have already worked through
        <a href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started">Getting started with HTML</a>,
        <a href="/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML">What's in the head? Metadata in HTML</a>,
        <a href="/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals">HTML text fundamentals</a>,
        <a href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks">Creating hyperlinks</a>, and
        <a href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting">Advanced text formatting</a>.
      </td>
    </tr>
    <tr>
      <th scope="row">Objective:</th>
      <td>
        Test basic and advanced HTML text formatting, use of hyperlinks, and use
        of HTML &lt;head&gt;.
      </td>
    </tr>
  </tbody>
</table></figure></div><section aria-labelledby="starting_point"><h2 id="starting_point"><a href="#starting_point">Starting point</a></h2><div class="section-content"><p>To begin, get the <a href="https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/marking-up-a-letter-start/letter-text.txt" class="external" target="_blank">raw text you need to mark up</a>, and the <a href="https://github.com/mdn/learning-area/blob/main/html/introduction-to-html/marking-up-a-letter-start/css.txt" class="external" target="_blank">CSS to style the HTML</a>. Create a new <code>.html</code> file using your text editor or use an online tool such as <a href="https://codepen.io/" class="external" target="_blank">CodePen</a>, <a href="https://jsfiddle.net/" class="external" target="_blank">jsFiddle</a>, or <a href="https://glitch.com/" class="external" target="_blank">Glitch</a> to complete the tasks.</p>
<div class="notecard note" id="sect1">
  <p><strong>Note:</strong> If you get stuck, then ask us for help — see the <a href="#assessment_or_further_help">Assessment or further help</a> section at the bottom of this page.</p>
</div></div></section><section aria-labelledby="project_brief"><h2 id="project_brief"><a href="#project_brief">Project brief</a></h2><div class="section-content"><p>For this project, your task is to mark up a letter that needs to be hosted on a university intranet. The letter is a response from a research fellow to a prospective PhD student concerning their application to the university.</p></div></section><section aria-labelledby="blockstructural_semantics"><h3 id="blockstructural_semantics"><a href="#blockstructural_semantics">Block/structural semantics</a></h3><div class="section-content"><ul>
  <li>Use appropriate document structure including doctype, and <a href="/en-US/docs/Web/HTML/Element/html"><code>&lt;html&gt;</code></a>, <a href="/en-US/docs/Web/HTML/Element/head"><code>&lt;head&gt;</code></a> and <a href="/en-US/docs/Web/HTML/Element/body"><code>&lt;body&gt;</code></a> elements.</li>
  <li>In general, the letter should be marked up as an organization of headings and paragraphs, with the following exception. There is one top level heading (the "Re:" line) and three second level headings.</li>
  <li>Use an appropriate list type to mark up the semester start dates, study subjects, and exotic dances.</li>
  <li>Put the two addresses inside <a href="/en-US/docs/Web/HTML/Element/address"><code>&lt;address&gt;</code></a> elements. Each line of the address should sit on a new line, but not be in a new paragraph.</li>
</ul></div></section><section aria-labelledby="inline_semantics"><h3 id="inline_semantics"><a href="#inline_semantics">Inline semantics</a></h3><div class="section-content"><ul>
  <li>The names of the sender and receiver (and <em>Tel</em> and <em>Email</em>) should be marked up with strong importance.</li>
  <li>The four dates in the document should have appropriate elements containing machine-readable dates.</li>
  <li>The first address and first date in the letter should have a class attribute value of <em>sender-column</em>. The CSS you'll add later will cause these to be right aligned, as it should be in the case in a classic letter layout.</li>
  <li>Mark up the following five acronyms/abbreviations in the main text of the letter — "PhD," "HTML," "CSS," "BC," and "Esq." — to provide expansions of each one.</li>
  <li>The six sub/superscripts should be marked up appropriately — in the chemical formulae, and the numbers 103 and 104 (they should be 10 to the power of 3 and 4, respectively).</li>
  <li>Try to mark up at least two appropriate words in the text with strong importance/emphasis.</li>
  <li>There are two places where the letter should have a hyperlink. Add appropriate links with titles. For the location that the links point to, you may use <code>http://example.com</code> as the URL.</li>
  <li>Mark up the university motto quote and citation with appropriate elements.</li>
</ul></div></section><section aria-labelledby="the_head_of_the_document"><h3 id="the_head_of_the_document"><a href="#the_head_of_the_document">The head of the document</a></h3><div class="section-content"><ul>
  <li>The character set of the document should be set as utf-8 using the appropriate meta tag.</li>
  <li>The author of the letter should be specified in an appropriate meta tag.</li>
  <li>The provided CSS should be included inside an appropriate tag.</li>
</ul></div></section><section aria-labelledby="hints_and_tips"><h2 id="hints_and_tips"><a href="#hints_and_tips">Hints and tips</a></h2><div class="section-content"><ul>
  <li>Use the <a href="https://validator.w3.org/" class="external" target="_blank">W3C HTML validator</a> to validate your HTML. Award yourself bonus points if it validates.</li>
  <li>You don't need to know any CSS to do this assignment. You just need to put the provided CSS inside an HTML element.</li>
</ul></div></section><section aria-labelledby="example"><h2 id="example"><a href="#example">Example</a></h2><div class="section-content"><p>The following screenshot shows an example of what the letter might look like after being marked up.</p>
<p>
  <img src="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter/letter-update.png" alt="Example" width="845" height="1830" loading="lazy">
</p></div></section><section aria-labelledby="assessment_or_further_help"><h2 id="assessment_or_further_help"><a href="#assessment_or_further_help">Assessment or further help</a></h2><div class="section-content"><p>If you would like your work assessed or are stuck and want to ask for help:</p>
<ol>
  <li>Put your work into an online shareable editor such as <a href="https://codepen.io/" class="external" target="_blank">CodePen</a>, <a href="https://jsfiddle.net/" class="external" target="_blank">jsFiddle</a>, or <a href="https://glitch.com/" class="external" target="_blank">Glitch</a>.</li>
  <li>Write a post asking for assessment and/or help at the <a href="https://discourse.mozilla.org/c/mdn/learn/250" class="external" target="_blank">MDN Discourse forum Learning category</a>. Your post should include:
    <ul>
      <li>A descriptive title such as "Assessment wanted for Marking up a letter".</li>
      <li>Details of what you have already tried and what you would like us to do; for example, tell us if you're stuck and need help or want an assessment.</li>
      <li>A link to the example you want assessed or need help with, in an online shareable editor (as mentioned in step 1 above). This is a good practice to get into — it's very hard to help someone with a coding problem if you can't see their code.</li>
      <li>A link to the actual task or assessment page, so we can find the question you want help with.</li>
    </ul>
  </li>
</ol><ul class="prev-next">
    <li><a class="button secondary" href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML"><span class="button-wrap"> Previous </span></a></li>
    <li><a class="button secondary" href="/en-US/docs/Learn/HTML/Introduction_to_HTML"><span class="button-wrap"> Overview: Introduction to HTML</span></a></li>
    <li><a class="button secondary" href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Structuring_a_page_of_content"><span class="button-wrap"> Next  </span></a></li>
</ul></div>
</section>
  <aside class="metadata"><div class="metadata-content-container">
    <div id="on-github" class="on-github"><h3>Found a content problem with this page?</h3>
      <ul><li>
        <a href="https://github.com/mdn/content/edit/main/files/en-us/learn/html/introduction_to_html/marking_up_a_letter/index.md" title="This will take you to GitHub, where you'll need to sign in first." target="_blank" rel="noopener noreferrer">
          Edit the page on GitHub</a>.</li>
        <li><a href="https://github.com/mdn/content/issues/new?template=page-report.yml&amp;mdn-url=https%3A%2F%2Fdeveloper.mozilla.org%2Fen-US%2Fdocs%2FLearn%2FHTML%2FIntroduction_to_HTML%2FMarking_up_a_letter&amp;metadata=%3C%21--+Do+not+make+changes+below+this+line+--%3E%0A%3Cdetails%3E%0A%3Csummary%3EPage+report+details%3C%2Fsummary%3E%0A%0A*+Folder%3A+%60en-us%2Flearn%2Fhtml%2Fintroduction_to_html%2Fmarking_up_a_letter%60%0A*+MDN+URL%3A+https%3A%2F%2Fdeveloper.mozilla.org%2Fen-US%2Fdocs%2FLearn%2FHTML%2FIntroduction_to_HTML%2FMarking_up_a_letter%0A*+GitHub+URL%3A+https%3A%2F%2Fgithub.com%2Fmdn%2Fcontent%2Fblob%2Fmain%2Ffiles%2Fen-us%2Flearn%2Fhtml%2Fintroduction_to_html%2Fmarking_up_a_letter%2Findex.md%0A*+Last+commit%3A+https%3A%2F%2Fgithub.com%2Fmdn%2Fcontent%2Fcommit%2F751d58669499de0c6ea0d5b356e0e1448418c5d3%0A*+Document+last+modified%3A+2023-06-30T06%3A21%3A35.000Z%0A%0A%3C%2Fdetails%3E" title="This will take you to GitHub to file a new issue." target="_blank" rel="noopener noreferrer">Report the content issue</a>.</li><li><a href="https://github.com/mdn/content/blob/main/files/en-us/learn/html/introduction_to_html/marking_up_a_letter/index.md?plain=1" title="Folder: en-us/learn/html/introduction_to_html/marking_up_a_letter (Opens in a new tab)" target="_blank" rel="noopener noreferrer">View the source on GitHub</a>.</li></ul>Want to get more involved?<!-- --> <a href="https://github.com/mdn/content/blob/main/CONTRIBUTING.md" title="This will take you to our contribution guidelines on GitHub." target="_blank" rel="noopener noreferrer">Learn how to contribute</a>.</div><p class="last-modified-date">This page was last modified on<!-- --> <time datetime="2023-06-30T06:21:35.000Z">Jun 30, 2023</time> by<!-- --> <a href="/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter/contributors.txt">MDN contributors</a>.</p></div></aside><div class="empty-place bottom-banner"></div></article>
