# gns3api - Simple python module to access the GNS3 API

This module provides an easy access the GNS3 API, see http://api.gns3.net/en/2.0.

Example:
- create an API object  
  api = gns3api.api()
- access the API  
  (status, data) = api.request('POST', '/v2/version', {"version": "0.1"})

Restrictions:
- Notifications are not supported
