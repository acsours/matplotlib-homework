# matplotlib-homework
This script reads two separate csv files containing data from a study examining how several different drug regimens treat tumor volume in mice. 

  * According to the final mean tumor volume, mice treated with Ramicane had the lowest final mean tumor volume (40.216745 mm3), 
  followed by mice treated with Capomulin (40.675741 mm3).

  * Infubinol and Ceftamin had a greater final average tumor volumes than Capomulin and Ramicane. While Infubinol had one potential outlier with an average tumor     volume of 36.321346 mm3, the final tumor volumes tended to be greater than those of the two leading drugs. 
  
       ![final_tumor_boxplot.png](final_tumor_boxplot.png?raw=true "Title")

  * For mouse s=185, treated with Capomulin, as time progressed tumor volume decreased at a nearly linear rate. 

      ![mouse_progression.png](mouse_progression.png?raw=true "Title")

  * According to the scatter plot, regression line, and correlation coefficient comparing average tumor volume by weight of mouse treated with Capomulin,
  There is a strong correlation beween mouse weight and average tumor volume. As mouse weight increases, tumor volume increases. This makes sense, 
  as a larger mouse would logically be able to have a larger tumor. It may be more beneficial to analysis to compare weight with final tumor volume to 
  analyze potential benefits of treatment. 
      ![scatter_plot.png](scatter_plot.png?raw=true "Title")
