# epas-docker-dev

This is a docker-compose project that provides a postgres database and icd-11 api instance for development purposes.
This is specifically used in our Tryton ICD-11 project.

Take a look at https://github.com/alteroo/trytond_health_icd11

## Usage

- Make sure you have docker and docker-compose installed.
- Take a look at database.env and icd11.env and edit to set passwords etc.. (it's okay to keep the defaults for development)

# Launch
```
mkdir -p data
docker-compose up -d
```

