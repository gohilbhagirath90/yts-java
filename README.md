# yts-java
A Java wrapper around the yts v2 API using retrofit.  Pull requests are welcome.  yts methods are grouped into service objects which can be centrally managed by a ytsV2 instance. It will act as a factory for all of the services and will automatically initialize them with your API key (OAuth client id) and optionally a given user access token.
