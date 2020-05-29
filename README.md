# cae-workbench
cae-workbench for product developer who use script manner to analytics for cad model.
Programming languages are type script (UI), java (server side).
User can access and use workbench with his web browser.

# main function to be developed
1. User signup and sign in and approval by admin
2. Workspace management, project management, member management
3. Job management
- Job creation
  - Parametic type (second priority)
    Job creation UI should provide user (engineer) with parametic type job creation UI which is acceptable by commercial Job schedulers
  - Script program type (first priority)
    A engineer can do programming by himself using programming language like python, bash script, tool command language
    Web IDE which language is bash script, python, tool command language.
    Programming language should be added dynamically
  - Pipeline manner (third priority)
    Similiar to jenkins' pipeline but in this case each pipe is algorithm
    In this case, K8S can be used instead of HPC as a infrastructure
- Job submit into job scheduler (ex: IBM LSF)
- Job status monitoring
  - Job cancel/restart could be performed by user in monitoring UI
  - Job processing status and processing log with status
- Job result
  - Viewer for job result
- Many kind of commercial Job scheduler should be supported.
4. Library management
- In-house library (python, bash, TCL) should be managed and re-used by user (engineer)
- At backend, repository like nexus could be used, and workbench should provide engineer with related function 
5. Etc
- Personalization (Thema, Language-no means programming language)
- Notice
  For example, A python library is created newly or updated for some engineer (script developer) it should be noticed to him
- My projects
- Search
  By source code file name, by contents, by date, by engineer and so on
