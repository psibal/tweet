A Pen created at CodePen.io. You can find this one at http://codepen.io/billymoon/pen/rKCGf.

 …or create a new repository on the command line
echo "# tweet" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/psibal/tweet.git
git push -u origin master


…or push an existing repository from the command line
git remote add origin https://github.com/psibal/tweet.git
git push -u origin master



...updating github
git add *
git commit -m "first commit"
git push -u origin master



--
$git config --global credential.helper cache
# Set git to use the credential memory cache


$git config --global credential.helper 'cache --timeout=3600'
# Set the cache to timeout after 1 hour (setting is in seconds)