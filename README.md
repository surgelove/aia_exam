# aia_exam
Examine instruments for profitability, using LLMs, vibe coding only, no manual editing.

# Manual
Create project in github and add readme
Clone the repo in VS Code
Copy a weekly .tar in root

# Prompts (Edit mode)
`create a gitignore file and add .tar to it`\
`look for .tar files in the  current directory and untar them`\
`in the db folder, connect to the sqlite file aia_big and tell me the column names and give me a sample of 10 rows`\
`after the sample is taken, select * from this table where instrument is USDCAD, and order by date, and the date column should be 4 hours earlier`\
`what are some web based options to dislpay graphs`\
`list all of them`\
`there are some missing`\
`using the dataframe created, add 2 columns to it: xee is an EMA 15 minutes and xer is a triple EMA 15 minutes. Display the graph using echarts`\
`the graph does not show`\
`correct current cell so the graph doesnt start at 0`\
`in current cell, dont display numerical values in the graph as overlay`\
`in current cell, dont show dots`\
`in current cell, when i choose a period in the graph, use the available space in the graph for the y axis`\
`the graph does 15 rows, not 15 minutes as i asked, should be based on the date column and do the ema and tema at 15 minutes intervals`\
`in current file, make buy gray, xee blue and xer purple, all of them solid lines`\
`in current cell, graph white background`\
`TypeError: GraphicRect.init() got an unexpected keyword argument 'left'`\
`in current cell, make the graph with white background`\
`TypeError: AxisOpts.init() got an unexpected keyword argument 'scale'`\
`in current cell, in graph dont show tje legend`\
`in current cell in current graph, when i select a period, use the entire y axis`\
`in current cell dataframe, when xer crosses xee up, put the buy price in a column cross_up, and cross_dn when crossing down`\
`add .db to gitignore`\
`for each code cell, insert a markdown cell above that explains what follows, as a title with ### that makes the code below collapsible`\
`no, make the code below collapsible, not the markdown`\
