<p align="center">
<img src="https://app.ipbase.com/img/logo/ipbase.png" width="300"/>
</p>

# ipbase-go: Golang Geolocation API

This package is a Golang wrapper for [ipbase.com] that aims to make the usage of the API as easy as possible in your project.

## Usage

Initialize the API with your API Key (get one for free at [ipbase.com]):

```go
ipbase.Init("YOUR-API-KEY")
```

Afterwards you can make calls to the API like this:

### Status Endpoint

```go
ipbase.Status()
```

### Info Endpoint

```go
ipbase.Info({
    "ip": "1.1.1.1",
    "language": "de"
})
```


Find out more about our endpoints, parameters and response data structure in the [docs]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[docs]: https://ipbase.com/docs
[ipbase.com]: https://ipbase.com

