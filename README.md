CDK REST API template
---

An example of project that uses Chemistry Development Kit (CDK) and provides a REST API. To start it in IDE, run [Starter](./src/main/java/cdkapi/Starter.java) and open your browser at http://localhost:8080/api/mw/CCC

Project structure:

- [Starter](./src/main/java/cdkapi/Starter.java), you can start directly from the IDE
- [CdkApi](./src/main/java/cdkapi/CdkApi.java) is where the actual API is
- [web-app-context.xml](./src/main/resources/web-app-context.xml) is the main app context where the beans can be defined
- [CdkApiTest](./src/test/java/cdkapi/CdkApiTest.java) to test your API