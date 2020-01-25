# HTML to PDF

Quickly create/render PDF from an URL via the browser. This doesn't support cross origin.

#### Uses
 - [html2canvas](https://html2canvas.hertzen.com/)
 - [jsPdf](https://www.npmjs.com/package/jspdf)

#### Parameters
 - `url` (**required**) - url that will be used to create the PDF
 - `title` - title of the PDF
 - `delayConvert` - how long to wait to convert the page after it loads. Defaults to 150 milliseconds
 - `containerId` - specific id of an element on the page to convert otherwise will use the full document

#### Example URL
 http://IP:port/htmlToPdf.html?url=/order/invoice/index.html&title=Invoice

![Demo](demo.gif)
