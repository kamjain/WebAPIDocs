Simple XML request to record a TV show:
```
<recordTV>  
	<date>2020-08-11</date>  
	<time format="24">18:00</time>  
	<duration>1.0</duration>  
	<channel>200</channel>  
</recordTV>
```
This table represents the API request to record a TV show.
|Element|Description|Type|Required|Notes|
|---|---|---|---|---|
|recordTV|Top Level|TV program data |Required||
|&nbsp; &nbsp; date|Date on which the TV show needs to be recorded|String|Optional|Format: YYYY-MM-DD|Default value is today's date|
|&nbsp; &nbsp; time|Time at which the show is to be recorded|number|Required|Attributes: `format` can be 24 or 12 depending on the 24 hour or 12 hour formats. Format is HH:MM, with *am* or *pm* afterwards for 12 hour format.|
|&nbsp; &nbsp; duration|Length of the program|number|Required|in hours|
|&nbsp; &nbsp; channel|Channel number where the program is aired|number|Required||
