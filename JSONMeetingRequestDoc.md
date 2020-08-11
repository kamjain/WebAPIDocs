JSON Meeting Request:
```
{
	"meeting" : {
		"time": "2020-10-05 12:00",
		"duration": 60,
		"description": "Technical Writer Interview",
		"location": "http://zoom.us",
		"reminder": 15,
		"invitees": ["recruiter@company.com", "applicant@gmail.com"]
	}
}
```


This table describes the elements that make up a JSON meeting request.

|Element|Description|Type|Required|Notes|
|---|---|---|---|---|
|meeting|Top Level|meeting data object|Required||
|&nbsp; &nbsp; time| Time of meeting| string| Required| Format: YYYY-MM-DD HH:MM Timezone:GMT|
|&nbsp; &nbsp; duration| Length of the meeting| number|Required|in Minutes|
|&nbsp; &nbsp; description|Purpose of the meeting|string|Required||
|&nbsp; &nbsp; location|Place where the meeting is to be held|string|Optional|Default is an empty `string`|
|&nbsp; &nbsp; reminder| Minutes before the meeting to send meeting alert|number|Optional|Default is 10 minutes|
|&nbsp; &nbsp; invitees|List of email address of people to be invited to the meeting| Array of strings|Optional|The strings must be valid email addresses. Default is an empty `array`|

