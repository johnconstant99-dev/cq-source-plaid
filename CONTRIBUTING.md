kind: source
spec:
  name: "plaid"
  path: "cloudquery/plaid"
  version: "v1.1.0"
  destinations: [postgresql]
  spec:
    # plugin spec section
    client_id: ${PLAID_CLIENT_ID}
    secret: ${PLAID_SECRET}
    access_token: ${PLAID_ACCESS_TOKEN}
    environment: sandbox
