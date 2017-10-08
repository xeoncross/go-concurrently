In the following application we have:

1. a main process that gets events and instructs the Boss
2. a Boss that managers the workers until:
 		A) Work is done
 		B) Process gives Boss new work
3. Workers/Plugins that work until:
 		A) They are Finished
 		B) Boss tells them quit
