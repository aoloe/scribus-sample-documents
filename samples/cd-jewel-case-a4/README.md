# CD Jewel case

CD artwork (booklet, inlay, label, ...) for a classic CD jewel case.

The document was created by Peter B. (pb@xbloome.com) and used for layouting the audio CD artwork of the album "X marks the spot" of the band XBloome:

http://www.xbloome.com/

The version of Scribus used was v1.3.3.11.

## Content of the document

The document contains:

- 12-page booklet pages,
- Inla,
- Tra,
- CD labe,
- CD label (Neato stickers).


###  12-page booklet pages

We've had 12 pages, but it should be quite easy to adapt to more or less booklet pages. What's quite helpful is the numbering of pages, because sometimes it's not quite obvious which booklet side is on which page.

Additionally, I've linked the booklet text frames in the right order, so you can just copy/paste text into one of them, and it will be distributed across the pages correctly.

Only exception is the last page, because that one is usually used for non-continous text, such as credits, etc.

### Inlay:

This is the back side of the CD's jewel case

### Tray:

If you're using a jewel case with a transparent tray (not black, like it usually is), you can have a graphic underneath the CD within the case.

### CD label:

This is the image actually printed on the CD itself. If the CD is printed professionally, there is usually no offset or bleeding areas, so you might have to adjust the size manually to the size specification of the production facility you're producing at.

(In my case it was e.g. changing the inner circle from 16mm to 17mm size. So no big deal)

### CD label (Neato stickers):

For printing a CD label in a copyshop (e.g. for creating a dummy-master to send to the production facility), we've used CD-label stickers. Unfortunately, each vendor has a different positioning of the stickers on the A4 sheet, so this document only works with stickers from 'Neato'.

Tip: If you're using a different CD-label sticker set, you can quickly adapt the document by scanning the sticker page and put it in a background layer in Scribus, scaling it 1:1. Then you can easily move/resize the document's printing boundaries to match the sticker page (This is how I've done it).


## Sample content:

I've left some example content in the document, as paragraph styles, because I've made the experience that it's easier to delete/modify/adapt something, than to start from zero - even with paragraph styles or text. 


## Printing limits & size information:

The document contains 2 layers that should _not be printed_:

1) Printing limits:

This layer contains visual boundaries about bleeding edges, safe-areas, etc. - so you can align your content properly, without having to fear that there are nasty surprises when comes to final printing and cutting.

## Size information:

I've found it quite practical to have exact size information (in millimeters) about the printing limits, because this makes it very easy to adapt the document to e.g. other applications or environments.

(You might want to turn that layer invisible during layouting, because it may distract optically)


## Fonts

For correctly viewing the document you should make sure that the following fonts are installed:

  - AR PL Ukai TW Book (a chinese font: should be removed from the document)
  - Forgotten Futurist Bold and Regular:  
    <http://www.dafont.com/forgotten-futurist.font>
  - FreeSans Bold, BoldOblique, Medium:  
    <https://www.gnu.org/software/freefont/>


## Todo

- [ ] Cleanup the use fonts (remove AR PL Ukai TW Book)
- [ ] Simplify the use of layers?
- [ ] Provide screenshots.
- [ ] Eventually add the PDF.
