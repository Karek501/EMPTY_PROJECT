# EMPTY_PROJECT
empty classical structured project (to spare time)

contains /libs, /src, /include, /bin

To simplify a little the implementation of futur header and cpp files,
a linking/include sequence is already implemented in the toplevel CMakeLists.txt.
More precisely: The main program.cpp is located in /src
The subdirectory /include contains .header and .cpp files ("LOAD_libOperatorManagerWrapper", because i just pasted from former project)
The sublevel related CMakeLists is configured with add_library (cmake language)
in the Toplevel CmakeLists, links are made.

THE OBJECTIVE IS TO HELP at REPEATING SUCH OPERATIONS WHEN DEVELOPPING FURTHER THE PROJECT
BY GIVING A READY-TO-USE CASE


PUSH ON GITHUB:
git add * (indicate that all the content has to be copied to github)
git commit -m "label of the new commit"
git push -u origin main
