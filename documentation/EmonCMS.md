## Emoncms.org

> Emoncms is a powerful open-source web-app for processing, logging and visualising energy, temperature and other environmental data. Part of the OpenEnergyMonitor.org project.

- [EnomCMS Homepage](http://www.emoncms.org/)
- [OpenEnergyMonitor Homepage](OpenEnergyMonitor.org)

1. Go to [EmonCMS](http://emoncms.org) and sign up
2. From [My Account](http://emoncms.org/user/view) get
   - Username
   - Write API Key (Also known as Read & Write API Key)
   - Read API Key


### Inputs

- [Input API](http://emoncms.org/input/api)

- Create an Input called "MyInput"
```sh
    http://emoncms.org/input/post.json?json={MyInput:0}&apikey=
```
- Go to [Inputs](http://emoncms.org/input/view)


    Inputs
    
    Node:	Key	Name	Process list	last updated	value
    0	MyInput			6 mins ago	0			

### Dashboards

- Select __New__ called "MyDashboard"


    Id	Name	Alias	Main	Public	Published					
    29834	MyDashboard									