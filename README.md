# NB1-NODE
<br/>
The (Tiny) NB1-Node is a very neat development platform to experiment NB1. It is based on the Quectel BC66 module, it has an STM32L071 processor ( you could mount on the same footprint also an L4), USB connection that mimics exactly the Quectel BC66 EVK ( same chip same drivers ) so you can use all of Quectel tools, an on board 2Mbit Flash ( should we try some FOTA over NB1?? ), and last but not least a LiPO connector and charging circuit for testing on the field.<br/>
<br/>
Here picture of top and bottom.<br/>
<br/>
<br/>
<img src="/docs/nb1_node_top.jpg"/>
<br/>
<img src="/docs/nb1_node_bottom.jpg"/>
<br/>
<br/>
As you can see from the bottom silkscreen we also have part of the STM32L0 ports exposed on the external headers, so that you can very quickly develop your own sensors.

