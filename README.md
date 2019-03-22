# Customized Jenkins X server with JIRA integration plugins
Add JIRA plugins to allow triggering PROD promotions from JIRA deployment tickets through JIRA webhooks.

## Robbies own Jenkins x server instance
To configure this JIRA enabled Jenkins X server custom image you can specify your own Jenkins image via a myvalues.yaml file:

```
jenkins:
  Master:
    Image: "agilesolutions/jira-enabled-jenkinsx"
    ImageTag: "1.0.0"
```

