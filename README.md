# Depiction of Juju Lifecycle Events
This repository includes PlantUML files that can be used to generate the sequence of lifecycle events that are triggered as a result of some user commands entered via the Juju client, e.g. deploy. Note that the repository also includes the output "png" files. 


The following are covered:

1. deploy - Command to deploy an Application.

![deploy](deploy.png)

2. add-unit / scale - Command to add a Unit to an existing Application.

![add-unit/scale](add-unit-or-scale.png)

3. upgrade-charm - Command to upgrade a Charm.

![upgrade-charm](upgrade-charm.png)

4. configure - Command to configure an existing Charm.

![configure](configure.png)

5. remove-unit - Command to remove a Unit for an existing Application.

![remove-unit](configure.png)

6. remove-application - Command to remove an existing Application (reverse of "deploy").

![remove-application](remove-application.png)

7. add-storage - Command to add storage to an existing Application.

![add-storage](add-storage.png)

8. remove-storage - Command to remove storage from an existing Application.

![remove-storage](remove-storage.png)

9. add-relation - Command to a Relation.

![add-relation](add-relation.png)

10. relate - Command to relate an Application to another.

![relate](relate.png)

11. remove-relation - Command to remove an existing relation.

![remove-relation](remove-relation.png)


In addition, the following lifecycycle events are provided:

1. Leader election - The sequence of lifecycle events when a leader unit is elected.

![leader-election](leader-election.png)

2. Set relation data - The sequence of events when data are set by another Application in the same Relation.

![set-relation-data](set-relation-data.png)
