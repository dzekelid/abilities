swagger: "2.0"
x-collection-name: PagerDuty
x-complete: 1
info:
  title: PagerDuty
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /abilities:
    get:
      summary: List abilities
      description: List all of your account's abilities, by name.
      operationId: list-all-of-your-accounts-abilities-by-name
      x-api-path-slug: abilities-get
      responses:
        200:
          description: OK
      tags:
      - Abilities
  /abilities/{id}:
    get:
      summary: Test an ability
      description: Test whether your account has a given ability.
      operationId: test-whether-your-account-has-a-given-ability
      x-api-path-slug: abilitiesid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Abilities