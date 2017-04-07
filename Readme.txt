5. README
README 

Run environment:
1)	Eclipse MARS .2 EE IDE (recommended)
2)	Dataset.txt
3)	Java APIs and Libraries, including:
JRE system Library [jdk1.8.0_31] (recommended), jsoup-1.8.1.jar, terrier-3.5-core.jar, weka-3.7.3.jar, commons-io-2.4.jar 

Please follow the following steps to run the program:

1.	Create the following folders in the package directory (4020G6A3): chunk, data_index
2.	Import your package into Eclipse by clicking File at the left top corner, and select import from the menu, click import, select existing projects into workspace, and next, then select 4020G6A3.zip at select archive file and select the project contain within. Click finish to complete the import process.
3.	Name and store dataset as “Dataset.txt” into 4020G6A3 in the JAVA EE workspace
4.	Right click on your project, and select Properties, click on Java Build Path, go to the libraries tab, add jars by referencing to our libraries included in the lib folder in our package, click apply and ok.
Make sure all below .jar is in the library. If not, import them manually. 
JRE system Library [jdk1.8.0_31] (recommended), jsoup-1.8.1.jar, terrier-3.5-core.jar, weka-3.7.3.jar, commons-io-2.4.jar 
5.	If your computer has low java heap memory space, add “-Xmx8G” to extend maximum memory by selecting the little arrow next to the run button -> click on run configuration -> click on the argument tab -> copy and paste at the argument at the VM argument session -> click apply -> if you are already at the main class click run, otherwise click ok
6.	Run “Viewmain.java” without any server configuration as a JAVA Applet
7.	Result file will be outputted in the pop-out applet interface. The output will be stored in 10 .txt file. The applet is for the ease of use and view.
