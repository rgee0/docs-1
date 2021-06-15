# Get started with your free trial

Welcome to your tree trial of [inlets PRO](https://github.com/inlets/inlets-pro).

inlets PRO has both a client and a server component that supports HTTPS and TCP. The client (usually on a private network) connects to the server (usually hosted on a public network), and then tunnels one or more HTTP or TCP services to the other network.

Contrary to what you may have heard, inlets PRO does not mean that you need to expose applications on the Internet, often you only need to make the control-port (TCP/8123) of the inlets PRO server accessible by the client.

You can find out [more in the docs](https://docs.inlets.dev/)

> Not applied for a free trial yet? [Apply now to kick the tires](https://inlets.dev/pricing/)
 
## Community & support

You can [join the OpenFaaS community](https://slack.openfaas.io/) and chat with other users about inlets PRO in the `#inlets` channel.

Alternatively, you're welcome to reply to the email you were sent with your trial key.

## Use-cases and tutorials

You can find use-cases on the [inlets PRO blog](https://inlets.dev/blog)

For a list of tutorials [see the tutorials section of the docs](https://docs.inlets.dev/#/?id=tutorials)

### Kubernetes

If you're wanting to use tunnels with Kubernetes then you can deploy either the client or server component, or both as Pods or Deployments as required.

Or you can find out what other [charts exist here](https://github.com/inlets/inlets-pro/tree/master/chart)

Another option is to use the [inlets-operator](https://github.com/inlets/inlets-operator) brings LoadBalancers with public IP addresses to your local Kubernetes clusters.

See also: [inlets-operator quick start for various clouds](https://docs.inlets.dev/#/tools/inlets-operator?id=inlets-operator-reference-documentation)

### Docker

Docker users can deploy inlets PRO clients and servers as containers using `ghcr.io/inlets/inlets-pro`.

Find the [latest tags here](https://github.com/orgs/inlets/packages/container/package/inlets-pro).

### HTTPS tunnels

You can create a tunnel server and run inlets PRO there yourself, or you can use inletsctl to automate the creation.

inlets PRO has a built-in support for Let's Encrypt, so that you can obtain TLS certificates for hosts or APIs that you share without needing a reverse proxy.

[inletsctl documentation](https://docs.inlets.dev/#/tools/inletsctl?id=inletsctl-reference-documentation)

### TCP tunnels

You can create a tunnel server and run inlets PRO there yourself, or you can use inletsctl to automate the creation.

Examples of what you might expose include: a reverse proxy to host many different sites, SSH for remote access, RDP, a gRPC API or a database.

[inletsctl documentation](https://docs.inlets.dev/#/tools/inletsctl?id=inletsctl-reference-documentation)

