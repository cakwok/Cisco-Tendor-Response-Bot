Operation Manual
----------------
1.  Modify the inventory list at

eg, adding a new inventory from

inventory = ["Cisco 9400 C9400-SUP-1XL-Y", "Cisco Catalyst 9600 Series Supervisor Engine 1", "Cisco 9800-80",
             "Cisco Nexus 9500", "Cisco NCS 5500"]

to

inventory = ["Cisco 9400 C9400-SUP-1XL-Y", "Cisco Catalyst 9600 Series Supervisor Engine 1", "Cisco 9800-80",
             "Cisco Nexus 9500", "Cisco NCS 5500", "Cisco IE4000"]

2.  Modify tendor parameter.  eg, changing this line from "temperature" to "mtbf"

SearchString = self.model.replace(" ", "+") + "+mtbf"
