dita-ot-plugins
===============

DITA Open Toolkit Community Plugins

This repository serves to organize the various DITA Community plugins
into a single project, where each plugin is a separate git submodule. 
This makes it easier to work with the plugin projects as a unit.

This project also provides release packages of all the plugins.

If you clone or fork this repository, you must then initialize the
submodules in order to get the source for each plugin, using the "git submodule init" and 
"git submodule update" commands
in the dita-ot-plugins directory, e.g.:

~~~~
cd ~/workspace
cd clone https://github.com/dita-community/dita-ot-plugins.git
cd dita-ot-plugins
git submodule init
git submodule update
git submodule foreach git checkout master
~~~

After running these commands, you should have an up-to-date repo for each plugin, checked out to the branch "master".

If any plugin is updated, you can update your local repo using the command:

~~~~
git submodule foreach git pull
~~~~

If you would like to contribute a plugin to the DITA Community organization, contact one of the DITA Community organization owners and we'll set up a repository for you and add the plugin to this project as a submodule.

Contact: ekimber@dita-community.org

## Contributing to the DITA Community organization

If you are interested in being a member of the DITA Community Github project team,
please contact one of the team members or create an issue indicating that you'd
like to contribute. We can always use help maintaining the repository.
  
## Other Sources of Plugins

* The DITA Open Toolkit is available at http://dita-ot.github.io 
* DITA for Publishers provides a number of plugins, including EPUB, HTML5, and 
  enhanced HTML output. It also provides a general map-driven framework that
  can be used by other plugins. http://dita4publishers.sourceforge.net
* The DITA Users Yahoo Group (https://groups.yahoo.com/neo/groups/dita-users/info) 
  has a files area that includes community-contributed plugins.  

   
   
