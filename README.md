# shipyard

This project is used to manage Shipyard, the infrastructure and tooling that enables hosted applications on Edge, and
its related projects on GitHub.

[![Stories in Ready](https://badge.waffle.io/30x/shipyard.png?label=ready&title=Ready)](http://waffle.io/30x/shipyard)

## Related Projects

* [30x/authsdk](https://github.com/30x/authsdk): APIs around authn/authz for Edge _(soon to be renamed)_
* [30x/congress](https://github.com/30x/congress): Kubernetes controller for automatically configuring
[network isolation](http://kubernetes.io/docs/user-guide/networkpolicies/)
* [30x/dispatcher](https://github.com/30x/dispatcher): Ingress controller _(router)_ for Shipyard applications _(this
router is also a general purpose ingress/router)_
* [30x/enrober](https://github.com/30x/enrober): Shipyard deployment controller
* [30x/kiln](https://github.com/30x/kiln): Shipyard build service
* [30x/microgateway-plugin-sso-proxy](https://github.com/30x/microgateway-plugin-sso-proxy): Proxy server that validates
requests have a valid Edge SSO JWT
* [30x/secretrestart](https://github.com/30x/secretrestart): Sidecar controller for `30x/kiln` deployment that juggles
the AWS credentials for ECR
* [30x/shipyardctl](https://github.com/30x/shipyardctl): CLI for Shipyard
