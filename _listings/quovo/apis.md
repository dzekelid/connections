---
name: Quovo
x-slug: quovo
description: Quovo&rsquo;s API provides methods for retrieving data from financial
  institutions on behalf of clients, advisors, and other users. This documentation
  includes detailed explanations of API endpoints and common data definitions. Please
  note that this documentation does not list all API endpoints. Additionally, you
  may not have access to all of the listed endpoints depending on the services you&rsquo;ve
  purchased from Quovo.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
x-kinRank: "7"
x-alexaRank: "391003"
tags: Connections
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/apis.md
specificationVersion: "0.14"
apis:
- name: Quovo API v3 - Get a connection's sync progress
  x-api-slug: connectionsconnection-idsync-get
  description: Check the ongoing Sync progress of an Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idsync-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idsync-get-openapi.md
- name: Quovo API v3 - Get a connection's transactions
  x-api-slug: connectionsconnection-idtransactions-get
  description: Provides information on a connection's historical transactions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idtransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idtransactions-get-openapi.md
- name: Quovo API v3 - Get  all connections
  x-api-slug: connections-get
  description: Retrieves all connections across all users.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connections-get-openapi.md
- name: Quovo API v3 - Fetch the Connection's Accounts
  x-api-slug: connectionsconnection-idaccounts-get
  description: |-
    Fetches all of the accounts belonging to the connection. These are automatically created by Quovo after an initial sync.

    If you have a Postman Environment set up, this request will automatically set the variable `account_id` to the id of the first account returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idaccounts-get-openapi.md
- name: Quovo API v3 - Get a user's connections
  x-api-slug: usersuser-idconnections-get
  description: Returns all of a user's connections.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/usersuser-idconnections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/usersuser-idconnections-get-openapi.md
- name: Quovo API v3 - Get a connection's manual holdings
  x-api-slug: connectionsconnection-idmanual-holdings-get
  description: Fetches all Manual Assets for an Account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idmanual-holdings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idmanual-holdings-get-openapi.md
- name: Quovo API v3 - Get a connection's holdings
  x-api-slug: connectionsconnection-idholdings-get
  description: Fetches all holdings for a specific connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idholdings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idholdings-get-openapi.md
- name: Quovo API v3 - Initiate a Sync on the Connection
  x-api-slug: connectionsconnection-idsync-post
  description: |-
    Initiates a new sync on the connection.

    Syncs are an ongoing update attempt on a connection. Syncing a newly created connection ensures the connction contains the most recent, available financial data, which includes current holdings and historical transactions.

    Before making the request, check that the `{{connection_id}}` Postman variable is set properly, or that the URL contains the correct connection id.

    The request will return a sync object with a `progress.state` of "queued", which indicates the sync request was sent successfully.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idsync-post-openapi.md
- name: Quovo API v3 - Get a single connection
  x-api-slug: connectionsconnection-id-get
  description: Provides information on a specific connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-get-openapi.md
- name: Quovo API v3 - Modify a connection
  x-api-slug: connectionsconnection-id-put
  description: Modifies an existing connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-put-openapi.md
- name: Quovo API v3 - Delete a connection
  x-api-slug: connectionsconnection-id-delete
  description: Deletes an existing Quovo connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-delete-openapi.md
- name: Quovo API v3 - Create a Connection
  x-api-slug: usersuser-idconnections-post
  description: Creates a new Quovo Connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/usersuser-idconnections-post-openapi.md
- name: Quovo API v3 - Get challenges for a connection
  x-api-slug: connectionsconnection-idchallenges-get
  description: Retrieves any Challenges associated with a connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idchallenges-get-openapi.md
- name: Quovo API v3 - Initiate a Sync on the Connection
  x-api-slug: connectionsconnection-idsync-post
  description: |-
    Initiates a new sync on the connection.

    Syncs are an ongoing update attempt on a connection. Syncing a newly created connection ensures the connction contains the most recent, available financial data, which includes current holdings and historical transactions.

    Before making the request, check that the `{{connection_id}}` Postman variable is set properly, or that the URL contains the correct connection id.

    The request will return a sync object with a `progress.state` of "queued", which indicates the sync request was sent successfully.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idsync-post-openapi.md
- name: Quovo API v3 - Get a single connection
  x-api-slug: connectionsconnection-id-get
  description: Provides information on a specific connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-get-openapi.md
- name: Quovo API v3 - Modify a connection
  x-api-slug: connectionsconnection-id-put
  description: Modifies an existing connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-put-openapi.md
- name: Quovo API v3 - Delete a connection
  x-api-slug: connectionsconnection-id-delete
  description: Deletes an existing Quovo connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-delete-openapi.md
- name: Quovo API v3 - Create a Connection
  x-api-slug: usersuser-idconnections-post
  description: Creates a new Quovo Connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/usersuser-idconnections-post-openapi.md
- name: Quovo API v3 - Get challenges for a connection
  x-api-slug: connectionsconnection-idchallenges-get
  description: Retrieves any Challenges associated with a connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idchallenges-get-openapi.md
- name: Quovo API v3 - Get challenges for a connection
  x-api-slug: connectionsconnection-idchallenges-get
  description: Retrieves any Challenges associated with a connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idchallenges-get-openapi.md
- name: Quovo API v3 - Get challenges for a connection
  x-api-slug: connectionsconnection-idchallenges-get
  description: Retrieves any Challenges associated with a connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idchallenges-get-openapi.md
- name: Quovo API v3 - Get challenges for a connection
  x-api-slug: connectionsconnection-idchallenges-get
  description: Retrieves any Challenges associated with a connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idchallenges-get-openapi.md
- name: Quovo API v3 - Create a Connection
  x-api-slug: usersuser-idconnections-post
  description: Creates a new Quovo Connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/usersuser-idconnections-post-openapi.md
- name: Quovo API v3 - Create a Connection
  x-api-slug: usersuser-idconnections-post
  description: Creates a new Quovo Connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/usersuser-idconnections-post-openapi.md
- name: Quovo API v3 - Create a Connection
  x-api-slug: usersuser-idconnections-post
  description: Creates a new Quovo Connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/usersuser-idconnections-post-openapi.md
- name: Quovo API v3 - Delete a connection
  x-api-slug: connectionsconnection-id-delete
  description: Deletes an existing Quovo connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-delete-openapi.md
- name: Quovo API v3 - Delete a connection
  x-api-slug: connectionsconnection-id-delete
  description: Deletes an existing Quovo connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-delete-openapi.md
- name: Quovo API v3 - Delete a connection
  x-api-slug: connectionsconnection-id-delete
  description: Deletes an existing Quovo connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-delete-openapi.md
- name: Quovo API v3 - Modify a connection
  x-api-slug: connectionsconnection-id-put
  description: Modifies an existing connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-put-openapi.md
- name: Quovo API v3 - Modify a connection
  x-api-slug: connectionsconnection-id-put
  description: Modifies an existing connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-put-openapi.md
- name: Quovo API v3 - Modify a connection
  x-api-slug: connectionsconnection-id-put
  description: Modifies an existing connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-put-openapi.md
- name: Quovo API v3 - Get a single connection
  x-api-slug: connectionsconnection-id-get
  description: Provides information on a specific connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-get-openapi.md
- name: Quovo API v3 - Get a single connection
  x-api-slug: connectionsconnection-id-get
  description: Provides information on a specific connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-get-openapi.md
- name: Quovo API v3 - Get a single connection
  x-api-slug: connectionsconnection-id-get
  description: Provides information on a specific connection.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-id-get-openapi.md
- name: Quovo API v3 - Initiate a Sync on the Connection
  x-api-slug: connectionsconnection-idsync-post
  description: |-
    Initiates a new sync on the connection.

    Syncs are an ongoing update attempt on a connection. Syncing a newly created connection ensures the connction contains the most recent, available financial data, which includes current holdings and historical transactions.

    Before making the request, check that the `{{connection_id}}` Postman variable is set properly, or that the URL contains the correct connection id.

    The request will return a sync object with a `progress.state` of "queued", which indicates the sync request was sent successfully.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idsync-post-openapi.md
- name: Quovo API v3 - Initiate a Sync on the Connection
  x-api-slug: connectionsconnection-idsync-post
  description: |-
    Initiates a new sync on the connection.

    Syncs are an ongoing update attempt on a connection. Syncing a newly created connection ensures the connction contains the most recent, available financial data, which includes current holdings and historical transactions.

    Before making the request, check that the `{{connection_id}}` Postman variable is set properly, or that the URL contains the correct connection id.

    The request will return a sync object with a `progress.state` of "queued", which indicates the sync request was sent successfully.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idsync-post-openapi.md
- name: Quovo API v3 - Initiate a Sync on the Connection
  x-api-slug: connectionsconnection-idsync-post
  description: |-
    Initiates a new sync on the connection.

    Syncs are an ongoing update attempt on a connection. Syncing a newly created connection ensures the connction contains the most recent, available financial data, which includes current holdings and historical transactions.

    Before making the request, check that the `{{connection_id}}` Postman variable is set properly, or that the URL contains the correct connection id.

    The request will return a sync object with a `progress.state` of "queued", which indicates the sync request was sent successfully.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28293-quovo.jpg
  humanURL: http://quovo.com
  baseURL: https://example.com//
  tags: SaaS, Technology, Enterprise, Financial Services, Financial, Market Data,
    Profiles, General Data, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/connections/master/_listings/quovo/connectionsconnection-idsync-post-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.quovo.com/fintech-blog/feed/
- type: x-postman-collection
  url: https://www.getpostman.com/collections/82cf673bb22d4f8b8881
- type: x-website
  url: http://quovo.com
- type: x-api-gallery
  url: http://quandl.api.gallery.streamdata.io
- type: x-api-stack
  url: http://quovo.stack.network
- type: x-authentication
  url: https://api.quovo.com/docs/v3/#authentication
- type: x-blog
  url: https://www.quovo.com/fintech-blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/quovo
- type: x-developer
  url: https://api.quovo.com/docs/v3/
- type: x-email
  url: audit@quovo.com
- type: x-email
  url: info@quovo.com
- type: x-email
  url: copyright@quovo.com
- type: x-email
  url: support@quovo.com
- type: x-github
  url: https://github.com/quovo
- type: x-twitter
  url: https://twitter.com/quovo
- type: x-webhook
  url: https://api.quovo.com/docs/v3/#webhooks
- type: x-website
  url: https://www.quovo.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---