# Resume: Vasyl Kuzma

One-page resume of Vasyl Kuzma, Full-stack Developer (React, Node.js) in Prague, as a plain HTML page.

- **Online:** https://kuzmavasil74.github.io/Resume-Vasyl-Kuzma/
- **PDF:** https://kuzma-dev-com.vercel.app/Vasyl_Kuzma_CV.pdf
- **Portfolio:** https://kuzma-dev-com.vercel.app

## Files

- `index.html`: the content.
- `styles.css`: screen layout plus an A4 print layout that fits on one page.

## Making the PDF

Open `index.html` in Chrome, press **Print**, choose **Save as PDF** and turn off **Headers and footers**. Or from the terminal on macOS:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --no-pdf-header-footer --print-to-pdf=Vasyl_Kuzma_CV.pdf "file://$PWD/index.html"
```

Then copy the PDF to `public/Vasyl_Kuzma_CV.pdf` in the [KuzmaDev.com](https://github.com/kuzmavasil74/KuzmaDev.com) repository so the portfolio's **Download CV** button serves the new version.
