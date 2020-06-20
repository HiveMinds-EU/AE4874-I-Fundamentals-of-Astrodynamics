# SOW-MKI46 Brain Reading and Writing Content:

1. ~~The complete course planning. (It automatically compiles a pdf with the planning, and more importantly, it automatically generates all the taskwarrior commands to add your tasks to your tasklist (taskwarrior).)~~
2. Old exam solutions templates, the actual solutions are in a private repo shared with collaborators.test
3. Templates for summaries of the following course related material: 

3.a Papers to read

3.b Presentations

3.c Lectures

3.d Optional ~~templates for~~ literature reviews

# How to participate 
4. goto:
https://docs.google.com/spreadsheets/d/19_cDitN3zIDJ-0dzYjyM7MMhUfv3d08VRKC3NFfKkZo/edit?usp=sharing and allocate yourself to:

4.a Papers to read

4.b Presentations (only 1 needed per team, so if your teammate summarised this you can perhaps assist your teammate with their lecture summary or something to balence it out.)

4.c Lectures

5. Then fork this repository, create the summaries in the latex files/templates I created for you
6. Send me a message/ pull request when you're done.
7. I inspect your files, if they are complete you are granted access to the work of your fellow peers.


# FAQ
## How do I use latex/overleaf with (this) git? 
0. Get a github account (and log in).
1. Click on "fork" here in this website (top right).
0. Get an Overleaf account (and log in on overleaf.com).
1. Click new project (in Overleaf).
2. Click Import from git(?hub?).
3. Then click on this repository that you forked (named :SOW-MKI46 Brain-Reading-And-Writing.
4. Then you just start working in it. 
5. PS. on menu set the main file to /lectures/<yourlecture>/main.tex if that is the main overleaf must show/compile.
6. When you're done, click on Menu>github> push changes to github.
  

## How to use this (git) with latex locally
0. You can git clone this repository
1. You can edit pdf's in this repository with TexMaker (OpenSource):https://www.xm1math.net/texmaker/download.html
2. You can compile/create the pdf's in this repository by telling TexMaker to use MikTex (OpenSource): https://download.cnet.com/MiKTeX-64-bit/3000-18483_4-75851644.html
Or:
https://miktex.org/download
https://miktex.org/howto/install-miktex
3. Or just do it in overleaf (Skip to step `7.b` and `7.c`)

2. And then send a pull request after you have pushed your changes. After inspection of your pull request (and acceptance), you will be made collaborator in the private repo, to re-do your pull request which will be accepted. This will grant you access to all the exam solutions generated collectively! 

To change (a copy of) this a latex exam solution template after you have installed TexMaker:
  0. Open Main.tex file in TexMaker:
  
  ![1](./HowToUseTexMaker/1.png)
  
  ![1](./HowToUseTexMaker/2.png)
  
  1. Make sure you have opened `Main.tex` and not `someChapterOrOther.tex` and click the triangle meaning "Run/compile". That exports the PDF to your/this directory.
  
  
  2. Click `Options>Define current document as "Master Document"`.
  ![1](./HowToUseTexMaker/master_document.png)
  
  3. Selected `PDFLatex` and `View PDF` (see next pic)
  
  3.a Press `f2`,`f11` to compile the bibliography, followed by `f2` to include the bibliography in the report. Then:
  
  4. Press `f6` to compile the pdf. (left triangle in pic below)
  
  ![1](./HowToUseTexMaker/3.png)
  
  5. Press `f7` to preview the pdf in the right half of your screen. (Right triangle in pic below)
  
  ![1](./HowToUseTexMaker/4.png)
  
  6. If you get error saying: "no logfile" or anything else, it's most likely becuase you havent installed "the compiler". So latex is just some kind of computer language, Texworks is an editor for files of that language, and Miktex (also open source) is a compiler. So you can already edit your tex files, but to also build the pdf, install miktex and tell texworks where it can find your miktex `.exe` file (via `Options`> ?compiler? ..). Actually you have 3 options to create your latex solution:
  
   7.a  Install miktex, (F did that already) AND link the target destination of miktex in texworks.
  
   7.b Import your forked repository to overleaf (get a temporary free trial acount with ggr.la mail.
  
   7.c Import your forked repository to overleaf by pressing: menu>new>import zip file> put your 2010-xx-yy folder Content into a zip, and click import. Then you can just work in overleaf.

  
### Configuring Texmaker for convenience ###
Normally you can switch between your tabs/files with `Alt+PageDown` and `Alt+PageUp`. However if you also have FLux installed on windows, those shortcuts are already mapped to reducing the blue content in your screen. The shortcuts wont work in that case. To switch between screens fast with your keyboard:

  7. Click Options.
  
  8. Click Configure Texmaker.
  
  ![1](./HowToUseTexMaker/5.png)

  9. Click tab: "Shortcuts" and scroll down to Action: "Next Documents".
  
  10. Click the "shortcut" next to `Next Document` and Press the shortcut you want, e.g. press `Ctrl+PageDown`.
  
  ![1](./HowToUseTexMaker/6.png)
  
  11. Then do the same for the `Previous Document`



If you are having troubles with any of the above steps/don't know how you do any of that, feel free to click on: "issue" and type your question :)
