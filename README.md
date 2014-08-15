# SMF Tools repository.

This repository contains a few useful scripts for SMF, such as install/upgrade or repair scripts, database cleaning up, etc.
All scripts in this repository are under BSD 3-clause license, unless specified otherwise.

# Tool explanation

* databasecleanup
* **install_script**: a (nice I hope :P) template that can be used to create manual installation scripts for mods. At the moment the hook part is fully working, the database part is still WIP.
* **ban_script.php**: a script that allows perform multiple user banning at once. You can provide a list of usernames that you want to ban or you can ask the script to scan a board you have collected all the users you want to ban in (the name must be the subject of the topic).
* **fix_packages.php**: with SMF 2.0 after a large upgrade (to cleanup forum, not after an upgrade from SMF 1.x) the mods are still marked as installed, with this script you can invert that state.
* **Populate.php**: a script that can be used to populate a forum with dummy users (usually useful for testing), originaly written by SlammedDime http://code.mattzuba.com/populator
* **repair_settings.php**: updated version of repair_settings.php it supports multiple attachments directory, fix several other problems...oh I don't remember everything! :P
* smfinfo.php
* status.php
* webinstall.php

# Tools download

Apart from cloning the repo, you can find the files more useful to end-users at the [download page](https://github.com/emanuele45/tools/downloads)
=======
SMF Tools repository.

This repository contains a few useful scripts for SMF, such as install/upgrade or repair scripts, database cleaning up, etc.
All scripts in this repository are under [BSD 3-clause license](http://www.opensource.org/licenses/BSD-3-Clause) license, unless specified otherwise.

Feel free to fork this repository and make your desired changes.

Please see the [Developer's Certificate of Origin](https://github.com/norv/tools/blob/master/DCO.txt) in the repository:
by signing off your contributions, you acknowledge that you can and do license your submissions under the license of the software.

######How to contribute:
* fork the repository. If you are not used to Github, please check out [fork a repository](http://help.github.com/fork-a-repo).
* branch your repository, to commit the desired changes.
* sign-off your commits, to acknowledge your submission under the license of the project.
 * an easy way to do so, is to define an alias for the git commit command, which includes -s switch (reference: [How to create Git aliases](http://githacks.com/post/1168909216/how-to-create-git-aliases))
* send a pull request to us.
