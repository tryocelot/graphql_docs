# Ocelot GraphQL Documentation

Use this to generate GQL docs for Ocelot. An API for an Ocelot store is required.

## Generation

```shell
# Place API key in the .env file
echo "API_KEY=my-api-key" >> .env

# Generate your docs
bin/generate

# Commit them
git add .
git commit -m "updated documentation"
git push
```
