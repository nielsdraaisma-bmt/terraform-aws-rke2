# Terraform AWS RKE2 Cluster

This example is a basic use case for the module, it is verified by Terratest in the ./tests directory (test_dev_cluster.go).
You can run this test by navigating to the ./tests directory and running `go test -v -parallel=10 -timeout=30m -run TestDevCluster`.
The cluster generated by this example should not be considered production ready or scalable, it is a single step beyond a single dev server.