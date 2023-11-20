# ARCHY 488 Lithic Technology Lab

Canvas site for the course: [https://canvas.uw.edu/courses/1629611](https://canvas.uw.edu/courses/1632617)

This repository contains a Dockerfile that UW-IT use to provide RStudio on JupyterHub for the class. I update the Dockerfile to provide a custom set of R packages to the class so they don't have to install anything. The browser-based instance of RStudio for the class is freely accessible to registered students here: https://jupyter.rttl.uw.edu/2023-spring-archy-488-a/user-redirect/rstudio (UW ID log in required, file storage is attached to your UW ID and persists through the quarter). To make this work for UW-IT, I activate 'Actions' in 'Settings', then trigger a run, e.g. by updating the README, which builds a package hosted on GitHub's container registery. I send the URL of the package to UW-IT. 

You can also click on this button to write code in your web browser (no log in required, file changes do not persist beyond the current session): [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/benmarwick/ARCHY-488-Lithic-Technology-Lab/master?urlpath=rstudio)

You can also click on "Code", select the codespaces tab, and click "[Create codespace on main](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=614008148)", wait a few moments for the virtual machine to lauch a customized Visual Studio Code interface in your browser. Then click on the Ports tab (this may take another moment to appear after the instance opens), and clicking on the "globe" icon to open the link. This should open a new tab showing an RStudio login page. The default login user/password here is rstudio/rstudio. Once RStudio opens, consider using File -> New Project (cf. https://github.com/espm-157/reproducibility-template)



