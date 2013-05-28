aa-as
=====

AndroidAnnotations with Android Studio

This is reference how to get AndroidAnnotations work with Android Studio. 
As IDE is in very early stages there are thing we have to do manually:
1. modify build.gradle inside module<br>
2. add dependency on androidannotations-api jar in module settings<br>
   optionally add generated path to sources if you want to write tests<br>
4. run test tasks from command line:<br>

   > gradle installDebug<br>
   > gradle connectedInstrumentTest<br>
   
   run build at least once to make Android Studio pickup generated classes
   
   
   
