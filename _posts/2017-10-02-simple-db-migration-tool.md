> Simplicity is prerequisite for reliability.
>
> -- Edsger W. Dijkstra 

One of the common problem with web-based application is how to handle database migration. Often times the answer to this is to use the migration tool that comes with the [ORM](https://martinfowler.com/bliki/OrmHate.html) the system relies on. 

In the past, as the system grew to use multiple layers each with its own runtime / language / ORM , I was forced to maintain db migration in one of the layer. Thus I came to realize that an ORM agnostic db migration tool would be the ideal approach. 

One of the simplest db migration tool I have encountered is [**shmig**](https://github.com/mbucc/shmig) - A database migration tool written in BASH consisting of just one file! Shmig even supports creating test data (which is another gnarly issue worth a blog post). 

If you are looking for a db migration tool I reccomend you take a look at [**shmig**](https://github.com/mbucc/shmig).
