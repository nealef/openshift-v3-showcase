#
# Derived entirely from the work of https://github.com/sebastianfaulhaber
#
FROM 	sinenomine/websphere-liberty:webProfile6

# Add binary deployment artifact to 'dropins' folder
#RUN wget --directory-prefix=/opt/ibm/wlp/usr/servers/defaultServer/dropins/ $BINARY_DEPLOYMENT_ARTIFACT_URL
COPY 	app/* /opt/ibm/wlp/usr/servers/defaultServer/dropins/

# IBM WebSphere Liberty license must be accepted
ENV 	LICENSE $LICENSE
