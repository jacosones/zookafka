1. Create RBAC for new namespace
If you want to use WCSV9 Helm Charts to deploy on a new namespace, please create the rbac for that namespace by edit rbac.yaml and change the namespace name with your target one.

2. Support Commerce 9.0.0.1
If you want to deploy Commerce 9.0.0.1, you must specify the value "CommerceVersion: 9.0.0.1 and OVERRIDE_PRECONFIG: true" in vaules.yaml, for 9.0.0.2 or higher, you can ignore this step