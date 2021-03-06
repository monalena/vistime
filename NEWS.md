# 0.6.0 (dev)
- corrected font colors of Presidents example on help page

# 0.5.0 (CRAN)
- added a new argument `showLabels` to choose whether or not the event labels shall be drawn - improves layout of dense timelines
- new argument `lineInterval`: the distance in seconds that vertical lines shall be drawn (to reduce plot size and increase performance). When omitted, a heuristic (as before) is used.
- improved heuristic of vertical line drawing

# 0.4.0
- line width calculation for ranges improved (thicker lines if less events happening simultaneously)
- new parameter: `linewidth` to override the calculated line width for events
- layout and labelling improvements
- simplified examples
- improved error checking

# 0.3.0
- new parameters: 
    + `title` (a title for the timeline)
    + `tooltips` (column name of data that contains individual tooltips)
    + `fontcolors` (column name of data that contains color of the event font)
- ordering of groups in plot is now the same as the order of "groups" column in data
- added more complex example and removed school data/example
- changed `colors` argument default to "color" (i.e. if a column `color` is present in your data, it will be used for coloring the events)
- bugfix if data contains only one event
- bugfix where events where not correctly categorized into their respective groups
- improved error checking
- improved drawing of vertical lines for certain ranges
- major improvement of intelligent levelling of ranges (" \_-\_&#175;-&#8212;")

# 0.2.0
- improved error checking
- various bugfixes

# 0.1.0
First public release on 29/01/2017
