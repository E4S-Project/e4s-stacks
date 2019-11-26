# Spack Environments for ECP Facilities

This is a first pass at collecting Spack environments from ECP facilities
in a central location.  There's a directory per facility, and inside is
whatever they're currently using (or want to use) to build their stack
with Spack.

The goals are to:
1. Get each stack building in a CI pipeline at its local facility.
2. Union these configs into a single environment to be incorporated into E4S.

## Stacks

The following are the stacks we have so far:

* `olcf`: OLCF's Spack Environments
  * Originally pulled from https://github.com/mpbelhorn/olcf-spack-environments
* `alcf`: Tests & localization settings for Theta at ALCF
