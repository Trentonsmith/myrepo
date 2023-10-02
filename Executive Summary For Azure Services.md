# Executive Summary For Azure Services

## Virtual network

- Used to connect azure resources (VM's, storage, etc.) to each other, the internet, and on premise resources

- Can use a public IP address for outbound and inbound connections

- Can be peered to to other virtual networks

- Can allow you filter and route network traffic 

  ###           Connect to on Prem resources

  - Point to site - established between single on prem computer and the AZ VNET

  - SITE to SITE - established between On-Prem VPN device and Azure VPN Gateway, allows any authorized devices on on-prem to access AZ VNET

  - ExpressRoute, connect to AZ VNET without internet

    ### Filtering

    - network security groups are firewalls for azure resources

    - Network virtual appliances Like a firewall, WAN optimizer and more

      ### Routing

      - Route tables available
      - BGP routes from on prem if using VPN Gateway

      

      

      

## Network Security Groups

- Used to filter networking inbound and outbound to and from azure resources.
- Have rules that can specify source, destination, port and protocol
- rules have: name, priority, source or destination, protocol, direction (inbound or outbound), port range, action

