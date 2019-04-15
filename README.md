# Postman collection to test wodss FS19 API
## Requirements
The test suite runs with a preexisting `ADMINISTRATOR 1` account and expects an otherwise empty database.

## Run tests
1. Change variabels in `wodss_dev.postman_environment.json`
2. Run tests with newman or postman
3. ???
4. PROFIT

## Example

```shell
newman run wodss_API_Tests_StringID.postman_collection.json -e wodss_dev.postman_environment.json
```