# kotlin-coroutine-ktor-mongodb

Kotlin's simplicity, Java interoperability, and Ktor's user-friendly framework combined with MongoDB Atlas' flexible cloud database provide a robust stack for modern software development.
Together, we'll demonstrate and set up the Ktor project, implement CRUD operations, define API route endpoints, and run the application. By the end, you'll have a solid understanding of Kotlin's capabilities in API development and the tools needed to succeed in modern software development.


## Built with

- [Kotlin - Programming Language](https://kotlinlang.org/docs/coroutines-overview.html)
- [Ktor - Asynchronous framework](https://ktor.io/)
- [Koin - Dependency Injection framework](https://insert-koin.io/)
- [MongoDB Kotlin Driver — Kotlin Coroutine](https://www.mongodb.com/docs/drivers/kotlin/coroutine/current/)

## Getting Started

Follow the steps below to get the Fitness Tracker App up and running on your local machine.

### Running

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/fitness-tracker-app.git
    cd fitness-tracker
    ```

2. Start the application using Docker Compose:

    ```bash
    docker-compose up -d
    ```

3. Compile the application jar using Gradle:

   ```bash
   ./gradlew shadowJar
     ```

4. Run the application local or in cluster
    
   ```bash
   java -jar -DMONGO_URI="mongodb://localhost:27017/fitness/" -DMONGO_DATABASE="discover" build/libs
   ```

### Swagger UI

To explore the API documentation and interact with the Fitness Tracker App, you can use Swagger. Open your web browser and navigate to:

 http://localhost:8080/openapi/
 
 

![OpenAPI](https://i.ibb.co/kQzksr4/openapi.png)


