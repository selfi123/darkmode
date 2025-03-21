let style = document.createElement('style');
style.innerHTML = `
    * { background: #121212 !important; color: #fff !important; border-color: #333 !important; }
    img, video, iframe { filter: invert(1) hue-rotate(180deg) !important; }
`;
document.head.appendChild(style);
