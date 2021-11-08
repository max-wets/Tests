# Tests

Clone the repository and then download the packages
```bash
npm install
```

In the root folder, start nodemon
```bash
nodemon index
```

Now you can edit the 'changesList.json' file to add your own instructions
```json
{
    "page1[0].data.value": 400,
    "page1.initialSettings.color.data.value": "200",
    "page1.initialSettings.coordinates": [24,30],
    "page1.available-filters.name-filter": { "column": "lastName", "sort": "desc" },
    "page1.available-filters.name-filter.sort": "asc",
    "page1.initialSettings.coordinates[0]": { "value": "Wow JSON injected!!" },
    "page1.available-filters.name-filter.column": { "first": {"a": 2, "b": 3}, "second": "lastName" }
}
```
