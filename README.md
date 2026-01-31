# Grafana server

Observability platform for log collection and analysis

## Start docker

    ./start.sh

## Stop docker

    ./stop.sh

## UI

    http://localhost:3000

## Basic query example

    {app="order-service"}

## Filter query example

    {app="order-service"} |= "Order created successfully"

