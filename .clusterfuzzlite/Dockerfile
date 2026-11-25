# ClusterFuzzLite build image for GlyphGuard's Atheris fuzz targets (see tests/fuzz/).
FROM gcr.io/oss-fuzz-base/base-builder-python@sha256:5a20f6927f4157bafbb9f66eb62a99dd9e6e92ed94b10ffaee4262b9bedac08a
COPY . $SRC/glyphguard
WORKDIR $SRC/glyphguard
COPY .clusterfuzzlite/build.sh $SRC/
