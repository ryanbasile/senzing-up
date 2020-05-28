# senzing-up

## Overview

[senzing-up.sh](senzing-up.sh) launches the Senzing Entity Search web application using a local SQLite database.

### Contents

1. [Expectations](#expectations)
1. [Demonstrate](#demonstrate)
    1. [Prerequisite software](#prerequisite-software)
    1. [Download](#download)
    1. [Start web application](#start-web-application)
    1. [View web application](#view-web-application)

## Expectations

- **Space:** The demonstration requires 6 GB free disk space.
- **Time:** Budget 30 minutes to get the demonstration up-and-running, depending on CPU and network speeds.

## Demonstrate

### Prerequisite software

The following software programs need to be installed:

1. [docker](https://github.com/Senzing/knowledge-base/blob/master/HOWTO/install-docker.md)
1. [curl](https://github.com/Senzing/knowledge-base/blob/master/HOWTO/install-curl.md)
1. [python3](https://github.com/Senzing/knowledge-base/blob/master/HOWTO/install-python-3.md)

### Download

1. Get a local copy of
   [senzing-up.sh](https://raw.githubusercontent.com/Senzing/senzing-up/master/senzing-up.sh)
   and make executable.
   Example:

    ```console
    curl -X GET \
      --output ~/senzing-up.sh \
      https://raw.githubusercontent.com/Senzing/senzing-up/master/senzing-up.sh

    chmod +x ~/senzing-up.sh
    ```

### Start web application

1. Run the command.

    1. Command format: **`senzing-up.sh <project-directory>`**

   In this example, the Senzing instance will be put into the `~/my-first-senzing-test` project directory.
   Example:

   ```console
   sudo ~/senzing-up.sh ~/my-first-senzing-test
   ```

### View web application

1. Visit [http://localhost:8251](http://localhost:8251).

1. For a tour of sample data, visit
   [Synthetic Truth Sets](https://senzing.zendesk.com/hc/en-us/articles/360047940434-Synthetic-Truth-Sets).
