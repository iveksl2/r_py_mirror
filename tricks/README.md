**Q: How do I list all the functions associated with a library or package to quickly grok around?** 

Within `R` one can list all the loaded packages with the `search()` command. One can then just list all the exposed
functions within any package through `ls` command. I.E. `ls('package:stats')` or `ls('package:dplyr')`.

Within `Python` one can `dir(lib)` or `dir(obj)`to list the associated attributes of an object. 

