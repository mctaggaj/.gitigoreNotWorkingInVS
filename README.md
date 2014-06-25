.gitigoreNotWorkingInVS
=======================

**/*.js* does not work recursively

after a build
>app.js
>app.js.map
>IGNORED.js
>IGNORED.map
>folder1>IGNORED.js
>folder1>IGNORED.map
>folder1>folder2>IGNORED.js
>folder1>folder2>IGNORED.map
show up in the untracked files list under the team explorer
