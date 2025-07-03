[
  {
    "id": "kratos-registration",
    "match": {
      "url": "http://oathkeeper-staging.btaskee.work/self-service/registration<.*>",
      "methods": ["GET", "POST"]
    },
    "authenticators": [
      { "handler": "anonymous" }
    ],
    "authorizer": {
      "handler": "allow"
    },
    "mutators": [
      { "handler": "noop" }
    ],
    "upstream": {
      "url": "http://kratos-staging.btaskee.work"
    }
  }
]
