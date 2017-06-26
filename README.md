# Data Science in Apache Spark 
## Exploring the Global Terrorism Database Dataset

**Level**: Moderate
**Language**: Scala
**Requirements**: 
- [HDP 2.5](http://hortonworks.com/products/sandbox/) (or later) or [HDCloud](https://hortonworks.github.io/hdp-aws/)
- Spark 1.6.x
- Download GTDB dataset https://www.kaggle.com/START-UMD/gtdﬂ

**Author**: Ian Brooks
**Follow** LinkedIn - Ian Brooks PhD (https://www.linkedin.com/in/ianrbrooksphd/)

## Context
Information on more than 150,000 Terrorist Attacks

The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2015 (with annual updates planned for the future). The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 150,000 cases. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland. [More Information] (http://start.umd.edu/gtd/)

## Instructions 
1. Using the provided link, please download [HDP Sandbox.] (https://hortonworks.com/products/sandbox/?gclid=CMr9tJ7a8tMCFYmffgodizMGSQ)  For assistance, please use the following [tutorial] (https://hortonworks.com/tutorial/sandbox-deployment-and-install-guide/) for assistance. 

2. Using the provided link, please download Global Terrorism Database CSV file from [Kaggle.] (https://www.kaggle.com/START-UMD/gtd)  Note: You will need a Kaggle account. 

3. Using the provided link, please download the [Zeppelin Note.] (https://github.com/BrooksIan/SacWomenInData) 

4. Launch HDP Sandbox. 

5. Log into Apache Ambari as User: raj_ops & Password: raj_ops

6. In Ambari, select "Files View" and upload GTDB CSV file to the /tmp/ directory.  For assistance, please use the following [tutorial.] (https://fr.hortonworks.com/tutorial/loading-and-querying-data-with-hadoop/)

7. In Zeppelin, import the Zeppelin Note JSON file. 


## License
Unlike all other Apache projects which use Apache license, this project uses an advanced and modern license named The Star And Thank Author License (SATA). Please see the [LICENSE](LICENSE) file for more information.
