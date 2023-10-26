# Ip checker web

## Project structure
```
ip_checker_web
├── src
│   ├── check_ip
│   │   ├── router.py # core of module with all the endpoints
│   │   ├── schemas.py  # pydantic models
│   │   ├── config.py  # local configs
│   │   ├── exceptions.py # module exceptions
│   │   ├── service.py # specific business logic
│   │   └── utils.py # non-business logic functions
│   ├── config.py  # global configs
│   ├── models.py  # global models
│   ├── exceptions.py  # global exceptions
│   └── main.py
├── tests/
│   └── check_ip
├── templates/
│   └── index.html
├── .gitignore
├── pyproject.toml
└── readme.md
```