Some Tasks
==========

convert README to markdown
--------------------------

    git mv README README.md
    # mark it up with markdown
    cheat markdown

To view it w/o having to upload it first you can get a quick ghetto viewing by:
 using tilt and a ghetto browser tool:

    mkdir ~/bin
    vi ~/.bashrc
    # append following line to end of file:
    export PATH=$PATH:$HOME/bin
    # save and open a new terminal

    curl https://gist.github.com/raw/988187/browser -o ~/bin/browser
    chmod 755 ~/bin/browser 
    # test it by typing:
    echo '<h1>hi hi hi</h1>' | browser

    # all that work just so we could install tilt and try it:
    gem install tilt
    tilt TASK.md | browser
