This is a site hosted to display **CCD: CUDA Code smell catalog** in support of CCD tool.

**CCD: CUDA Code-smell Detector**

A tool to detect code smells in CUDA programming language. To try out our CCD tool, please download recent version from [CCD: CUDA Code-Smell Detector GitHub](https://github.com/Abhijeetkumar96/CUDACodeSmell)

**About CUDA:**

CUDA is used in parallel programming, to facilitate faster and complex codes which need GPU(Graphical User Interface) assitance along with CPU processing. The first release of NVidia CUDA was in 2007, and from then there has been tremendous applications built using this interface.

**Website Information:**

_index.html_ is the main page of the website. Left half of the screen explains about the tool and development ifnormation. Right half of the screen displays the **CCD catelog**. Each code smell description in the catelog can be accessed by clickig on respectiev links. 


Each code smell has a respective _.html file_ which serves as the code for the respective webpage. **Description, Identification mechanism and refactorisation suggestion** is provided for each smell in respective webpage. 


**Why Code-smell needs to be identified?**
1) "Unfreed memory", 2)"active streams" will cause memory leakage. 
3) "Missing validation" might give wrong results in the end as we are assuming that the API call is successful without validating it.
4) Multiple memory exchanges between CPU and GPU would reduce the performance, so instead use "Unified Memory". 
5) Thread Divergance and 6)Memory Coalescing are smells which affects performance of the code and can be detected using code evaluation.

Liked the tool? Any suggestions for improvements? Happy to receive ideas and suggestions.

**Happy CUDA coding !!** _Use our tool to detect code smells so you can refactor for effective CUDA coding._
</br>
</br>


Developed by: 

* [Abhijit Kumar Sahu](mailto:cs22s501@iittp.ac.in), Research Scholar, Parallel Computing, Computer Science, IIT Tirupati, India.  

* [Jahnavi Kumar](mailto:cs22s503@iittp.ac.in), Research Scholar, Software Engineering, Computer Science, IIT Tirupati, India.  

Guidance of:

* [Dr. Sridhar Chimmalakonda](mailto:ch@iittp.ac.i), Professor, Software Engineering, Computer Science, IIT Tirupati, India. 

* [Dr. G. Ramakrishna](mailto:rama@iittp.ac.in), Professor, Parallel Computing, Computer Science, IIT Tirupati, India.  

* [Eashaan Rao](mailto:cs21d002@iittp.ac.in), Research Scholar-PhD, Software Engineering, Computer Science, IIT Tirupati, India.   
