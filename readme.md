# platformr-test

A simple repository designed to test CI/CD systems.

 * Build with: `docker build $BUILD_OPTS -t platformr/test .`
 * Run with: `docker run --name platformr_test -d -p 8080:80 platformr/test`
 * Visit `http://localhost:8080` to verify that this is platformr/test calling!
