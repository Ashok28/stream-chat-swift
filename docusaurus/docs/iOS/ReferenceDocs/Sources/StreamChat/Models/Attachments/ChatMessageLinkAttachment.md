---
id: chatmessagelinkattachment 
title: ChatMessageLinkAttachment
slug: /ReferenceDocs/Sources/StreamChat/Models/Attachments/chatmessagelinkattachment
---

A type alias for attachment with `LinkAttachmentPayload` payload type.

``` swift
public typealias ChatMessageLinkAttachment = _ChatMessageAttachment<LinkAttachmentPayload>
```

The `ChatMessageLinkAttachment` attachment will be added to the message automatically
if the message is sent with the text containing the URL.