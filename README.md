# centos7-tomcat-for-filebeat

run with : docker run -d -P --env FRPASSWD=&lt;passwd&gt; --env FRLICENSE=&lt;license&gt; btooncall/centos7-tomcat-for-filebeat

investigate ports : docker port &lt;container_id&gt;

watch logs : docker logs -f &lt;container_id&gt;

shell inside container : docker exec -it &lt;container_id&gt; /bin/bash
