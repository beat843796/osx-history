We want to create a slick and simple page that renders a timeline of the history of osx versions.

- The timeline should go vertically, newest on top, oldest on bottom
- Each version is a circle, left to the circle the release date, right to the circle version number and name separated by a slash (/)
- each circles is connected with a line, the distance between the circels (and therefor the length of the line) must be proportional to the real original release date
- only vertical scroll allowed
- page must be responsive
- separate CSS from htlm so wen can style without touching the html
- load json from data/osx.json (dont include in html)
- make it super simple and fast
- when i click on a circle, a callout should appear showing the following information: Version as title, name, darwin version, release date, latest verison, latest verison release date, support status as a colored icon (red: unsupported, yellow: supported, green: latest version)
- Circles must have a solid background with no inner dot and should fully cover the line behind
- Callout must also close when the x button is pressed
