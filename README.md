# python-web-fastapi-api-sqlserver-simple

## Description
Simple web app that serves api
for a fastapi project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
  - fastapi
  - uvicorn
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- mssql

## Docker stack
- python:latest
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
- [Availble at](http://localhost/dog)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
