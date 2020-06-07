# operator-sdk-guide

create a new operator
```bash
OPERATOR_NAME=visitors-helm-operator
operator-sdk new ${OPERATOR_NAME} --api-version=example.com/v1 \
  --kind=VisitorsApp --type=helm
```

