The OpenFaaS environment is being prepared, wait for 2 minutes to let it up and you will 
see the OpenFaaS Gateway URL in the terminal aside. 

### OpenFaaS Design & Architecture
Below is the design and Architecture of OpenFaaS.

![OpenFaaS Architecture](https://docs.openfaas.com/images/of-conceptual-operator.png)

### Kubernetes Dashboard
To access the dashboard, click on the Kubernetes Dashboard tab above the command line or from this link: 
https://[[HOST_SUBDOMAIN]]-30000-[[KATACODA_HOST]].environments.katacoda.com/. 
At the sign in prompt select Token and paste in the token, you copied a moment ago.

`echo -e "\n--- Copy and paste this token for dashboard access --\n$TOKEN\n---"`{{execute}}

### Access the OpenFaaS Gateway

To interact with OpenFaaS through its portal, access the OpenFaaS Gateway on the tab or from 
this link: https://[[HOST_SUBDOMAIN]]-31112-[[KATACODA_HOST]].environments.katacoda.com/

When asked about credentials enter the username as `admin` and password as revealed below:
`echo -e "The OpenFaaS portal will need these credentials when prompted:\nuser: admin\npassword: $PASSWORD"`{{execute}}

Once login you should be able to see the dashboard and option to deploy function.