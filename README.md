

Before you should create two directories named "json" , "image" , "compare" , "price"

How to use:

First, you can generate all companies' json file , image and relative file between all of them in folder "compare" with this:

ruby toc_project.rb "your_url"

If you want to merge graphs into one image, you can input the json file which you want to compare , but at most 7 arguments

ruby generate_graph.rb arg1 arg2 arg3 .....

ex.

ruby generate_graph.rb ./json/1_台股.json ./json/16_群創.json

and you will get the combination of those companies in output.png

If you want to zoom in one of the company between two dates, you can input:

ruby graph_month.rb json_file date1 date2

ex.

ruby graph_month.rb ./json/1_台股.json 9/6 10/6

