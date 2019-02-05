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

|Application|Port|Internal Container URL|
|---|---|---|
|[`conveyancer-ui`](http://github.com/LandRegistry/digital-street-conveyancer-ui)|7002-7003|https://conveyancer-ui:8080|
|[`case-management-api`](http://github.com/LandRegistry/digital-street-case-management-api)|8003-8004|http://case-management-api:8080|
|[`hmlr-ui`](http://github.com/LandRegistry/digital-street-hmlr-ui)|7001|https://hmlr-ui:8080|
|[`title-ui`](http://github.com/LandRegistry/digital-street-title-ui)|7004|https://title-ui:8080|
|[`title-api`](http://github.com/LandRegistry/digital-street-title-api)|8005|http://title-api:8080|
|[`lender-ui`](http://github.com/LandRegistry/digital-street-lender-ui)|7009-7010|https://lender-ui:8080|
|[`lender-management-api`](http://github.com/LandRegistry/digital-street-lender-management-api)|8001-2002|http://lender-management-api:8080|

## Applications outside dev env

|Application|Port|
|---|---|
|[`digital-street-cordapp`](http://github.com/LandRegistry/digital-street-cordapp)|10002-10033,2222|
|[`conveyancer-api`](http://github.com/LandRegistry/digital-street-conveyancer-api)|7006-7007|
|[`hmlr-api`](http://github.com/LandRegistry/digital-street-hmlr-api)|7008|
|[`lender-api`](http://github.com/LandRegistry/digital-street-lender-api)|7006-7007|

Please follow instructions in the `digital-street-cordapp` [README](https://github.com/landregistry/digital-street-cordapp) to set up and deploy the CorDapp.

## Useful links

* [Buy and Sell Process](./docs/Buy-Sell-Journey.pdf)
* [User Journey](./docs/User-Journey-Process-v1.0.md)
* [Slack Channel](https://digitalstreetgroup.slack.com)

## Contributing

We welcome contributions to the project! Please see our [CONTRIBUTING](./CONTRIBUTING.md) guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
