# ResourceManager

The ResourceManager is a repository and document management system implemented in Java and based on Neo4J which, in conjunction with the AuthorityManager, enables user and group-related management (upload, download, management) of any resources.

The ResourceManager is accessible via REST and the API allows you to perform operations on specific resources, such as image segmentation.

## Database
The Resource Manager uses Neo4J as a database to store the resources. These resources do not have to be physically available in the ResourceManager, but can also be stored in external databases.

Examples:
* MongoDB
* Hadoop
* mySQL


## API
The API can be accessed at: http://api.hucompute.org/?url=https://resources.hucompute.org/api


## Cite
If you want to use the API, please quote this as follows:

R. Gleim, A. Mehler, and A. Ernst, “SOA implementation of the eHumanities Desktop,” in Proceedings of the Workshop on Service-oriented Architectures (SOAs) for the Humanities: Solutions and Impacts, Digital Humanities 2012, Hamburg, Germany, 2012. [PDF](https://www.texttechnologylab.org/wp-content/uploads/2015/08/dhc2012.pdf).


## BibTeX
```
@InProceedings{Gleim:Mehler:Ernst:2012,
  Author         = {Gleim, Rüdiger and Mehler, Alexander and Ernst,
                   Alexandra},
  Title          = {SOA implementation of the eHumanities Desktop},
  BookTitle      = {Proceedings of the Workshop on Service-oriented
                   Architectures (SOAs) for the Humanities: Solutions and
                   Impacts, Digital Humanities 2012, Hamburg, Germany},
    pdf            = {https://www.texttechnologylab.org/wp-content/uploads/2015/08/dhc2012.pdf},
  year           = 2012
}
```
