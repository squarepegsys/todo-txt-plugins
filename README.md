# todo-txt-plugins

This is Mike Hostetler's own [Todo.txt](http://todotxt.com/)
actions. All of them are borrowed/stolen from other places. See their
projects for more information

Both `contextview` and `projectview` are from
[the1ts project])(https://github.com/the1ts/todo.txt-plugins) but
switched. So `contextview` in that project is `projectview` in this
project, and vice-versa. This is to play nice with
[SimpleTask Cloudless](https://play.google.com/store/apps/details?id=nl.mpcjanssen.simpletask).

The Note add-on is from
[mgarrido][https://github.com/mgarrido/todo.txt-cli/tree/note/todo.actions.d].

Recur is from
[paulroub's project](https://github.com/paulroub/todo.txt-recurring-tasks). I
run it on a server using a cronjob:

     11 * * * * /home/user/bin/todo.sh recur
	 

I don't need to run it every hour but I do anyway.


