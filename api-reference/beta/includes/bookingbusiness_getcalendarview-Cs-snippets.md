---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var calendarView = await graphClient.BookingBusinesses["Contosolunchdelivery@M365B489948.onmicrosoft.com"].CalendarView
	.Request()
	.GetAsync();

```