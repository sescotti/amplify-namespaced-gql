
- (Optional) Open repo in devcontainer
- Run `amplify codegen`
- Command will return the following error:


```bash
node ➜ /workspaces/namespaced-graphql (master) $ amplify codegen
✔ Generated GraphQL operations successfully and saved at src/graphql
⠋ Generating.../GraphQL request: Field "create" argument "input" of type "CreateCustomerInput!" is required, but it was not provided.
.../GraphQL request: Field "create" argument "input" of type "CreateOrderInput!" is required, but it was not provided.
.../GraphQL request: There can be only one operation named "Customer".
.../GraphQL request: There can be only one operation named "Customer".
.../GraphQL request: Field "get" argument "id" of type "ID!" is required, but it was not provided.
.../GraphQL request: There can be only one operation named "Order".
.../GraphQL request: There can be only one operation named "Order".
.../GraphQL request: Field "get" argument "id" of type "ID!" is required, but it was not provided.
✖ Validation of GraphQL query document failed
```
