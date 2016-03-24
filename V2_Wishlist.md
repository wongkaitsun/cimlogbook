  * Application structure to mimic Pyro best practices
  * Conserve screen realestate : dock to the side of the screen or hide off the screen
  * LogMultiple sessions concurrently
  * Watch variables via cim logging (Logger.watch())
> > -> Extend to Logger.watch(object)
  * Alerts
  * On init refresh current connection and save the last session to file
  * Load Log files
  * Memory profiling via watch implementation (graph)
  * custom filters including regex support for log searches
  * validate logbook performance under high load / may dump older objects or write them out to AIR sqllite db
  * User preference: Look for updates (monthly/weekly/on-demand)


Nice to have

  * Colored labels (a-la Mac Labels) via context menu
  * Evolve CIM logging to enable command to be sent via LogBook to a project
  * Ability to graph numerical data