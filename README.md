```
inputs:
  token:
    description: "The slack bot token"
    required: true
  channel:
    description: "Send the message to this channel"
    required: true
  ts:
    description: "If passed, update matching message instead of posting a new one"
    required: false
  threadTs:
    description: "If passed, add message to thread to the message referenced"
    required: false
  text:
    description: "The message's base text"
    required: false
  blocks:
    description: "Optional array of blocks (JSON.stringify'ed)"
    required: false
  attachments:
    description: "Optional array of attachements (JSON.stringify'ed)"
    required: false
  appendText:
    description: "Append given text to original message (update only)"
    required: false
  appendBlocks:
    description: "Append given blocks to original message (update only)"
    required: false
  appendAttachments:
    description: "Append given attachments to original message (update only)"
    required: false

outputs:
  ts:
    description: "Updated or created message for later reference"
```
