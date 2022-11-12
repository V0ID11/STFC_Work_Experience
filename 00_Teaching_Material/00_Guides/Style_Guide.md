# Accelerator Simulation Framework
## :notebook_with_decorative_cover: :art: Style Guide: Formatting for Git repositories
---

# :speech_balloon: Commit messages
> When committing changes to files, Git advises using a commit message to record the basics of said changes. This is done with the command:
> 
>     git commit -m 'commit message'
>     
> Currently we adopt the following syntax and format for a Git commit message in an Accelerator Simulation Framework repository:
> 
>     <type>[main directories] additional information if necessary
>     
> In it's complete form one would write the following in a terminal:
> 
>      git commit -m '<type>[main directories] additional information'
>     
> **type** For example:
> - add
> - update
> - remove
> - bugfix
> - output
> - doc
> - example
> 
> **main directories**:
> - directories/files changed
> 
> **additional information**
> - status (complete/incomplete/ongoing)
> - details:
>   - **bug**: what is broken, what are the results (expected or otherwise)
>   - **bugfix**: what was broken, how it was fixed
>   - **add**: what was added and why
>   - **update**: content of update
>   - **output**: type of simulation, if it is complete/ongoing, type of output (bunch distribution, twiss file...)
>   - **remove**: what was removed and why
>   - **doc**: documentation modification
>   - **example**: example modification

> Example sequence of commit messages:
> 
>       git commit -m '<add>[hello world] initial code'
>       git commit -m '<remove>[hello world] initial code removed'
>       git commit -m '<bug>[my simulation] SCARF submission script not working'
>       git commit -m '<bugfix>[my simulation] SCARF submission script typo corrected'
>       git commit -m '<doc>[my simulation] instructions for correctly running on SCARF'     
>       git commit -m '<output>[my simulation] completed tracking sim on SCARF, bunch distributions added'     
>       git commit -m '<output>[my simulation] bunch plotting script and plots added'  
>       git commit -m '<example>[my example simulation] tested example of particle tracking dumping the bunch at every turn'


