# Shutdown or Switch widget for KDE Plasma 6

A minimalistic KDE Plasma 6 widget for quick accessing the leave options (shutdown, reboot, suspend, logout, lockscreen, etc.) or to quickly switch between different users.

<div>
<img src="https://raw.githubusercontent.com/Davide-sd/shutdown_or_switch/master/imgs/img1.png" width=250/>
<img src="https://raw.githubusercontent.com/Davide-sd/shutdown_or_switch/master/imgs/img2.png" width=250/>
</div>

This is a customized version of the widget [user switcher](https://github.com/KDE/kdeplasma-addons/tree/master/applets/userswitcher) created by Kai Uwe Broulik.

*Master* branch deals with Plasma 6. *plasma5* branch contains the code for Plasma 5.

## Installation

### From openDesktop.org

1. Go to **[Opend Desktop](https://www.opendesktop.org/p/1288430/)**
2. Click on the Files tab
3. Click the Install button

### From within the Plasma workspace

1. If your widgets are locked, right-click the desktop and select `Unlock Widgets`
2. Right-click the desktop and select `Add Widgets...`
3. Click the `Get new widgets` button in the Widget Explorer that just opened
4. Type `Shutdown or Switch` into the search field
5. Click the `Install` button next to `Shutdown or Switch`


## How to contribute

Here are the recommended steps to contribute to this widget:

1. fork this repository.
2. download the repository: `git clone https://github.com/<YOUR-USERNAME>/ip_address.git`
3. enter the project directory: `cd ip_address`
4. create a new branch: `git branch -d YOUR-BRANCH-NAME`
5. do the necessary edits and commit them.
6. push the branch to your remote: `git push origin YOUR-BRANCH-NAME`
7. open the Pull Request.

PRs are welcomed. However, each PR should be concise and on point with its intended goal. If a PR claims to implement `feature A` but it also modifies other parts of the code unnecessarely, than it is doing too much and I won't merge it.


**<ins>NOTE about AI-LLM usage</ins>**: I have nothing against the use of these tools. However, many people are unable to properly control their outputs. In practice, these tools often modifies too much. With this in mind:

* If there is a comment in the code, it is very likely to be important to me (the maintainer). Equally important are variable names, function names etc. If the LLM is going to change variable names, remove comments or reorganize the code just for the sake of it, I'll close the PR immediately.
* I prefer that you code manually and understand exactly what you are doing. Remember that at this moment, testing is done manually after each edit, which is time consuming.

