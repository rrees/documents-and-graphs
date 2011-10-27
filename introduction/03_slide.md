!SLIDE bullets

# The requirement #

* Who creates ideas with keywords that match the keywords of my request?

!SLIDE

# A naive solution #

!SLIDE bullets

* Create a Couch view that maps keyword to user

!SLIDE code small

	if doc.role {
		for (var idx in doc.role) {
			keyword = doc.role[idx]
			doc.emit([doc.role, keyword], doc._id)
		}
	}

!SLIDE center

<img src="trap.png"/>

!SLIDE bullets incremental

#The pressure of evolution #

* Relationships to ideas become richer
* Entities start to be linked in many different ways

!SLIDE bullets incremental

#View creation will become unmanageable#

* Every new role
* Every new interaction with an idea
* Results in a new view

!SLIDE 

# Enter Neo4J #

