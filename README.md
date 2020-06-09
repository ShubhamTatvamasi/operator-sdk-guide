# operator-sdk-guide

create a new operator type: helm
```bash
OPERATOR_NAME=visitors-helm-operator
operator-sdk new ${OPERATOR_NAME} --api-version=example.com/v1 \
  --kind=VisitorsApp --type=helm
```

create a new operator type: ansible
```bash
OPERATOR_NAME=visitors-ansible-operator
operator-sdk new $OPERATOR_NAME --api-version=example.com/v1 \
  --kind=VisitorsApp --type=ansible
```

create a new operator type: go
```bash
operator-sdk new visitors-operator --repo github.com/ShubhamTatvamasi/visitors-operator
```
> `go` is the default type

add API in operator
```bash
operator-sdk add api --api-version=example.com/v1 --kind=VisitorsApp
```

generate code for deployment
```bash
operator-sdk generate k8s
```
