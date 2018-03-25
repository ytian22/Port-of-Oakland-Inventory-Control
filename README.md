# Port of Oakland Inventory Control
The jupyter notebook shows the process of Monte-Carlo and Bootstrapping simulations and hypothesis tests on 4,989 observations to evaluate the statistical significance for a new inventory-controlling system. <br>

### Business
The Port of Oakland is one of the largest ports on the west coast of the United States. Its business is done via containerization methods: 40 and 20 foot containers are put directly from ships onto trucks and rail. <br>

### Problem
Some freight is unpackaged and repackaged onto other transportation methods at the port, which leads to a severe problem as the operators need to decide when and how to ship it. The operators are most efficient when trucks are operating at capacity, but with different size loose materials coming into different destinations maintaining efficiency is challenging.

### Current Solution
The port currently uses a software, written in the early 1980’s, that attempts to maximize revenue using algorithms. It leverages the company’s historical shipping record to anticipate the likelihood of a truck being full. 

### New Solution
A new, silicon-valley startup is attempting to disrupt this industry. It offers some desirable features such as sending TXT notifications, an internet enabled interface and a mobile app. The company has also offered to let the port use the software on a trial basis for a few days before committing.

### Test
The test ran on an otherwise average Friday, with 4,989 trucks leaving the port. Monte-Carlo and bootstrapping simulations were run to evaluate the statistical significance of the test.
