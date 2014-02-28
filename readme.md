#KidoZen Agent
Use this service to connect to the KidoZen platform and access to your Line of Business Systems even behind the firewall.

##Installation
Run npm to install the dependencies

	npm install

Create a config.json file (you can copy and edit config.json.sample)

	{
	    "name": "name-of-the-agent",	// for instance, it could be the machine's name. 
	    "credentials": {
	        "user": "my-user@kidozen.com",
	        "password": "my-password",
	        "marketplace": "https://my-company.kidocloud.com"
	    }
	}

Run the service executing:

	node ./bin/server [--level error|warn|info|verbose|debug]

npm SSL Error:
npm ERR! Error: SSL Error: SELF_SIGNED_CERT_IN_CHAIN is fixed on agent versión .22
	 
