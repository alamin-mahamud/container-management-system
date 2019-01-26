# Container Management System

![Container Management System](http://maritime-connector.com/ships_uploads/wana_bhum-9308663-container_ship-8-140842.jpg)

## Table Of Contents

- [Microservices](#microservices)
- [Tools](#tools)
- [Getting Started](#getting-started)
- [Resources](#resources)
- [Versioning](#versioning)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)
- [Credits](#credits)

## Microservices

- users
- authentication
- roles
- consignments
- vessels
- inventory


## Tools

- Golang
- Grpc
- go-micro
- Mongodb
- Docker
- Kubernetes
- Google cloud
- NATS
- Circle CI
- Terraform

## Getting Started

### Prerequisites

1. golang
2. gRPC

``` shell
# This Version is used before we used go-micro
# go get -u google.golang.org/grpc
# go get -u github.com/golang/protobuf/protoc-gen-go

go get -u github.com/micro/protobuf/{proto,protoc-gen-go}
```

## Resources

- [Nginx Guide - Microservices From Design to Deployment](https://www.nginx.com/blog/introduction-to-microservices/)
- [HTTP2 Performance](https://developers.google.com/web/fundamentals/performance/http2/)
- [gRPC beyond the basic](https://blog.gopheracademy.com/advent-2017/go-grpc-beyond-basics/)

## Versioning

We use [semver](#semver.org) for versioning. For the versions available, see the [tags](https://github.com/alamin-mahamud/container-management-system/tags) on this repository.

## Contributing

- Fork it
- Download your fork to your PC (git clone https://github.com/your_username/cobra && cd cobra)
- Create your feature branch (git checkout -b my-new-feature)
- Make changes and add them (git add .)
- Commit your changes (git commit -m 'Add some feature')
- Push to the branch (git push origin my-new-feature)
- Create new pull request


## Authors

- **Alamin Mahamud** - Initial work - [alamin.rocks](https://alamin-rocks.herokuapp.com)

See also the list of [contributors](./CONTRIBUTORS.md) who participated in this project.

## License

This project is licensed under the MIT License.
See the [LICENSE](./LICENSE.md) file for details.


## Credits

1. `README` Banner Image Credit - [Maritime Connector - Andrew Mackinnon](http://maritime-connector.com/ship/wana-bhum-9308663/)
