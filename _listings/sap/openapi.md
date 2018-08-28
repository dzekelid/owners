swagger: "2.0"
x-collection-name: SAP
x-complete: 1
info:
  title: SAP Translation Hub
  description: to-provide-users-of-software-in-a-global-market-with-texts-in-their-own-language-translations-are-required--sap-translation-hub-enables-you-to-draw-on-saps-translation-experience-across-multiple-products-and-languages-to-propose-translations-for-short-texts-
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/self:
    get:
      summary: Retrieves your own organization
      description: Retrieves the information of the login user's own organization.
      operationId: retrieves-the-information-of-the-login-users-own-organization
      x-api-path-slug: organizationsself-get
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Your
      - Own
      - Organization
  /users/self:
    get:
      summary: Retrieves your own user info
      description: Retrieves the information of the current login user.
      operationId: retrieves-the-information-of-the-current-login-user
      x-api-path-slug: usersself-get
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Your
      - Own
      - User
      - Info