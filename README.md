# K-means Clustering:  Isotopic Composition Plutonium Batches

![A left-hand with 'I'm a lefty' written on it](https://imgur.com/2ksgRt3.png)
<a href="https://www.analyticsvidhya.com/blog/2021/04/k-means-clustering-simplified-in-python/"> Image courtesy of Analytics Vidhya</a>

This data is fairly odd and K-Means may not be ideal for it in certain respects, but the takeaway is that it can do an ok job with whispy, elongated shapes.  

(A more ideal model is probably DBSCAN or a hierachical clustering.)

Here's our [data dictionary](https://vincentarelbundock.github.io/Rdatasets/doc/cluster/pluton.html) for the interested:

    Pu238: the percentages of (238)Pu, always less than 2 percent.

    Pu239: the percentages of (239)Pu, typically between 60 and 80 percent (from neutron capture of Uranium, (238)U).

    Pu240: percentage of the plutonium 240 isotope.

    Pu241: percentage of the plutonium 241 isotope.
