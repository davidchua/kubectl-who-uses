# kubectl-who-uses

`kubectl-who-uses` is a kubectl plugin that allows users to identify whether a `Secret`, `ConfigMap` or `ServiceAccount` is being used by any `Deployment` or `Pod`.

## Installation

Copy `kubectl-who_uses` into any directory within your $PATH

## Usage

```
$ kubectl who-uses <resource> <name>

eg.

$ kubectl who-uses secret <secretname>
```
