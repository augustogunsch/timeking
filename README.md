Simple script for limiting access time to certain applications.

## Examples
- Only allow usage of newsboat from 8AM to 9AM:
```
timeking '08:00-09:00' && newsboat
```
- Allow newsboat from 8AM to 9AM and from 11AM to 12AM:
```
timeking '08:00-09:00&11:00-12:00' && newsboat
```
