# ELK-Networking
This repository contains different configurations for logstash 5.4.0, elasticsearch 5.4.0 and kibana 5.4.0.

Devices / Products included:

- Firewall Palo Alto traffic and URL.
- Firewall Juniper NetScreen.
- Firewall Juniper SRX.
- Bluecoat SG traffic.
- Bluecoat SG SysLog.
- Arbor Pravail DDoS.
- Proxy Squid.
- Nginx WebServer.

# Logstash
Configuration files directory: /etc/logstash/conf.d/

# Elasticsearch 
Templates: 

Just paste entire text files into your development console in Kibana.

Or execute this on your elasticsearch server:

curl -XPUT localhost:9200/_template/name -d '
{
content
}
'
# Kibana

Visualizations (import json on kibana -> Management -> Saved objects)

Dashboards (import json on kibana -> Management -> Saved objects)
  
