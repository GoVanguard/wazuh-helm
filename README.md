wazuh-helm (https://govanguard.io)
==

## Authors:
Shane Scott

## About
Wazuh-helm is a helm template for deploying Wazuh.

Current design allows one to dictate individal image verions, image sources and optionally use an external elasticsearch or a launch a built in cluster.

Notes:
 - AWS managed ElasticSearch, while able to technically work with Wazuh if using a kibana-oss sourced image, performs very poorly under load. I do not know why this is.

## Credits
Portions of code and concepts from wazuh/Wazuh-Kubernetes, Copyright (C) 2018 Wazuh Inc.
