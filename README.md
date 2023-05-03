# Jahnavi-K_CCD.github.io
Site hosted to show CCD: CUDA Code smell catalog

index.html is the main page of the website. Left half of the screen explains about the tool and developemnt ifnormation. Right half of the screen displays the CCD catelog. Each code smell description in the catelog can be accessed by clickig on respectiev links. 

Each code smell has a respective .html file which serves as the code for the respective webpage. Description, Identification mechanism and refactorisation suggestion is provided for each smell in respective webpage. 

Happy CUDA coding !! Use our tool to detect code smells so you can refactor for effective CUDA coding. 

All the 6 code smells code have been added.
Why they need to be identified:
1) "Unfreed memory", 2)"active streams" will cause memory leakage. 
3) "Missing validation" might give wrong results in the end as we are assuming that the API call is successful without validating it.
4) Multiple memory exchanges between CPU and GPU would reduce the performance, so instead use "Unified Memory". 
5) Thread Divergance and 6)Memory Coalescing are smells which affects performance of the code and can be detected using code evaluation.
