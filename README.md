<!-- @format -->

# How to use Kustomize in k8s

1. `git clone https://github.com/hamzazahidulislam/kustomize-k8s`
2. go to overlay folder `cd overlay/prod/`
3. Run k8s deployement `kustomize build | kubectl apply -f -`

### why we use kustomize beasue its easy to customize multiple configuration of same project. or some time you have so much `k8s.***.yaml` file in your project. that is easy to manage those configuration files
