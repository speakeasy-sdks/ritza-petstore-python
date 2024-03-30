<!-- Start SDK Example Usage [usage] -->
```python
import sdk
from sdk.models import components

s = sdk.SDK()

req = components.Pet(
    id=596804,
    name='<value>',
)

res = s.pets.create_pets(req)

if res is not None:
    # handle response
    pass

```
<!-- End SDK Example Usage [usage] -->