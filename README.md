# SPR-MOEAD-for-HEGLRP
Data of test instances

The first set is the classic LRP benchmark instances provided by Barreto et al. (2007).
Their instances range from 21 to 150 client node and 5 to 15 depot node. This set was then adapted by Lv et al. (2022) for the hybrid LRP and our tests are based on the adapted instances.

The second LRP instance set is provided by Tuzun & Burke (1999) with clients range from 100 to 200 and depots range from 10 to 20.
To make the set applicable to hybrid LRP, Lv et al. (2022) adapted it by dividing the client nodes into the retailer and customer nodes and the depots are served as distribution centers, which fits our tackled problem.

The third set focus on large-scale LRP over 300 nodes and is adapted from the biggest shared bike system in New York, the Citi Bike.
This set of instances provide client nodes from 303 to 519 and depot nodes from 20 to 30.
The instances are tested by Lv et al. (2020) and adapted into the hybrid LRP by Lv et al. (2022) using the similar way to the second set.

All the instances are represented in the form of [name]-[DC]-[OR]-[OC], where [DC], [OR] and [OC] represents the number of DC node, OR node and OC node in the instance, respectively.
