# SampleTodoApp
Backend and frontend (iOS) for a very simple todo application

## How to set up

- Right now the application looks for the backend at `localhost/3030`
- To run the rust app and serve the backend at `localhost/3030`:
  - Set your current directory to the `backend` directory
  - Use `cargo run --release` to run in release mode


## Unit tests

The iOS client has a test suite that covers about 76% of the lines in the whole project. There are snapshot tests and regular unit tests.

Make sure you have `FB_REFERENCE_IMAGE_DIR=$(SOURCE_ROOT)/$(PROJECT_NAME)Tests/ReferenceImages` an an enviroment argument for the tests target for snapshot tests to pass.
