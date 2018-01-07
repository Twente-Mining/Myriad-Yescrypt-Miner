# Myriad Yescrypt Miner
Donations are welcome =)





Options:

  -o, --url=URL         URL of mining server

  -O, --userpass=U:P    username:password pair for mining server

  -u, --user=USERNAME   username for mining server

  -p, --pass=PASSWORD   password for mining server

      --cert=FILE       certificate for mining server using SSL

  -x, --proxy=[PROTOCOL://]HOST[:PORT]  connect through a proxy

  -t, --threads=N       number of miner threads (default: number 
of processors)

  -r, --retries=N       number of times to retry if a network call fails
                          (default: retry indefinitely)

  -R, --retry-pause=N   time to pause between retries, in seconds (default: 30)	

  -T, --timeout=N       timeout for long polling, in seconds (default: none)

  -s, --scantime=N      upper bound on time spent scanning current work when
                          long polling is unavailable, in seconds (default: 5)

      --coinbase-addr=ADDR  payout address for solo mining

      --coinbase-sig=TEXT  data to insert in the coinbase when possible

      --no-longpoll     disable long polling support

      --no-getwork      disable getwork support

      --no-gbt          disable getblocktemplate support

      --no-stratum      disable X-Stratum support

      --no-redirect     ignore requests to change the URL of the mining server

  -q, --quiet           disable per-thread hashmeter output

  -D, --debug           enable debug output

  -H, --hashdebug enable hash debug output

  -P, --protocol-dump   verbose dump of protocol-level activities

      --benchmark       run in offline benchmark mode

  -c, --config=FILE     load a JSON-format configuration file

  -V, --version         display version information and exit

  -h, --help            display this help text and exit