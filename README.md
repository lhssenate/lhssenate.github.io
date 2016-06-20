# LHS Student-Faculty Senate Website

Hello! If you're seeing this, you're probably looking at the source code for 
this website! Hopefully eventually you may be helping out with maintaining 
this site, which should be quite intuitive.

(If you have any questions, feel free to contact me, Clive Chan LHS '16, at cc@clive.io.)

## Steps to start working on this site

1. Install [Git](https://git-scm.com/) and [Ruby](https://www.ruby-lang.org/en/documentation/installation/#rubyinstaller).
2. Open up a command line or terminal, and run these commands:
   * `gem install jekyll`
   * `git clone https://github.com/lhssenate/lhssenate.github.io`
   * `cd lhssenate.github.io`
   * `jekyll serve`
3. Navigate to http://localhost:3000 in your browser, and you should see an exact copy of the Senate website.
4. Modify files however you want and reload to see your changes.
   * You should look up the documentation for Markdown (and Jekyll), which is what all these files are written in.
   * You can also just write plain old HTML and it should work fine.
   * Test and experiment! Figure out how it works, and have fun with it!
5. Press ctrl-C in the terminal to stop the Jekyll server, and run these commands to submit your changes to the actual website:
   * `git add -A`
   * `git commit -m "[some message describing your changes]"`
   * `git push origin master`
   * The last step will require a GitHub account and permissions on the GitHub repository. Ask the Senate webmaster.
6. Your changes should now be reflected on https://lhssenate.github.io!
