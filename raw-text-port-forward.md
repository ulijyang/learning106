== port-forward

Forward one or more local ports to a Pod.

.Example: Listen on port `8888` locally and forward to port `5000` in the Pod
----
$ oc port-forward python-1-mz2rf 8888:5000
----