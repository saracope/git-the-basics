# Class: Intro to Git and Github

Git is a distributed version control system, it can be used as a server out of the box. Dedicated Git server software adds access control, display the contents of a Git repository via the web, and help to manage multiple repositories. 

GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as wikis and basic task management tools for every project.

The workshop will be a mix of lectures and hands-on exercises. 

**Topics covered**

* What are Version Control systems?
* Git workflow
* Setting up repos
* Staging changes
* Committing changes
* Using & merging branches
* Using remote repos 

**Slides**

**Resources**
* For Windows users, download and install [Git Bash](https://git-scm.com/downloads)
* Command line [cheat sheet](https://www.git-tower.com/blog/command-line-cheat-sheet/)
* Git [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
* Additional [GitHub tutorial](https://try.github.io/)

**Tech requirements**

* Your laptop (Mac, PC, Linux) and charger
* A modern web browser (Chrome, Firefox, Safari)

**Payment**

This session is Free!

### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

1. Clone the repository
   ```sh
   $ git clone https://github.com/saracope/git-the-basics.git
   ```

1. Navigate to the folder
   ```sh
   $ cd git-the-basics
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view the presentation

   You can change the port by using `npm start -- --port=8001`.

### Folder Structure

- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)


