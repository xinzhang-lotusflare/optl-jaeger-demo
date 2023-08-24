# optl-jaeger-demo

A simple demo to create OpenTelemetry-Jaeger system.

Jaeger is deployed as a single instance, which persists data in embeded storage system.

Demo app has 2 impementations.

- [One](https://github.com/xinzhang-lotusflare/optl-jaeger-demo/blob/105d67353a3070eaec1b0b7958cabf7cc6f7c4d5/app/src/server.go) will send traces through OpenTelemetry as gateway
  https://github.com/xinzhang-lotusflare/optl-jaeger-demo/blob/105d67353a3070eaec1b0b7958cabf7cc6f7c4d5/app/src/server.go#L42

- The [other](https://github.com/xinzhang-lotusflare/optl-jaeger-demo/blob/105d67353a3070eaec1b0b7958cabf7cc6f7c4d5/app/src/server-j.go) will send to Jaeger directly
  https://github.com/xinzhang-lotusflare/optl-jaeger-demo/blob/105d67353a3070eaec1b0b7958cabf7cc6f7c4d5/app/src/server-j.go#L42

