<!-- Start SDK Example Usage [usage] -->
```python
import sdk
from sdk.models import shared

s = sdk.SDK()

req = shared.Pet(
    id=596804,
    name='<value>',
)

res = s.pets.create_pets(req)

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->