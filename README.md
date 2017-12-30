GRPC on Java:

Build Server:
$ ./gradlew installDist

Run Server:
$ ./build/install/examples/bin/hello-world-server

Run Client:
$ ./build/install/examples/bin/hello-world-client

Server and Client Java files are here:
\src\main\java\io\grpc\examples\helloworld

Proto File is here:
\src\main\proto

Note: These both should be running on different windows of the CLI
