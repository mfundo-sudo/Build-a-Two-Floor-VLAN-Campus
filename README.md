# Build-a-Two-Floor-VLAN-Campus

Place the campus
  Lay out two access floors and one shared router before adding cables.

Cable both floors
  Connect the access hosts, then build the two-link campus backbone.

Address the departments
  Use one IPv4 subnet and gateway per department on both floors.

Build the access VLANs
  Create the same two departments on each floor and assign their edge ports.

Carry VLANs between floors
  Turn the shared backbone links into trunks for both department VLANs.

Route between the VLANs
  Use two tagged subinterfaces so one router port can serve both gateways.

Prove the campus paths
  Test each VLAN across floors, then cross the router between departments.
