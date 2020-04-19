### Run tests

```sh
npm run test
```

### Connecting service with app

```sh
serverless
```

### Deploy service

```sh
serverless deploy
```

### Open dashboard

```sh
serverless dashboard
```

### Test service with curl

```sh
# -i flag to see response
 curl --request POST --url https://ulwgjriyc2.execute-api.us-east-1.amazonaws.com/dev/v1/user --data '{"username": "testUsername", "password": "password"}' -H 'Content-Type: application/json' -i
```
