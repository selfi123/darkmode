# darkmode


let css = `
  html, body, div, span, a, p, h1, h2, h3, h4, h5, h6, table, td, th, ul, ol, li, section, article, footer, header, nav, main, aside {
    background-color: #121212 !important;
    color: #ffffff !important;
    border-color: #333 !important;
  }
  img, video, iframe {
    filter: invert(1) hue-rotate(180deg) !important;
  }
  *:not(img):not(video):not(iframe) {
    background-color: #121212 !important;
    color: #ffffff !important;
  }
`;
let style = document.createElement('style');
style.appendChild(document.createTextNode(css));
document.head.appendChild(style);
