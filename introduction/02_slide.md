!SLIDE 

# Infrastructure survey #

!SLIDE bullets incremental

# Our main store is CouchDB #

* Low maintenance
* HTTP/JSON
* Great replication
* The model is right

!SLIDE 

#Ideas have document properties #

!SLIDE bullets

# Other advantages of using a document store #

* Combines with functional programming powerfully
* Has helped keep us agile and responsive

!SLIDE bullets

# A disadvantage #

* No ad-hoc queries

!SLIDE bullets

# Elasticsearch #

* Integrates easily
* Dynamic types save effort
* Adhoc fast queries
* Powerful grouping and filtering

!SLIDE 

# Disadvantages #

* Dynamic typing cannot handle JSON collections
* Search documents are independent (no joins)

!SLIDE bullets

* Elasticsearch cannot help here without custom types
* Unroll collections into the search document
