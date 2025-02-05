k logs keycloak-0 -n keycloak
Defaulted container "keycloak" out of: keycloak, prepare-write-dirs (init)
keycloak 08:21:08.29 INFO  ==>
keycloak 08:21:08.29 INFO  ==> Welcome to the Bitnami keycloak container
keycloak 08:21:08.29 INFO  ==> Subscribe to project updates by watching https://github.com/bitnami/containers
keycloak 08:21:08.29 INFO  ==> Did you know there are enterprise versions of the Bitnami catalog? For enhanced secure software supply chain features, unlimited pulls from Docker, LTS support, or application customization, see Bitnami Premium or Tanzu Application Catalog. See https://www.arrow.com/globalecs/na/vendors/bitnami/ for more information.
keycloak 08:21:08.30 INFO  ==>
keycloak 08:21:08.30 INFO  ==> ** Starting keycloak setup **
keycloak 08:21:08.32 INFO  ==> Validating settings in KEYCLOAK_* env vars...
keycloak 08:21:08.34 INFO  ==> Trying to connect to PostgreSQL server keycloak-postgresql...
timeout reached before the port went into state "inuse"
timeout reached before the port went into state "inuse"
keycloak 08:21:40.51 INFO  ==> Found PostgreSQL server listening at keycloak-postgresql:5432
keycloak 08:21:40.52 INFO  ==> Configuring database settings
keycloak 08:21:40.53 INFO  ==> Enabling statistics
keycloak 08:21:40.54 INFO  ==> Enabling health endpoints
keycloak 08:21:40.54 INFO  ==> Configuring http settings
keycloak 08:21:40.55 INFO  ==> Configuring hostname settings
keycloak 08:21:40.56 INFO  ==> Configuring cache count
keycloak 08:21:40.56 INFO  ==> Configuring log level

keycloak 08:21:40.57 INFO  ==> ** keycloak setup finished! **
keycloak 08:21:40.58 INFO  ==> ** Starting keycloak **
Appending additional Java properties to JAVA_OPTS
Updating the configuration and installing your custom providers, if any. Please wait.
2025-02-04 08:21:53,921 WARN  [io.qua.config] (build-23) Unrecognized configuration key "quarkus.micrometer.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:21:53,922 WARN  [io.qua.config] (build-23) Unrecognized configuration key "quarkus.smallrye-health.extensions.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:22:01,521 WARN  [org.key.services] (build-23) KC-SERVICES0047: metrics (org.jboss.aerogear.keycloak.metrics.MetricsEndpointFactory) is implementing the internal SPI realm-restapi-extension. This SPI is internal and may change without notice
2025-02-04 08:22:05,024 WARN  [org.key.services] (build-23) KC-SERVICES0047: metrics-listener (org.jboss.aerogear.keycloak.metrics.MetricsEventListenerFactory) is implementing the internal SPI eventsListener. This SPI is internal and may change without notice
2025-02-04 08:22:08,620 INFO  [io.qua.hib.orm.dep.HibernateOrmProcessor] (build-6) A legacy persistence.xml file is present in the classpath. This file will be used to configure JPA/Hibernate ORM persistence units, and any configuration of the Hibernate ORM extension will be ignored. To ignore persistence.xml files instead, set the configuration property 'quarkus.hibernate-orm.persistence-xml.ignore' to 'true'.
2025-02-04 08:22:28,037 INFO  [io.qua.dep.QuarkusAugmentor] (main) Quarkus augmentation completed in 40495ms
PS D:\> k logs -f keycloak-0 -n keycloak
Defaulted container "keycloak" out of: keycloak, prepare-write-dirs (init)
keycloak 08:21:08.29 INFO  ==>
keycloak 08:21:08.29 INFO  ==> Welcome to the Bitnami keycloak container
keycloak 08:21:08.29 INFO  ==> Subscribe to project updates by watching https://github.com/bitnami/containers
keycloak 08:21:08.29 INFO  ==> Did you know there are enterprise versions of the Bitnami catalog? For enhanced secure software supply chain features, unlimited pulls from Docker, LTS support, or application customization, see Bitnami Premium or Tanzu Application Catalog. See https://www.arrow.com/globalecs/na/vendors/bitnami/ for more information.
keycloak 08:21:08.30 INFO  ==>
keycloak 08:21:08.30 INFO  ==> ** Starting keycloak setup **
keycloak 08:21:08.32 INFO  ==> Validating settings in KEYCLOAK_* env vars...
keycloak 08:21:08.34 INFO  ==> Trying to connect to PostgreSQL server keycloak-postgresql...
timeout reached before the port went into state "inuse"
timeout reached before the port went into state "inuse"
keycloak 08:21:40.51 INFO  ==> Found PostgreSQL server listening at keycloak-postgresql:5432
keycloak 08:21:40.52 INFO  ==> Configuring database settings
keycloak 08:21:40.53 INFO  ==> Enabling statistics
keycloak 08:21:40.54 INFO  ==> Enabling health endpoints
keycloak 08:21:40.54 INFO  ==> Configuring http settings
keycloak 08:21:40.55 INFO  ==> Configuring hostname settings
keycloak 08:21:40.56 INFO  ==> Configuring cache count
keycloak 08:21:40.56 INFO  ==> Configuring log level

keycloak 08:21:40.57 INFO  ==> ** keycloak setup finished! **
keycloak 08:21:40.58 INFO  ==> ** Starting keycloak **
Appending additional Java properties to JAVA_OPTS
Updating the configuration and installing your custom providers, if any. Please wait.
2025-02-04 08:21:53,921 WARN  [io.qua.config] (build-23) Unrecognized configuration key "quarkus.micrometer.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:21:53,922 WARN  [io.qua.config] (build-23) Unrecognized configuration key "quarkus.smallrye-health.extensions.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:22:01,521 WARN  [org.key.services] (build-23) KC-SERVICES0047: metrics (org.jboss.aerogear.keycloak.metrics.MetricsEndpointFactory) is implementing the internal SPI realm-restapi-extension. This SPI is internal and may change without notice
2025-02-04 08:22:05,024 WARN  [org.key.services] (build-23) KC-SERVICES0047: metrics-listener (org.jboss.aerogear.keycloak.metrics.MetricsEventListenerFactory) is implementing the internal SPI eventsListener. This SPI is internal and may change without notice
2025-02-04 08:22:08,620 INFO  [io.qua.hib.orm.dep.HibernateOrmProcessor] (build-6) A legacy persistence.xml file is present in the classpath. This file will be used to configure JPA/Hibernate ORM persistence units, and any configuration of the Hibernate ORM extension will be ignored. To ignore persistence.xml files instead, set the configuration property 'quarkus.hibernate-orm.persistence-xml.ignore' to 'true'.
2025-02-04 08:22:28,037 INFO  [io.qua.dep.QuarkusAugmentor] (main) Quarkus augmentation completed in 40495ms
Running the server in development mode. DO NOT use this configuration in production.
2025-02-04 08:22:32,065 WARN  [io.quarkus.config] (main) Unrecognized configuration key "quarkus.micrometer.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:22:32,066 WARN  [io.quarkus.config] (main) Unrecognized configuration key "quarkus.smallrye-health.extensions.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:22:40,048 INFO  [org.keycloak.quarkus.runtime.storage.infinispan.CacheManagerFactory] (Thread-5) Starting Infinispan embedded cache manager
2025-02-04 08:22:40,769 INFO  [org.infinispan.CONTAINER] (Thread-5) Virtual threads support enabled
2025-02-04 08:22:41,658 INFO  [org.infinispan.CONTAINER] (Thread-5) ISPN000556: Starting user marshaller 'org.infinispan.commons.marshall.ImmutableProtoStreamMarshaller'
2025-02-04 08:22:42,543 WARN  [org.jgroups.stack.Configurator] (Thread-5) JGRP000014: ThreadPool.thread_dumps_threshold has been deprecated: ignored
2025-02-04 08:22:42,656 INFO  [org.infinispan.CLUSTER] (Thread-5) ISPN000078: Starting JGroups channel `ISPN` with stack `kubernetes`
2025-02-04 08:22:42,657 INFO  [org.jgroups.JChannel] (Thread-5) local_addr: fe272c1f-5413-43cc-b2cf-d8b5b31e2733, name: keycloak-0-16699
2025-02-04 08:22:42,741 INFO  [org.jgroups.protocols.FD_SOCK2] (Thread-5) server listening on *.57800
2025-02-04 08:22:44,746 INFO  [org.jgroups.protocols.pbcast.GMS] (Thread-5) keycloak-0-16699: no members discovered after 2002 ms: creating cluster as coordinator
2025-02-04 08:22:44,835 INFO  [org.infinispan.CLUSTER] (Thread-5) ISPN000094: Received new cluster view for channel ISPN: [keycloak-0-16699|0] (1) [keycloak-0-16699]
2025-02-04 08:22:45,447 INFO  [org.infinispan.CLUSTER] (Thread-5) ISPN000079: Channel `ISPN` local address is `keycloak-0-16699`, physical addresses are `[10.244.0.97:7800]`
2025-02-04 08:22:47,954 INFO  [org.keycloak.quarkus.runtime.storage.database.liquibase.QuarkusJpaUpdaterProvider] (main) Initializing database schema. Using changelog META-INF/jpa-changelog-master.xml
2025-02-04 08:23:06,758 WARN  [io.agroal.pool] (main) Datasource '<default>': JDBC resources leaked: 3 ResultSet(s) and 0 Statement(s)
2025-02-04 08:23:06,759 WARN  [io.agroal.pool] (main) Datasource '<default>': JDBC resources leaked: 156 ResultSet(s) and 0 Statement(s)
2025-02-04 08:23:08,080 INFO  [org.keycloak.connections.infinispan.DefaultInfinispanConnectionProviderFactory] (main) Node name: keycloak-0-16699, Site name: null
2025-02-04 08:23:08,755 INFO  [org.keycloak.broker.provider.AbstractIdentityProviderMapper] (main) Registering class org.keycloak.broker.provider.mappersync.ConfigSyncEventListener
2025-02-04 08:23:08,786 INFO  [org.keycloak.services] (main) KC-SERVICES0050: Initializing master realm
2025-02-04 08:23:16,758 INFO  [org.keycloak.services] (main) KC-SERVICES0077: Created temporary admin user with username user
2025-02-04 08:23:16,867 WARN  [io.agroal.pool] (main) Datasource '<default>': JDBC resources leaked: 3 ResultSet(s) and 0 Statement(s)
2025-02-04 08:23:17,573 INFO  [io.quarkus] (main) Keycloak 26.1.0 on JVM (powered by Quarkus 3.15.2) started in 48.790s. Listening on: http://0.0.0.0:8080
2025-02-04 08:23:17,573 INFO  [io.quarkus] (main) Profile dev activated.
2025-02-04 08:23:17,574 INFO  [io.quarkus] (main) Installed features: [agroal, cdi, hibernate-orm, jdbc-postgresql, keycloak, narayana-jta, opentelemetry, reactive-routes, rest, rest-jackson, smallrye-context-propagation, vertx]
PS D:\> k logs -f keycloak-0 -n keycloak
Defaulted container "keycloak" out of: keycloak, prepare-write-dirs (init)
keycloak 08:21:08.29 INFO  ==>
keycloak 08:21:08.29 INFO  ==> Welcome to the Bitnami keycloak container
keycloak 08:21:08.29 INFO  ==> Subscribe to project updates by watching https://github.com/bitnami/containers
keycloak 08:21:08.29 INFO  ==> Did you know there are enterprise versions of the Bitnami catalog? For enhanced secure software supply chain features, unlimited pulls from Docker, LTS support, or application customization, see Bitnami Premium or Tanzu Application Catalog. See https://www.arrow.com/globalecs/na/vendors/bitnami/ for more information.
keycloak 08:21:08.30 INFO  ==>
keycloak 08:21:08.30 INFO  ==> ** Starting keycloak setup **
keycloak 08:21:08.32 INFO  ==> Validating settings in KEYCLOAK_* env vars...
keycloak 08:21:08.34 INFO  ==> Trying to connect to PostgreSQL server keycloak-postgresql...
timeout reached before the port went into state "inuse"
timeout reached before the port went into state "inuse"
keycloak 08:21:40.51 INFO  ==> Found PostgreSQL server listening at keycloak-postgresql:5432
keycloak 08:21:40.52 INFO  ==> Configuring database settings
keycloak 08:21:40.53 INFO  ==> Enabling statistics
keycloak 08:21:40.54 INFO  ==> Enabling health endpoints
keycloak 08:21:40.54 INFO  ==> Configuring http settings
keycloak 08:21:40.55 INFO  ==> Configuring hostname settings
keycloak 08:21:40.56 INFO  ==> Configuring cache count
keycloak 08:21:40.56 INFO  ==> Configuring log level

keycloak 08:21:40.57 INFO  ==> ** keycloak setup finished! **
keycloak 08:21:40.58 INFO  ==> ** Starting keycloak **
Appending additional Java properties to JAVA_OPTS
Updating the configuration and installing your custom providers, if any. Please wait.
2025-02-04 08:21:53,921 WARN  [io.qua.config] (build-23) Unrecognized configuration key "quarkus.micrometer.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:21:53,922 WARN  [io.qua.config] (build-23) Unrecognized configuration key "quarkus.smallrye-health.extensions.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:22:01,521 WARN  [org.key.services] (build-23) KC-SERVICES0047: metrics (org.jboss.aerogear.keycloak.metrics.MetricsEndpointFactory) is implementing the internal SPI realm-restapi-extension. This SPI is internal and may change without notice
2025-02-04 08:22:05,024 WARN  [org.key.services] (build-23) KC-SERVICES0047: metrics-listener (org.jboss.aerogear.keycloak.metrics.MetricsEventListenerFactory) is implementing the internal SPI eventsListener. This SPI is internal and may change without notice
2025-02-04 08:22:08,620 INFO  [io.qua.hib.orm.dep.HibernateOrmProcessor] (build-6) A legacy persistence.xml file is present in the classpath. This file will be used to configure JPA/Hibernate ORM persistence units, and any configuration of the Hibernate ORM extension will be ignored. To ignore persistence.xml files instead, set the configuration property 'quarkus.hibernate-orm.persistence-xml.ignore' to 'true'.
2025-02-04 08:22:28,037 INFO  [io.qua.dep.QuarkusAugmentor] (main) Quarkus augmentation completed in 40495ms
Running the server in development mode. DO NOT use this configuration in production.
2025-02-04 08:22:32,065 WARN  [io.quarkus.config] (main) Unrecognized configuration key "quarkus.micrometer.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:22:32,066 WARN  [io.quarkus.config] (main) Unrecognized configuration key "quarkus.smallrye-health.extensions.enabled" was provided; it will be ignored; verify that the dependency extension for this configuration is set or that you did not make a typo
2025-02-04 08:22:40,048 INFO  [org.keycloak.quarkus.runtime.storage.infinispan.CacheManagerFactory] (Thread-5) Starting Infinispan embedded cache manager
2025-02-04 08:22:40,769 INFO  [org.infinispan.CONTAINER] (Thread-5) Virtual threads support enabled
2025-02-04 08:22:41,658 INFO  [org.infinispan.CONTAINER] (Thread-5) ISPN000556: Starting user marshaller 'org.infinispan.commons.marshall.ImmutableProtoStreamMarshaller'
2025-02-04 08:22:42,543 WARN  [org.jgroups.stack.Configurator] (Thread-5) JGRP000014: ThreadPool.thread_dumps_threshold has been deprecated: ignored
2025-02-04 08:22:42,656 INFO  [org.infinispan.CLUSTER] (Thread-5) ISPN000078: Starting JGroups channel `ISPN` with stack `kubernetes`
2025-02-04 08:22:42,657 INFO  [org.jgroups.JChannel] (Thread-5) local_addr: fe272c1f-5413-43cc-b2cf-d8b5b31e2733, name: keycloak-0-16699
2025-02-04 08:22:42,741 INFO  [org.jgroups.protocols.FD_SOCK2] (Thread-5) server listening on *.57800
2025-02-04 08:22:44,746 INFO  [org.jgroups.protocols.pbcast.GMS] (Thread-5) keycloak-0-16699: no members discovered after 2002 ms: creating cluster as coordinator
2025-02-04 08:22:44,835 INFO  [org.infinispan.CLUSTER] (Thread-5) ISPN000094: Received new cluster view for channel ISPN: [keycloak-0-16699|0] (1) [keycloak-0-16699]
2025-02-04 08:22:45,447 INFO  [org.infinispan.CLUSTER] (Thread-5) ISPN000079: Channel `ISPN` local address is `keycloak-0-16699`, physical addresses are `[10.244.0.97:7800]`
2025-02-04 08:22:47,954 INFO  [org.keycloak.quarkus.runtime.storage.database.liquibase.QuarkusJpaUpdaterProvider] (main) Initializing database schema. Using changelog META-INF/jpa-changelog-master.xml
2025-02-04 08:23:06,758 WARN  [io.agroal.pool] (main) Datasource '<default>': JDBC resources leaked: 3 ResultSet(s) and 0 Statement(s)
2025-02-04 08:23:06,759 WARN  [io.agroal.pool] (main) Datasource '<default>': JDBC resources leaked: 156 ResultSet(s) and 0 Statement(s)
2025-02-04 08:23:08,080 INFO  [org.keycloak.connections.infinispan.DefaultInfinispanConnectionProviderFactory] (main) Node name: keycloak-0-16699, Site name: null
2025-02-04 08:23:08,755 INFO  [org.keycloak.broker.provider.AbstractIdentityProviderMapper] (main) Registering class org.keycloak.broker.provider.mappersync.ConfigSyncEventListener
2025-02-04 08:23:08,786 INFO  [org.keycloak.services] (main) KC-SERVICES0050: Initializing master realm
2025-02-04 08:23:16,758 INFO  [org.keycloak.services] (main) KC-SERVICES0077: Created temporary admin user with username user
2025-02-04 08:23:16,867 WARN  [io.agroal.pool] (main) Datasource '<default>': JDBC resources leaked: 3 ResultSet(s) and 0 Statement(s)
2025-02-04 08:23:17,573 INFO  [io.quarkus] (main) Keycloak 26.1.0 on JVM (powered by Quarkus 3.15.2) started in 48.790s. Listening on: http://0.0.0.0:8080
2025-02-04 08:23:17,573 INFO  [io.quarkus] (main) Profile dev activated.
2025-02-04 08:23:17,574 INFO  [io.quarkus] (main) Installed features: [agroal, cdi, hibernate-orm, jdbc-postgresql, keycloak, narayana-jta, opentelemetry, reactive-routes, rest, rest-jackson, smallrye-context-propagation, vertx]
2025-02-04 08:26:26,355 WARN  [org.keycloak.events] (executor-thread-3) type="LOGIN_ERROR", realmId="cad3ad9b-90fb-438a-9e56-52d614915a5f", realmName="master", clientId="security-admin-console", userId="null", ipAddress="10.244.0.1", error="user_not_found", auth_method="openid-connect", auth_type="code", redirect_uri="http://127.0.0.1:64648/admin/master/console/", code_id="09213ee1-ea2e-4d80-b554-06d8e60e67a4", username="admin"