cat ~/.ssh/id_dsa.pub | ssh root@xxxx "umask 077; mkdir -p .ssh ; cat >> .ssh/authorized_keys"

```
String query = "{foo}";

client.get().uri(uriBuilder -> uriBuilder.path("/graphql")
		.queryParam("query", "{query}")
		.build(query))
		.accept(MediaType.APPLICATION_JSON_UTF8)
		.exchange()
		.expectStatus().isOk();
```
 
 
find ~/.gradle -type f -name "*.lock" -delete
