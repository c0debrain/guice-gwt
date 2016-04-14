Sample application which will demonstrate Guice and GWT integration. This sample will also demonstrate use of multiple Persistent unit management with Guice. Its complete tested sample. Client (UI) side implementation is not that perfect, as main intention was to demonstrate Guice and GWT integration. Also this sample don't demonstrate any GIN DI usage.

One can check out the code and test the sample. You need to follow below steps.

1. You will require mysql and maven.
2. Check out the code.
3. Run db script placed inside db folder.
4. Change db credentials inside persistence.xml and build the application using maven.

It has few required test cases, which will get fired while making the build. All of them should run successfully unless there is no other issue related to db permissions.

Once build is ready you can deploy the application in servlet container and test the application.

You can even try importing this project inside eclipse. If you are not aware how to do it [refer](http://blog.pandurangpatil.com/2011/08/create-maven-gwt-project-and-setup.html)