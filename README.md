# cgyeung.github.io

Notes for the project portfolio at PG&E

Intro: 
  * Purpose is to land a data science job in Vancouver, salvaging the value of the PG&E experience
  * In order to accomplish that, must continuously monitoring the match betwen potential job opportunities and experiences
  * Experiences may need to be repackaged a bit to make it applicable to the outside world
  * Must not lie but 'ok' to stretch the truth a little: business use cases cannot be made up, but implementation can
  * Build a Github repo that archives all the quant experience in one easy to read, easy to share location
  * One programming language only: Python
  * Data science only. Other fields like finance requires formal certification and you never worked in the CFO organization. Project Management experience is almost nil
  * 

Areas of Expertise:
1) Data
  * Transform large data sets of data into knowledge in order to recommend actions
  * Business use case was trading strategies (GWF, Helms, C1, BCR, P&L, PDR)
  * Tools are SQL, Python Sci-kit
  * Possible to use Apache Spark, Mapreduce, and Hadoop?

2) Optimization
  * Formulate complex problem mathematically to solve for an optimal solution
  * Business use cases were temp gen assignment, energy storage, fossil dispatch, demand response
  * Tools are Xpress, python, SQL

3) Machine Learning
  * This is not yet developed, there is no ML project
  * Business use cases were STDF, MTLF, PRT, Fuel Burn
  * Potential business case is geo-spatial forecasting such as EV adoptation forecast
  * Tools are Python, Sci-kit Learn, Tensorflow, PyTorch

Descriptions of Business Cases
1) Data
  a) C1: Issue is that the contract consistently losing money. Hypthesis is that our offer drives down the price. Goal is to investigate.
  b) BCR/P&L: Issue is to perform calculation on time series with complex logic (if-case, assignment, 10+ tables)  using the fastest method possible: SQL 
  c) PDR: Issue is to find utilization rate based on prices by backtesting several years of data
  
2) Optimization
  a) Energy Storage: mixed-integer problem, maximizing profit subject to hundreds of operational constraints including mode changes
  b) Fossil Dispatch: mixed-integer problem, minimizing cost subject to hundreds of operational constraints including commitment
  c) Demand Response: mixed-integer problem, maximizing profit, opportunity cost (shadow price) calculation
  d) Temp Gen Assignment: mixed-integer assignment problem, maximizing customers served, subject to geo-spatial constraints

3) Machine Learning
  a) 
