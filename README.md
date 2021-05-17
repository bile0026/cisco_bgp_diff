# cisco_bgp_diff

Runs a diff between 2 Cisco router BGP tables.

The first time it runs, it will create a file with the hostname in dumps/<hostname>.txt, then the second time it creates a file with -new at the end. It will then diff these 2 files and create a vimdiff .html file in `diffs/`.

Remember to clear the dumps folder before running a new set of tests.
