---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const user = {
  '@odata.id': 'https://graph.microsoft.com/v1.0/users/{userId}'
};

await client.api('/print/shares/{printerShareId}/allowedUsers/$ref')
	.post(user);

```