## Hazelcast Collections
Hazelcast implementations of distributed Maps <br />




### Technologies
Hazelcast Cache, Maps <br />
 

### Exmaples
Multi-map: <br />
Store values in a map <br />

Aggregations, Fast Aggregations: <br />
Calculations on map content <br />

Mapstore: <br />
Store map data in a relational database <br />
Persistence <br />


### Steps
##### Multi-map
*mvn clean compile package* <br />
java -cp target/lib/*:target/classes PutMember <br />
java -cp target/lib/*:target/classes PrintMember <br />


##### Aggregations
*mvn clean compile package* <br />
./start-aggregations.sh <br />


##### Fast-Aggregations
*mvn clean compile package* <br />
./start-fast-aggregations.sh <br />


##### Mapstore
*mvn clean compile package* <br />
./loadAll.sh <br />






