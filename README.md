aa-as
=====

AndroidAnnotations with Android Studio

This is reference how to get AndroidAnnotations work with Android Studio. 
As IDE is in very early stages there are thing we have to do manually:
1. modify build.gradle inside module
2. add dependency on androidannotations-api jar in module settings
   optionally add generated path to sources if you want to write tests
4. run test tasks from command line:

   > gradle installDebug
   > gradle connectedInstrumentTest
   
   run build at least once to make Android Studio pickup generated classes
   
   
   
