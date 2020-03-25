**Hypothesis**

* assume task definition is perfect
* bpml is perfect
* bpml is linear
* bpml only have if, goto and subroutine (basic mode)
* we have creators for all tasks tags
* creators can not reject tasks
* creators finishes tasks as fast as possible
* simple tasks like "tag", "set consensus" does not have a consensus
* creators works for free
* money for the production budget is know by all creators
* time is not important
* every data can be accessed by every creator
* no report is autmatically prepared

**Execution**
```
execute{      
until all task are done
  take first task undone
        tag task
        set consensus for task type
        execute task w/consensus
        mark task done
}  
```

**Database**

* consensus types
* creators list
* tag list
* files (produced outcomes)

