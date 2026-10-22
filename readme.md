# MAD row-center regression evidence

The figure compares measured `median_abs_deviation` outputs on the synthetic input `[[0, 2], [10, 12]]`, with `center=[1, 11]` and `scale=1`. The reference is computed separately for each row as `median(abs(row - center))`.

- Before: `cc441486e3ca68212dec5deb5b0adf29abaa04f7`
- After: `c34d7717deb64f1df72248ae17f0e25b8809fcc1`
- Measured values, including the rectangular-input exception: `mad-measurements.json`
- Figure: `mad-row-centers.png`, 16 cm wide at 420 dpi.

These are small regression inputs, not satellite observations or a performance benchmark.
