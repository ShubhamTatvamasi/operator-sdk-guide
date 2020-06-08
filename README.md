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

