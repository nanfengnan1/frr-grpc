This is a grpc unit test for having achieve northbound api
----------------------------------------------------------

frrouting
=========

1. using master branch as grpc source
2. /usr/lib/frr/zebra -d -M grpc:<port> -F traditional -A 127.0.0.1

grpc client
===========

we should access grpc-server using `port` by frrouting daemon listened
