
The goal is to execute a simple patch (`./patches/replica-0.yaml`) against all
deployments with the label, `app: test-app`

`./works`: module label for application (`app: test-app`) is defined in `./works/deployment{,2}/kustomization.yaml`.

`./fails`: module label for application (`app: test-app`) is defined in `./fails/kustomization.yaml`.
