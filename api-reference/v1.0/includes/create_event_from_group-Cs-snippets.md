---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var @event = new Event
{
	OriginalStartTimeZone = "originalStartTimeZone-value",
	OriginalEndTimeZone = "originalEndTimeZone-value",
	ResponseStatus = new ResponseStatus
	{
		Response = ResponseType.None,
		Time = "datetime-value"
	},
	ICalUId = "iCalUId-value",
	ReminderMinutesBeforeStart = 99,
	IsReminderOn = true
};

await graphClient.Groups["{id}"].Events
	.Request()
	.AddAsync(@event);

```