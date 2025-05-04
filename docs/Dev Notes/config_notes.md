# Configuration Notes

## Markdown
To avoid having zebra tables in markdown. Able to incorporate the following: 
> It's not possible with CSS, but there is a workaround. Just add an empty row between your rows.
```css
<tr><tr>
```

## Bulk Image Conversion using Magick v7
This is used for image conversion from websites or other photos 

For a single file: 
> magick file_name_input.webp file_name_output.jpg

For bulk files and convert into a directory called **FOLDER**, use: 

<pre>
> mkdir output
> magick mogrify -format JPEG -path OUTPUT *.webp 
</pre>

## Applying whitespace into markdown files 

```html
<pre></pre>
```
This will add an additional space to your text to format it into a multi-line. Alternativly can use: 
```html
&nbsp;
```
Reference: [Whitespace preserved in markdown](https://stackoverflow.com/questions/15721373/how-do-i-ensure-that-whitespace-is-preserved-in-markdown)

## Keyboard Bindings

- Creating customer macros with VIA - [video reference](https://www.youtube.com/watch?v=aKQH09xxWEU)
- [Documentation](https://docs.qmk.fm/keycodes) for the key bindings for QMK Keyboards

## Troublshooting

Google Cloudsites and Cloudfare integration

- Redirecting naked IP addresses for a google site account - [video reference](https://www.youtube.com/watch?v=MeZ0US6u24E)

- To avoid the 525 error in Cloudflare for SSL handshake not being received. An additional rule is required to the naked DNS name to route to www* address

## Windows Plugins 

- customize windows actions and perform macros across custom key bindings - [autohotkey](https://www.autohotkey.com/)

- To have the script always run at startup, open up run->shellstartup->copy/paste the script into this directory folder

