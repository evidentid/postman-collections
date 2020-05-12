# Using Postman collections

To use EvidentID's Postman collections follow these steps:

1. Download [Postman](https://www.postman.com/) and install on your machine
2. Download the Evident Postman collections and environment files from this repository (\*.postman_collection.json and \*.postman_environment.json)
3. Import the collection and environent files into Postman (⌘+O)
4. Go to [Evident Sandbox portal](https://demo.evidentid.com/) and copy your account name and API key from the "Administration" tab
5. Add the API credentials (accountName and apiKey from RP Portal) to the "Initial value" column in the “Evident Sandbox” environment in Postman (cog wheel icon or ⌥+⌘+E)
6. Whitelist “evidentid.com” for [programmatic access of cookies](https://learning.postman.com/docs/postman/sending-api-requests/cookies/#whitelisting-domains-for-programmatic-access-of-cookies)
7. Unfold the collection you're interested in
8. Make the API calls in the order of: 1. Request 2. Submit 3. Retrieve
