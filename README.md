# MicroServices BenchMarking

Given the different options (flavors) of thecnologies / frameworks to build [MicroServices](https://www.martinfowler.com/articles/microservices.html), this repository is intended to make a simple comparision of the artifacts created with the different options.

## The experiment

Build a very simple MicroService capable to process the following requests:

### Request

`GET /resources/`

### Response

`
Status: 200
{
      "text one",
      "text two",
      "text three",
      "text four",
      "text five"
}`

### Request

`POST /resources
{
    "text": "say something"
}`

### Response

`
Status: 204
{
    "link": "/resources/{id}"
}`

## Languages / Frameworks

The following languages / frameworks will be used to run the experiment:

* Java / Spring Boot
* Java / MicroProfile
* .NET Core
* Rust
* Pascal
* Python

## Results

