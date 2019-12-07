# CryptoTranscript 


CryptoTranscript deals with Blockchain based digital transcripts to the University or School or Employer. Hence, transcripts values will never get tampered and data will never get lost as well. 


## Prerequisits

[Java Development Kit JDK8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)


## Running

To run this application, follow the below methods:

1. Traverse to project directory in terminal / command prompt 
2. Once you are in the project directory, run the command `gradlew run`
3. The warnings and 80% [Executing] can safely be ignored
4. Open the CryptoTranscript.html which is in the parent directory.


## API Information

Once the application is up and running, the API instances are available at http://localhost:4444 and is accessible through postman.

### endpoints

* `GET /getTranscriptBlocks` for listing all existing blocks in the chain
* `POST /transcriptBlocks/mine` for mining a block
* `POST /tamperBlocks` for tampering an existing block and after the chain is created
* `POST /transcriptBlocks/fork` - to simulate fork
* `GET /transcriptBlocks/longestchain` - to find the longest chain


## References

* [Mango Research](https://www.mangoresearch.co)
* [BlockCerts](https://www.blockcerts.org/guide)

#### This project uses some open source libraries:

* [Apache Commons Codec](https://github.com/apache/commons-codec)
* [Javalin](https://javalin.io/)
* [Jackson Module Kotlin](https://github.com/FasterXML/jackson-module-kotlin)
* [Gradle Build Tool](https://gradle.org/)
