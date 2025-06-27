FROM solr:8.11.1

# argument variables to define

# copy the solr configset from WebAPI
COPY --chown=solr /solr /var/solr/data/v5.0_27-FEB-25

# copy your JDBC file
COPY --chown=solr postgresql-42.7.5.jar /opt/solr-8.11.1/server/lib/postgresql-42.7.5.jar
