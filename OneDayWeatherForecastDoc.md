This table describes the elements in a JSON file for a single day's weather forecast.

|Element|Description|Type|Notes|
|---|---|---|---|
|date| Date of the forecast| String|Format: YYYY-MM-DD|
|description|Weather condition of the day|String|Valid values: "sunny", "overcast", "partly cloudy", "raining", "snowing"|
|maxTemp|Maximum temperature of the day|number|Unit is degrees celsius|
|minTemp|Minimum temperature of the day|number|Unit is degrees celsius|
|windSpeed|Speed of the Wind|number|Unit is kilometers per hour|
|danger|Danger of Fire|Boolean|`true` if the weather conditions are dangerous; `false` otherwise|
