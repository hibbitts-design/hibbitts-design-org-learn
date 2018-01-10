---
title: Integrating Grav with Moodle
taxonomy:
    category: docs
metadata:
    'twitter:card' : summary
    'twitter:site' : @hibbittsdesign
    'twitter:title' : Integrating Grav with Moodle
    'twitter:description' : Step-by-step guide for embedding Grav Open Course Hub pages within Moodle.
    'twitter:image': 'http://learn.hibbittsdesign.org/coursehub/integrating-grav-with-moodle/grav-with-moodle.png'
---

The 'chromeless' feature of the Grav Course Hub hides a site's global navigation elements for seamlessly displaying Course Hub page content within the Moodle LMS in three different ways:

* [Displaying Course Hub Content Within a Moodle Page](#displaying-course-hub-content-within-a-moodle-page)
* [Displaying Course Hub Unit Summary in a Moodle Topic](#displaying-course-hub-unit-summary-in-a-moodle-topic)
* [Adding Course Hub Content using the External Tool](#adding-course-hub-content-using-the-external-tool)

#### Displaying Course Hub Content Within a Moodle Page

##### 1. View the page you want to embed, and copy the full URL of that page

![](../../images/displaying-course-hub-content-within-a-moodle-page/view-the-page-you-want-to-embed--and-copy-the-full-url-of-that-page.png)

##### 2. Navigate to the Moodle Section/Page you want to embed your Course Hub content into, and choose the "Edit" option

![](../../images/displaying-course-hub-content-within-a-moodle-page/navigate-to-the-moodle-section-page-you-want-to-embed-your-course-hub-content-into--and-choose-the--.png)

##### 3. Tap the "Show more buttons" button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--show-more-buttons--button.png)

##### 4. Tap the "HTML" editor button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--html--editor-button.png)

##### 5. Paste the HTML iFrame code, using the below example

```
<p><iframe scrolling="no" style="border: 0px #ffffff none; " src="http://example.com/chromeless:true" allowfullscreen="allowfullscreen" height="540px" width="100%"></iframe></p>
```

![](../../images/displaying-course-hub-content-within-a-moodle-page/paste-the-html-iframe-code--using-the-below-example.png)

##### 6. Highlight the default URL within the iFrame code, not including the "/chromeless=true" text (this will be needed to be included after your URL)

![](../../images/displaying-course-hub-content-within-a-moodle-page/highlight-the-default-url-within-the-iframe-code--not-including-the---chromeless-true--text--this-wi.png)

##### 7. Paste the previously copied Course Hub page HTTP URL, and ensure that the "/chromeless:true" text is still part of the URL

![](../../images/displaying-course-hub-content-within-a-moodle-page/paste-the-previously-copied-course-hub-page-http-url--and-ensure-that-the---chromeless-true--text-is.png)

##### 8. Tap the "Save changes" button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--save-changes--button.png)

##### 9. Review the final result of the embedded iFrame code.

If all of the content expected is not displayed, or there is too much space between the bottom of the content and the next Moodle item, you may want to re-edit your iFrame code and adjust the "height" value.


![](../../images/displaying-course-hub-content-within-a-moodle-page/review-the-final-result-of-the-embedded-iframe-code.png)

#### Displaying Course Hub Unit Summary in a Moodle Topic

##### 1. View the Unit (i.e. Week) page you want to include in a Topic, and copy the full URL of that page

![](../../images/displaying-course-hub-content-within-a-moodle-page/view-the-unit--ie-week--page-you-want-to-include-in-a-topic--and-copy-the-full-url-of-that-page.png)

##### 2. Navigate to the Moodle Topic you want to embed your Course Hub content into, and choose the "Edit" option

![](../../images/displaying-course-hub-content-within-a-moodle-page/navigate-to-the-moodle-topic-you-want-to-embed-your-course-hub-content-into--and-choose-the--edit--o.png)

##### 3. Tap the "Show more buttons" button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--show-more-buttons--button-1.png)

##### 4. Tap the "HTML" editor button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--html--editor-button-1.png)

##### 5. Paste the HTML iFrame code, using the below example

```
<p><iframe scrolling="no" style="border: 0px #ffffff none; " src="http://example.com/chromeless:true" allowfullscreen="allowfullscreen" height="540px" width="100%"></iframe></p>
```

![](../../images/displaying-course-hub-content-within-a-moodle-page/paste-the-html-iframe-code--using-the-below-example-1.png)

##### 6. Highlight the default URL within the iFrame code, not including the "/chromeless=true" text (this will be needed to be included after your URL)

![](../../images/displaying-course-hub-content-within-a-moodle-page/highlight-the-default-url-within-the-iframe-code--not-including-the---chromeless-true--text--this-wi-1.png)

##### 7. Add additional URL flags to only display the Unit summary ("/summaryonly:true") and hide the page title ("/hidepagetitle:true").

![](../../images/displaying-course-hub-content-within-a-moodle-page/add-additional-url-flags-to-only-display-the-unit-summary----summaryonly-true---and-hide-the-page-ti.png)

##### 8. Tap the "Save changes" button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--save-changes--button-1.png)

##### 9. Review the final result of the embedded iFrame code.

If all of the content expected is not displayed, or there is too much space between the bottom of the content and the next Moodle item, you may want to re-edit your iFrame code and adjust the "height" value.


![](../../images/displaying-course-hub-content-within-a-moodle-page/review-the-final-result-of-the-embedded-iframe-code-1.png)

#### Adding Course Hub Content using the External Tool

Please note that you can also add Course Hub Content using the URL object in Moodle.

##### 1. View the page you want to add to add using the External Tool, and copy the full URL of that page

![](../../images/displaying-course-hub-content-within-a-moodle-page/view-the-page-you-want-to-add-to-add-using-the-external-tool--and-copy-the-full-url-of-that-page.png)

##### 2. Navigate to the Moodle item you want to add an External Tool link to and tap the Add option

![](../../images/displaying-course-hub-content-within-a-moodle-page/navigate-to-the-moodle-item-you-want-to-add-an-external-tool-link-to-and-tap-the-add-option.png)

##### 3. Choose the "External Tool" option

![](../../images/displaying-course-hub-content-within-a-moodle-page/choose-the--external-tool--option.png)

##### 4. Tap the "Add" button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--add--button.png)

##### 5. Enter the name for the External Tool link

![](../../images/displaying-course-hub-content-within-a-moodle-page/enter-the-name-for-the-external-tool-link-.png)

##### 6. Paste the previously copied Course Hub page HTTPS URL into the "URL Redirect" field, and add "/chromeless:true" to the end of the URL

![](../../images/displaying-course-hub-content-within-a-moodle-page/paste-the-previously-copied-course-hub-page-https-url-into-the--url-redirect--field--and-add---chrom.png)

##### 7. Tap the "Save and display" button

![](../../images/displaying-course-hub-content-within-a-moodle-page/tap-the--save-and-display--button.png)

##### 8. Review the final result of the added Course Hub page

![](../../images/displaying-course-hub-content-within-a-moodle-page/review-the-final-result-of-the-added-course-hub-page.png)
