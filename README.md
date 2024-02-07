# Movieist Spring Boot Server
This server is implemented using Java with the Spring Boot framework, following the tutorial on freeCodeCamp's YouTube channel, available at https://youtu.be/5PdEmeopJVQ. The implementation includes the integration of the API documented in [movies.json](https://github.com/fhsinchy/movieist/blob/master/_data/movies.json).

## Development Environment
* Code Formatting: Prettier functionality similar to VSCode is used. Originally configured with google-java-format-setting, but later switched to using **Lombok**. Note that the shortcut key for formatting is now **Ctrl+Alt+L**.

* Database: **MongoDB** is utilized for data storage. While entering data proved surprisingly straightforward, connecting Spring Boot to the database posed challenges. Initially attempted using application.properties for configuration, the connection issues persisted. The solution was found in using application.yml for configuration, as **YAML** files provide a more seamless integration.

## Note
If you encounter issues connecting to the database or have questions about the setup, feel free to refer to the provided information or seek assistance.

Feel free to make any adjustments or let me know if there's anything specific you'd like to add or modify!