# varnish4.1-el6

### Debugar requisições de invalidação do cache (purge) no servidor Varnish:
`varnishlog -g request -q 'ReqMethod eq "PURGE"'`
