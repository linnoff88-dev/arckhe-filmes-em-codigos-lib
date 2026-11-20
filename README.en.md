# Films in code

![The same seaside temple shifts from a line drawing to a painting and then a realistic landscape.](guia/assets/banner.jpg)

[PT](README.md) · [EN](README.en.md) · [ES](README.es.md)

## About

You want to change one detail in a film and keep what already works. This library shows how AI can write the instructions that draw each image. If you’re curious and have never programmed, start with a demo, then open the project to see how the creator made that scene. All you need to explore is a browser.

[Open the guide](https://inematds.github.io/filmes-em-codigos-lib/guia/en/) · [Libraries of styles and films in code](https://inematds.github.io/filmes-em-codigos-lib/guia/en/#biblioteca) · [High realism in code](https://inematds.github.io/filmes-em-codigos-lib/guia/en/#realismo)

## The process, from start to finish

1. Open the guide, choose a style or high realism, and watch a demo.
2. Open the author’s repository, the page that stores the project files. If you’d like help reading the code, paste the request below into your assistant along with the project URL.
3. The assistant explains how the detail appears in the frame. Check the explanation against the film and the indicated code.
4. To create your scene, choose a reference. The assistant writes the program, the engine renders a frame, and you compare the result with the reference before approving the sequence.
5. The engine saves the approved frames, and the editing program combines them with the audio.

> Explain how the creator of this project drew one frame. Choose a detail I can recognize in the film and show me where it appears in the code.

---

## Technical setup

To view the library on your computer, use Git and Python 3. In a terminal, clone the project, enter its folder and start the server. Then open the address below.

```sh
git clone https://github.com/inematds/filmes-em-codigos-lib.git
cd filmes-em-codigos-lib
python3 -m http.server 8000
```

[localhost:8000/guia/en/](http://localhost:8000/guia/en/)
