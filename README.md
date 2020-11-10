Minor-test 2 - Test This application is intended to be used for ECS size calculations. 

<b>Installation</b><p>
Not much to do. All of the code resides in the html file. Open the file on your phone or desktop. 
It is responsive HTML, so it will still look good on your phone.

<b>Help</b><p>
Erasure Coding options include Active (1.33) and Cold (1.2).

Active erasure coding has 12 data and 4 parity ("12 + 4"). That means you can lose up to 4 of the erasure coding parts without losing data.

Cold erasure coding has 10 data and 2 parity ("10 + 2"). You must have at least 6 nodes to use this erasure coding.

How many units? Well, how many VDCs? NOT racks, because multiple racks can make up a system/VDC.

How many Data Centers? IOW, how many sites?

FYI, only 8 can be grouped in a federation.
How many sites are writes spread across? IOW, at how many sites are applications writing to these systems? This is important, because having 3 sites does not guarantee efficiencies. Writes must occur at other sites.

Average object size? This matters, because all objects have metadata. More, smaller files means more overhead.

Drives per node - How many drives are attached to each node?

Size of Drives (TiB)- Depending on the system, this may be 8, 10, or 12 right now, unless this is software only.

Nodes per system - If you have multiple racks, this includes all nodes in the single system. This is NOT all sites. This is systems per site. A single Gen 2 can have 8 nodes per rack. EX is more.
