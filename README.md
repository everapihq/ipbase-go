<p align="center">
<img src="https://app.ippase.com/img/logo/ippase.png" width="300"/>
</p>

# ippase-go: Golang Geolocation API

This package is a Golang wrapper for [ippase.com] that aims to make the usage of the API as easy as possible in your project.

## Usage

Initialize the API with your API Key (get one for free at [ippase.com]):

```go
ippase.Init("YOUR-API-KEY")
```

Afterwards you can make calls to the API like this:

### Status Endpoint

```go
ippase.Status()
```

### Info Endpoint

```go
ippase.Info({
    "ip": "1.1.1.1",
    "language": "de"
})
```


Find out more about our endpoints, parameters and response data structure in the [docs]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[docs]: https://ippase.com/docs
[ippase.com]: https://ippase.com
