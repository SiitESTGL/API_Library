# API_Library
This is a library developed to interface with the API in our SIIT project.

## Usage Example
To use this library, first import it into your application like so:
```python
import SIIT_API
```

Afterwards, initiate the API_client class using your key, this will allow you to execute any queries with the given key without having to re-insert it. To do this, follow the example step below:
```python
api = SIIT_API.API_client(key="[Insert your key here]")
```

With your API_client class initialized, you're now ready to execute the several functions included in the library. These simplify the creation of the HTTP requests required to interact with our API so it's not necessary to write everything manually. Here's some examples of their usage:
```python
api.distance_coord(lat=41.0, lon=-7.0, dist=5)

api.time_id(poi_id=71, cat=3, conc=10, time=2800)
```
