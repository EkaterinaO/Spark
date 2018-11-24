# Spark

How to setup Spark on Azure Ubuntu server:

1. I launched Azure Ubuntu server;

2. Installed spark with a help of this https://medium.com/@josemarcialportilla/installing-scala-and-spark-on-ubuntu-5665ee4b62b1 tutorial ;

3. I installed anaconda, using this https://www.digitalocean.com/community/tutorials/how-to-install-the-anaconda-python-distribution-on-ubuntu-16-04 ;
Installed pyspark with command: conda install pyspark ;

4. Used this tutorial to change some settings https://blog.sicara.com/get-started-pyspark-jupyter-guide-tutorial-ae2fe84f594f, however it is essential to do source ~/.bashrc after all;

5. After all of that I set the password for my jupyter notebook: jupyter  notebook password ;
Changed restrictions for some ports for my azure server ( opened 80) ;
Opened my notebook for all ips: jupyter notebook –ip = ‘*’ –port = 80;
It worked from my browser on my computer.
 
After all of these steps it finally started to work. 
I found that it is better to install pyspark with conda, 

and to check the directory where spark is and also to check java version not to be higher than 8.
 
