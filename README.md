wazuh-helm (https://govanguard.com).
==

## Authors:
Shane Scott

## About
Wazuh-helm is a helm template for deploying Wazuh.

Current design allows one to dictate individal image verions, image sources and optionally use an external elasticsearch or a launch a built in cluster.

Latest tested images:
 * wazuh: 3.12.3
 * wazuh-nginx: 3.12.3
 * wazuh-kibana: 3.12.3
 * elasticsearch: 7.6.2

Lots of room for improvement on this. Open to pull requests.

Notes:
 - AWS managed ElasticSearch, while able to technically work with Wazuh if using a kibana-oss sourced image, performs very poorly under load. I do not know why this is.

## Credits
Portions of code and concepts from wazuh/Wazuh-Kubernetes, Copyright (C) 2018 Wazuh Inc.
