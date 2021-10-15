# REFERENCE
W3
https://www.w3schools.com/

# PAGES <!--------------------------------------------->

**SPOILER ALERT/BUTTON**
https://wowchemy.com/docs/content/writing-markdown-latex/#toggle-lists

{{< spoiler text="Click to view the spoiler" >}}
You found me!
{{< /spoiler >}}

**STATIC REFERENCE**
https://wowchemy.com/docs/content/writing-markdown-latex/#link-to-a-file

To link to a file, such as a PDF, in the body of your content, place the file in your `static/uploads/` folder and then link to it using the following form:

{{% staticref "uploads/cv.pdf" "newtab" %}}Download my CV{{% /staticref %}}

**CITE**
https://wowchemy.com/docs/content/writing-markdown-latex/#cite

{{< cite page="/publication/preprint" view="4" >}}

**TABLE OF CONTENTS**
https://wowchemy.com/docs/content/writing-markdown-latex/#table-of-contents

{{< toc >}}
{{< toc hide_on="xl" >}}

**FIGURES**
https://wowchemy.com/docs/content/writing-markdown-latex/#figures

{{< figure src="image.jpg" id="wowchemy" width="100%" >}}

**CALL-TO-ACTION (CTA) BUTTON**
https://wowchemy.com/docs/content/writing-markdown-latex/#call-to-action-buttons

{{< cta cta_text="Do something" cta_link="/" cta_new_tab="false" >}}

{{< cta cta_text="Do something" cta_link="/" cta_new_tab="false" cta_alt_text="Alternative action" cta_alt_link="/" cta_alt_new_tab="false" >}}

**LIST CHILD PAGES**
https://wowchemy.com/docs/content/writing-markdown-latex/#list-child-pages

{{< list_children >}}

**ICONS**
https://wowchemy.com/docs/content/writing-markdown-latex/#inline-image

{{< icon name="terminal" pack="fas" >}} Terminal  
{{< icon name="python" pack="fab" >}} Python  
{{< icon name="r-project" pack="fab" >}} R

fab pack: https://fontawesome.com/icons?d=gallery&s=brands
fas pack: https://fontawesome.com/icons?d=gallery&s=regular,solid
ai  pack: https://jpswalsh.github.io/academicons/ 

Emoji cheat sheet: http://www.webpagefx.com/tools/emoji-cheat-sheet/

**TWEET**
https://wowchemy.com/docs/content/writing-markdown-latex/#embed-a-feed

{{< tweet 666616452582129664 >}}

**CALLOUTS**
https://wowchemy.com/docs/content/writing-markdown-latex/#callouts

**Note**
{{% callout note %}}
A Markdown callout is useful for displaying notices, hints, or definitions to your readers.
{{% /callout %}}

**Warning**
{{% callout warning %}}
Here's some important information...
{{% /callout %}}

**AUDIO**
https://wowchemy.com/docs/content/writing-markdown-latex/#audio

{{< audio src="markvard.mp3" >}}

**VIDEO**
https://wowchemy.com/docs/content/writing-markdown-latex/#videos

{{< video src="my_video.mp4" controls="yes" >}}
{{< youtube w7Ft2ymGmfc >}}
{{< vimeo 146022717 >}}

**CHARTS**
https://wowchemy.com/docs/content/writing-markdown-latex/#charts

{{< chart data="chart" >}}

**CVS TABLE**
https://wowchemy.com/docs/content/writing-markdown-latex/#csv-table

For larger tables, save your spreadsheet as a CSV file in your page’s folder and then render it by adding the Table shortcode to your page:

{{< table path="results.csv" header="true" caption="Table 1: My results" >}}



# SLIDES <!-------------------------------------------->
**REVEAL CSS EXAMPLE**
https://github.com/rodrigoalcarazdelaosa/fisiquimicamente/blob/main/assets/css/reveal_custom.css


**BACKGROUND IMAGE**
{{< slide background-image="/media/boards.jpg" >}}

**BACKGROUND COLOR**
{{< slide background-color="#00447c" >}}

**SLIDE CLASS**
{{< slide class="my-style" >}}


**BOTTOM SLIDES**
{{% section %}}

Slide 1

---

Slide 2

{{% /section %}}


# ARCHETYPES <!-------------------------------------------->
https://github.com/wowchemy/wowchemy-hugo-themes/tree/main/wowchemy/archetypes