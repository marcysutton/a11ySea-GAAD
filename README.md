# Global Accessibility Awareness Day 2018 - A11ySea

Slides for the Accessibility Seattle Meetup

By Marcy Sutton, Senior Front-end Engineer

Slide URL: [http://marcysutton.github.io/a11ySea-GAAD](http://marcysutton.github.io/a11ySea-GAAD)

## Installation

### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the repository
   ```sh
   $ git clone https://github.com/marcysutton/a11ySea-GAAD.git
   ```

5. Navigate to the project folder
   ```sh
   $ cd reveal.js
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.

## License

MIT licensed

Copyright (C) 2018 Marcy Sutton, http://marcysutton.com
