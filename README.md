# graphgist
"Tracking your home address with the help of your home devices" an application of Internet of Things.
The idea behind this model is that, we can track the home address with the help of devices associated with a home. As we know that IoT is an emerging technology which is viewed to be one of the "hottest" topic in future and according to Gartner, around 20 billion devices will be connected to internet in 2020. So this model is mostly describe how our home devices will become useful to track our home address.

Summary of the model:
I have used several nodes and relationship with this nodes.
NODE:HOME,PERSON,DEVICE
Relationship:Registered_with,Device_of,Owner,Member,Friend
Here home node is there to which a device node and person node is associated with.Also how this nodes are related to each other is shown.

Details of each node:
HOME node property(name,address)
PERSON node property(name,email,mobile)
DEVICE node property(name,address) (Note:each address of the device is unique)
