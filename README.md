    This Project is to display Running Ports and Services on a certain IP Address.

    API's exposed :
        1. /ipAddress
        
    <!-- DB schema :

	    1. ip
	        a. port
	        b. service
     -->

    APIs

    1. /ipAddress
         Request Format :

        POST Request to :
                            frontend/ipAddress


        #<post-params>

            {
               “ip”: “52.66.138.74”
               
            }

   		Response Format :

            {
              "ip" : "52.66.138.74",
              "domain_name" : "vimmey.com",
              "isp" : "amazon.com",              
              "ports" : "443","23" 
              "service" : "https", "ssh"
            }


    