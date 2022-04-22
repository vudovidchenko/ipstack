## IPIFY
Module For Easy Streamlined Access Of The IpStack GeoIP Service

### Examples

#### IPv4
```javascript
const ipstack = require('ipstack');
ipstack.setAccessKey("EXAMPLE_KEY")

(async () => {
    try {
        let geoData = await ipstack.getGeoData("EXAMPLE_ADDRESS")
        console.log(geoData)
    } catch (error) {
        console.log(error)
    }
})();
````