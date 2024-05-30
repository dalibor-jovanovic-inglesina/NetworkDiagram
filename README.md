# Network Diagram
A Web Based Network Diagram written in html-css-javascript to generate a colored map of your network populated in the data.yaml file.

# Setup
Edit the data.yaml file under devices section to configure Devices:
- name: 'Device Name'
- color: 'Devices Color (rgba)'
- ip: 'Devices Ip'

Edit the data.yaml file under connections section to configure Connections:
- from_device: 'Source Device Name'
- from_port: 'Source Port'
- to_device: 'Destination Device Name'
- to_port: 'Destination Port'

