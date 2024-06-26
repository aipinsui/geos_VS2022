2024-06-05

- Fixes:
  - Intersection: change to using DoubleDouble computation to improve robustness (GH-937, Martin Davis)
  - Fix build on Illumus (GH-971)
  - Buffer mitre join error (GH-995, Paul Ramsey)
  - Return 2D empty linestring on GEOSGeom_createLineString(NULL) (GH-998, Paul Ramsey)
  - Fix DiscreteHausdorffDistance for LinearRing (GH-1000, Martin Davis)
  - PointOnSurface crashes with a collection containing a empty linestring (GH-1002, Paul Ramsey)
  - Fix IsSimpleOp for MultiPoint with empty element (GH-1005, Martin Davis)
  - Fix PreparedPolygonContains for GC with MultiPoint (GH-1008, Martin Davis)
  - Fix TopologyPreservingSimplifier to prevent jumping components (GH-1012, Martin Davis)
  - Fix reading WKT with EMPTY token with white space (GH-1025, Mike Taves)
  - Segfault in CoverageSimplify for non-polygonal inputs (GH-1039, Paul Ramsey)
  - Fix buffer Inverted Ring Removal check (GH-1056, Martin Davis)
  - CoveragePolygonValidator: add section performance optimization (GH-1099, Martin Davis)

