## Multiclient chat
This is a cli chat application written completely in Golang. Participants have common functionality, communication with each other via the network, an ability to create channels for sharing messages and files. The application supports multiple backends for storing the data (redis, dynamodb and in-memory for local development). Mode detailed explanation is provided in the architecture [architecture](architecture.md) document. Keep in mind that the project is still in development and requires more work in order to be considered as done.