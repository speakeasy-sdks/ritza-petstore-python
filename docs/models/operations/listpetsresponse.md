# ListPetsResponse


## Fields

| Field                                                              | Type                                                               | Required                                                           | Description                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| `headers`                                                          | Dict[str, List[*str*]]                                             | :heavy_check_mark:                                                 | N/A                                                                |
| `http_meta`                                                        | [components.HTTPMetadata](../../models/components/httpmetadata.md) | :heavy_check_mark:                                                 | N/A                                                                |
| `error`                                                            | [Optional[components.Error]](../../models/components/error.md)     | :heavy_minus_sign:                                                 | unexpected error                                                   |
| `pets`                                                             | List[[components.Pet](../../models/components/pet.md)]             | :heavy_minus_sign:                                                 | A paged array of pets                                              |