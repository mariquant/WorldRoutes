#WorldRoutes

World marine routes database is provided for any purpose under the [￼Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode). You can get information about the license [here](https://creativecommons.org/licenses/by/4.0/)

Description of the approach can be found in our article on [Medium]()

The data consists of three files:
1.	Port-to-port distances calculated along the routes (distances.csv).
1.	Port-to-port routes as discussed in the article (routes.csv).
1.	We can’t provide you with the port polygons, however, we provide the reference data consisting of our internal index, [World Port Index](https://msi.nga.mil/NGAPortal/MSI.portal?_nfpb=true&_pageLabel=msi_portal_page_62&pubCode=0015) INDEX_NO, and PORT_NAME if any (or any available name we have) and a tuple of coordinates of the port polygon representative point. Representative point of the harbour polygon is obtained using geopandas representative_point() method (ports.csv).

