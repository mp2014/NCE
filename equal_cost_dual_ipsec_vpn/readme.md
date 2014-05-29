### NCE Document
http://www.juniper.net/techpubs/en_US/release-independent/nce/information-products/topic-collections/nce/nce0098-chassis-cluster-single-srx/chassis-cluster-single-srx-configuring.pdf

### Usage
First check & update configuration details specified in the datavars.yml file, then run:

````
python render.py
````

You should see a print-out of the rendered configuration. This configuration can be imported on a Junos device with the 'load merge terminal' command.

Tested on vSRX (12.1X44-D20.3)
