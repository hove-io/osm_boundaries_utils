:warning: This is forked from [Qwant/osm_boundaries_utils_rs](https://github.com/Qwant/osm_boundaries_utils_rs) which seems unmaintained (see https://github.com/Qwant/osm_boundaries_utils_rs/pull/20#issuecomment-1431388362).
Note however that we were able to get back the rights for crates.io so the crate's name remains :tada:

# osm_boundaries_utils

Misc utilities for OpenStreetMap boundary reading in rust.

This library provides mainly a method to compute the boundary of an OSM relation (as a geo::MultiPolygon).

It also provides as osm_builder utility to create osm datasets, mainly to write osm tests easily.

# Build

`cargo build`

# Test

`cargo test`

# Licence
This work is free. You can redistribute it and/or modify it under the terms of the Do What The Fuck You Want To Public License, Version 2, as published by Sam Hocevar. See the COPYING file for more details.
