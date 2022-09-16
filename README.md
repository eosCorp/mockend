# 1. My URL
https://mockend.com/eosCorp/mockend/users

# 2. List your fake users with a GET request
curl https://mockend.com/eosCorp/mockend/users

# 3. Fake a creation with a POST
# (don't worry changes aren't persisted)
curl https://mockend.com/eosCorp/mockend/users \
  -X POST \
  -H "Content-Type: application/json" \
  --data '{"name": "alice"}'

# 4. Access your GraphQL endpoint
https://mockend.com/eosCorp/mockend/graphql
