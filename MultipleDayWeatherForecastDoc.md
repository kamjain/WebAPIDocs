---


---

<p>The table below represents the weather forecast over multiple days, for a given location.</p>

<table>
<thead>
<tr>
<th>Element</th>
<th>Description</th>
<th>Type</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
<td>longitude</td>
<td>Longitude of the location</td>
<td>number</td>
<td></td>
</tr>
<tr>
<td>latitude</td>
<td>Latitude of the location</td>
<td>number</td>
<td></td>
</tr>
<tr>
<td>forecast</td>
<td>Weather forecast at this location</td>
<td>Array of forecast objects</td>
<td>Each element of the array represents the weather forecast for a single day</td>
</tr>
<tr>
<td>&nbsp; &nbsp; date</td>
<td>Date of the forecast</td>
<td>String</td>
<td>Format: YYYY-MM-DD</td>
</tr>
<tr>
<td>&nbsp; &nbsp; description</td>
<td>Weather condition of the day</td>
<td>String</td>
<td>Valid values: “sunny”, “overcast”, “partly cloudy”, “raining”, “snowing”</td>
</tr>
<tr>
<td>&nbsp; &nbsp; maxTemp</td>
<td>Maximum temperature of the day</td>
<td>number</td>
<td>Unit is degrees celsius</td>
</tr>
<tr>
<td>&nbsp; &nbsp; minTemp</td>
<td>Minimum temperature of the day</td>
<td>number</td>
<td>Unit is degrees celsius</td>
</tr>
<tr>
<td>&nbsp; &nbsp; windSpeed</td>
<td>Speed of the Wind</td>
<td>number</td>
<td>Unit is kilometers per hour</td>
</tr>
<tr>
<td>&nbsp; &nbsp; danger</td>
<td>Danger of Fire</td>
<td>Boolean</td>
<td><code>true</code> if the weather conditions are dangerous; <code>false</code> otherwise</td>
</tr>
</tbody>
</table>
