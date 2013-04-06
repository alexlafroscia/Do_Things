#Do Things

An Alfred Workflow for controlling Things.app

***

##The Commands

So far, Do can only do 3 things:

1. Add a new task to the Inbox or "Today" lists
2. List and completed the tasks in the inbox and "Today" lists
3. List your projects and the items in them
4. Log your completed tasks
5. Empty the trash

### The Inbox

To list the tasks to the inbox, the command is

    do inbox
    
Alfred will display the items in the inbox, and if you action one of them, it will mark the item as completed.

To add an item to the inbox, just keep typing! For example, the command

    do inbox example task
    
will add a task named "example task" to the inbox

### The "Today" List

The "Today" list works just like the "inbox" ones, just substitute "inbox" for "today", like this

    do today
    
or this

    do today example task
    
### Working with Projects

To access a list of projects, the command is

    do projects
    
When you action one of these options (which will appear in the dropbown), it will run a script that passes the selected project back to another workflow, which will then display the list of its tasks.

As of right now, this command is also ```do projects *project name*``` which might get confusing when using ```do projects``` to display the list. I will be fixing this in the future; consider it a "beta" feature for right now.

### Logging Tasks

To log the completed tasks, the command is

    do log

### Emptying the Trash

To empty the trash, the command is

    do empty

*** 
##Contact Information

If you want to get a hold of me, feel free to contact me on [Twitter](https://twitter.com/AlexLaFroscia).  I'd love to get some feedback, positive or negative, as well as suggestions and tips on improving Do!
