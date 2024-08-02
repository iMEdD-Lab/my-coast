# my-coast
Public data about the leasing of beaches in Greece

Notes on the columns of the dataset:

- **prefecture**: The administrative region.
- **municipality**: Contains municipalities, but in some cases also includes demotic units.
- **area**: The location of the beach.
- **purpose**: This column has been re-categorized into 11 categories.
- **start_date**: Indicates the start of the lease.
- **end_date**: Indicates the end of the lease.
- **area_size**: The area in square meters. Some values have been corrected, while missing values have been filled in by secondarily calculating the area of the polygons.
- **extracted_price**: The price per year in euros that we have been able to extract from the agreements found in Diavgeia.
- **x**: The longitude in meters. It is mapped on the map using the Coordinate Reference System (CRS) with the code EPSG:3857, also known as WGS 84 / Pseudo-Mercator or Web Mercator.
- **polygons**: The polygons that depict on the map the exact area that has been leased or concessioned.
