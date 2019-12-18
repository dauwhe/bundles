# bundles


At the moment you must have Chrome 79+ with Web Bundles Enabled for these to work. 

Flag: chrome://flags/#web-bundles

Useful introduction: https://web.dev/web-bundles/

Spec repo: https://github.com/WICG/webpackage

## What's here?

1. [Moby-Dick](https://github.com/dauwhe/bundles/raw/master/moby.wbn) as a very simple HTML bundle, with no Javascript. 

2. [Flatland](https://github.com/dauwhe/bundles/raw/master/flatland.wbn) (only part one) as very simple example of the [W3C Audiobook specification](https://w3c.github.io/audiobooks/) as a web bundle. Once you play the first audio, it will autoplay the rest. There's also navigation between sections. 

## What's not here?

Anything fancy. Most more complex ebooks I would make require iframes, and at the moment Chrome won't load an `iframe src` from a bundle. I'm assuming that will change with time. 

## Why should I care?

1. ebooks without reading systems

2. possible accessible replacement for PDFs

3. ad-hoc app distribution

4. shareable web content without servers! I think in some ways this really lowers the barrier to participation on the web on your own terms. Can you imagine creating a beautiful, artful letter in HTML to send to a friend? 

## Why is my code so bad?

I'm not a real developer.



