# Structure of Java Programs

* All Java source files MUST end with a _.java_ extension
* A source file should generally contain at most one top-level public class definition.
* If public class is present, the class name should match the unextended filename.
* There are three top-level elements that may appear in a file.  If they are present, then they must appear in the following:
  1. _Package_ declaration
  2. _Import_ statements
  3. _Class_ definitions

* The _main()_ method is the normal entry point for a Java application
* The _main()_ method is _public_ by convention.  However, it is a requirement that it be _static_ so that it may be executed without the necessity of constructing an instance of the corresponding class.
* The arss arraycontains any arguements that the user might have entered on the command line.