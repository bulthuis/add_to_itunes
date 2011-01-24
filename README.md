Add to iTunes
=============

Add to iTunes is a little script help with adding video files to iTunes. It is
most useful when set to run automatically when files are added to a folder.


Requirements
------------

- Ruby
- Rake
- [Handbrake CLI](http://handbrake.fr/downloads2.php)


Setup
-----

Configure the paths in config.yml for your setup. Run the script when files are added to the <code>original\_videos\_path</code>.


Tasks
-----

<code>videos:convert</code> 
: Converts files and adds them to iTunes.

<code>videos:move</code> 
: Moves the converted files to iTunes.


Known Issue
-----------

Once files are converted, they are only sometimes added to iTunes. This means
that you might have to run the <code>videos:move</code> task manually from time to time.
