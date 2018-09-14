# comics2018
the 2018 edition of cca's comics website

--

`npm install -g serve`

From the root directory:
`serve -s .`

Navigate to `localhost:5000/directory.html` and begin exploring



NOTE:  `data/students.json` is the most important file


NOTE:  `thesis.html` & `directory.html` follow similar set of steps:
1. Page initial load.
2. jQuery loads
3. When page finishes loading and DOM is ready:
4. fire off request for students.json
5. Use the students.json data, which is full of file path and
display data, to extract filepaths for assets needed from elsewhere in the repository.
6. Use those filepaths to assets to build jQuery DOM elements.
7. Attach those elements to the existing DOM mentioned in steps 1 and 3.