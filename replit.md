# Imported Java/Maven project

## Run on Replit

This project is a Java console application. Its entry point is
`src/main/java/Main.java`, which prints a greeting and then exits.

- Run the configured `Start application` workflow to execute it.
- Press **Run** to see `Hello world JPWP2!` in the Console. The workflow then
  finishes normally; this program does not serve a web page.
- Build and test manually with `mvn test`.
- Run the entry point directly with `javac -d . src/main/java/Main.java && java -cp . Main`.

The Java toolchain is provided by the `java-graalvm22.3` Replit module.
No secrets or external services are needed.

## Verification

- The run workflow compiled and printed the expected greeting.
- `mvn test` completed successfully. There are currently no active tests.
