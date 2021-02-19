```
- pipe: atlassian/firebase-deploy:0.8.0
  variables:
    KEY_FILE: '<string>'
    FIREBASE_TOKEN: '<string>'
    # PROJECT_ID: '<string>' # Optional.
    # MESSAGE: '<string>' # Optional.
    # EXTRA_ARGS: '<string>' # Optional.
    # MULTI_SITES_CONFIG: '<json>' # Optional
    # DEBUG: '<boolean>' # Optional.
```


```
- pipe: atlassian/google-app-engine-deploy:0.7.4
  variables:
    KEY_FILE: '<string>'
    PROJECT: '<string>'
    # DEPLOYABLES: '<string>' # Optional
    # VERSION: '<string>' # Optional.
    # BUCKET: '<string>' # Optional.
    # IMAGE: '<string>' # Optional.
    # PROMOTE: '<boolean>' # Optional
    # STOP_PREVIOUS_VERSION: '<boolean>' # Optional.
    # EXTRA_ARGS: '<string>' # Optional.
    # DEBUG: '<boolean>' # Optional.
    # CLOUD_BUILD_TIMEOUT: '<integer>' # Optional
```

```
- pipe: atlassian/heroku-deploy:1.2.1
  variables:
    HEROKU_API_KEY: '<string>'
    HEROKU_APP_NAME: '<string>'
    ZIP_FILE: '<string>'
    # WAIT: '<boolean>' # Optional.
    # DEBUG: '<boolean>' # Optional
```

```
- pipe: atlassian/rsync-deploy:0.4.4
  variables:
    USER: '<string>'
    SERVER: '<string>'
    REMOTE_PATH: '<string>'
    LOCAL_PATH: '<string>'
    # SSH_KEY: '<string>' # Optional.
    # SSH_PORT: '<string>' # Optional.
    # EXTRA_ARGS: '<string>' # Optional.
    # DEBUG: '<boolean>' # Optional.
    # DELETE_FLAG: '<boolean>' # Optional.
```


```
- pipe: atlassian/scp-deploy:1.0.0
  variables:
    USER: '<string>'
    SERVER: '<string>'
    REMOTE_PATH: '<string>'
    LOCAL_PATH: '<string>'
    # SSH_KEY: '<string>' # Optional.
    # EXTRA_ARGS: '<string>' # Optional.
    # DEBUG: '<boolean>' # Optional.
```
