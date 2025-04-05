# git clone
` git clone git@github.com:dharshan08/traefik_gateway.git`
# install relevant CRDS
`kubectl apply -f https://raw.githubusercontent.com/traefik/traefik/v2.9/docs/content/reference/dynamic-configuration/kubernetes-crd-definition-v1.yml`
# install helm chart 
` helm upgrade --install traefik ./traefik_gateway`

