# weather-forecast-api
This Application contains API as below:
API 1: Get the Weather forecast summary of Any city using API (RapidApiGetForecastSummaryByLocationName)
API 2: Get hourly Weather forecast details of Any city using API (RapidApiGetHourlyForecastByLocationName)
API Document: https://rapidapi.com/wettercom-wettercom-default/api/forecast9 (RapidApiGetForecastSummaryByLocationName & RapidApiGetHourlyForecastByLocationName)

Techstack:
This Application is using below versions.
Java 17
SpringBoot 3.2.5
Maven 4

Below maven dependencies used in the project:
'Spring Web','Spring Security','Spring Boot DevTools'

API Details:
1. getForecastSummary
URL: http://localhost:8080/api/weather/summary/Berlin
O/P: ![WeatherForecastOutput](https://github.com/Pratik22-Patil/weather-forecast-api/assets/114714806/11c42f91-98e8-4fee-9980-bb61be212fbe)

2.getHourlyForecast
URL: http://localhost:8080/api/weather/hourly/Berlin
O/P: ![image](https://github.com/Pratik22-Patil/weather-forecast-api/assets/114714806/17a4afe3-20c4-45b2-838e-96de37db273e)

Json O/P  for 1st API attached in repo as well for reference.

Note: API require subscription for rapidapi.com. As I used free subscription, It only have access for 1st API. I'm getting error for 2nd API as "401 Unauthorized: \"{\"message\":\"This endpoint is disabled for your subscription"
If subscription is available, it will work.

