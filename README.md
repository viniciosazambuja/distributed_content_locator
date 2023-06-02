## Add a settings file into root
```json
{
    "id": 1,
    "port": 8001,
    "database": {
        "host": "localhost",
        "port": 27017,
        "name": "node1"
    },
    "neighbors": [
        {
            "id": 2,
            "port": 8002
        }
    ]
}
```