I've contacted docker support team, and according to their response, the current limits on Automated Builds are:

- 2 hours
- 2 GB RAM
- 1 CPU
- 30 GB Disk Space

So, for larger builds you have to either break them into several Automated Builds connected by FROM statements and Repository Links, or build them locally on your machine and push them to the repository.

this is cuda base build.