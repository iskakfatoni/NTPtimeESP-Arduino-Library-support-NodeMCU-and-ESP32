# NTPtimeESP support NodeMCU and ESP32

This library returns the queries the NTP time service and returns the actual time in a structure:

```
struct strDateTime
{

  byte hour;
  byte minute;
  byte second;
  int year;
  byte month;
  byte day;
  byte dayofWeek;
  boolean valid;
  
};
```

The time can be automatically adjusted by time zone and European summer time. It runs on ESP8266 and ESP32 and needs an internet connection.
