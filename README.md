# origin
### SlackConfig

 ```
 SlackConfig{
  SlackUrl:           string ← (required) Url for sending Slack notification
 	SlackVerticalName:   string ← (required) Vertical for which alert should be send
  }
 ```

 #### Example

 ```go
 SlackConfig := config.SlackConfig{
   SlackUrl:           "https://hooks.slack.com/services/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"
   SlackVerticalName:   "Hotel"
 }
 ```
