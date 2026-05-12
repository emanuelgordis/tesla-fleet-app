# tesla-fleet-app

Hosts the public key used by Tesla Fleet API partner-account verification for the [sf-parking-watcher](https://github.com/emanuelgordis/sf-parking-watcher) project (or wherever the corresponding private key lives).

The single served file at `https://parking.trimresearch.com/.well-known/appspecific/com.tesla.3p.public-key.pem` is fetched once by Tesla during partner-account registration.
