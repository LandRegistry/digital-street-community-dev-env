# HM Land Registry Digital Street Proof of Concept - Community Development Environment

## Features

* User Journeys
* Documentation
* Specifications
* Architecture
* Source Code
* Sample Data
* Local Development Environment & Configuration

## Digital Street development environment

This development environment uses the Land Registry common development environment. Please refer to the readme here: https://github.com/LandRegistry/common-dev-env

```shell
git clone https://github.com/LandRegistry/common-dev-env.git digital-street-dev-env
cd digital-street-dev-env
source run.sh up
```

When prompted for the url of your configuration repository, enter: `https://github.com/LandRegistry/digital-street-community-dev-env.git`

## Applications

|Application|Port|Container URL|
|---|---|---|
|[`title-api`](https://github.com/landregistry/digital-street-title-api)|8005|http://title-api:8080|
|[`title-ui`](https://github.com/LandRegistry/digital-street-title-ui)|7004|http://title-ui:7004|
|[`hmlr-api`](https://github.com/LandRegistry/digital-street-hmlr-api)|7008|http://hmlr-api:7008|
|[`conveyancer-api`](https://github.com/LandRegistry/digital-street-conveyancer-api)|7006|http://conveyancer-api:7006|
|[`conveyancer-ui`](https://github.com/LandRegistry/digital-street-conveyancer-ui)|7002, 7003|http://conveyancer-ui:7002 http://conveyancer-ui:7003|
|[`case-management-api`](https://github.com/LandRegistry/digital-street-case-management-api)|8003, 8004|http://case-management-api:8003 http://case-management-api:8004|

Please follow instructions in the `digital-street-cordapp` [README](https://github.com/landregistry/digital-street-cordapp) to set up and deploy the CorDapp.

## Useful links

* [Buy and Sell Process](./docs/Buy-Sell-Journey.pdf)
* [User Journey](./docs/User-Journey-Process-v1.0.md)
* [Slack Channel](https://digitalstreetgroup.slack.com)

## Contributing

We welcome contributions to the project! Please see our [CONTRIBUTING](./CONTRIBUTING.md) guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
