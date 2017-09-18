### Useful Commands
* Validate cloudformation file.
    ```
    npm run validate-cloudformation
    ```
* Update cloudformation stack.
    ```
    aws cloudformation update-stack --stack-name WeatherCorrelationApp --template-body file://./application-stack.yml
    ```
